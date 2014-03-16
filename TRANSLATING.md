Translating fish
================

Preparations
------------

Before starting a new translation or updating an existing translation, please ensure that the `message.pot` and derived `.po` files are up-to date

    make messages.pot po/ll.po

with ll being the language locale for a new or existing target language (i.e. de for German).

Recommended process
-------------------
- Use Lokalize as application
- Resolve all pre-existing fuzzy translations
- Use Google to get an automatic translation of the missing entries as template
    - Go to [Google Translator Toolkit](http://http://translate.google.com/toolkit/) and login with an Google Account
    - Upload your current `ll.po` file of choice
    - Skip the commercials offers, save and download the automatically translated file 
    - Now use Lokalize _Sync Mode_ to iteratively adopt and modify the translation proposals
