# Cockpit i18n / Backend translation files

Language files for Cockpit's backend


## Usage

Just copy the language files you need to `/config/cockpit/i18n`. After that you will be able to change the language of Cockpit users in the user management.

You can create the `/config/cockpit/i18n` folder and a ready to translate file executing the following cli command:
```bash
./cp create-lang --lang [code]
```

To add TinyMCE (the WYSIWYG component) language files, download the desired language from [here](https://www.tiny.cloud/get-tiny/language-packages) and put the JS file on `/storage/assets/cockpit/i18n/tinymce` folder.

If any folder mentioned above is missing, just create it. Keep in mind to keep webserver permissions for those folders.
