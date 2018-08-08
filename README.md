# CKFinder 3 Translations

This repository contains language files for **CKFinder 3**.

There are two branches available:
* `master` &ndash; Language files from the **latest stable CKFinder release**.
* `major` (default) &ndash; Language files from the **most current development snapshot** of the next CKFinder release. May contain language strings for new features that are not published in any release available now.

## Contributing

This repository was created to simplify the process of updating or providing new language files.

You are welcome to help **localize CKFinder** into your native language and update existing localizations. You can use one of the methods described below to submit your translation. **Your help will be much appreciated!**

**Important notes:**

CKFinder language files are in JSON format. A few language strings contain some HTML tags like `<strong>` or placeholders such as `{name}` or `{count}`. Please leave these untouched as changing them may prevent CKFinder from working correctly.

All untranslated entries are marked with `[MISSING]`. When you translate, remove the `[MISSING]` part to mark the translation "done" and provide your localization. For example:

Untranslated:

	"deleteFiles": "[MISSING]Delete Files",
	
Translated:

	"deleteFiles": "Dateien löschen",
	
## Creating a Pull Request

If you are familiar with Git, you can fork this repository and submit a [pull request](https://github.com/ckfinder/ckfinder-translations/pulls) with your changes for the `major` branch.

## Editing Files on GitHub

Alternatively, you can edit existing language files directly on GitHub using its online code editor. Check the [step-by-step instructions](https://ckeditor.com/docs/ckfinder/ckfinder3/#!/guide/dev_translations-section-editing-files-on-github) for more information.

## Sending Translations by E-mail

Last but not least, if you are not familiar with Git and GitHub, please send us the translations to [info@cksource.com](info@cksource.com) and we will do the rest. Thank you!

## Adding New Languages

To add a new language file and use it in CKFinder, you need to adjust the configuration first:
  
  * [config.languages](https://ckeditor.com/docs/ckfinder/ckfinder3/#!/api/CKFinder.Config-cfg-languages) must be edited
    to include information about the newly added translation.
  * Optionally, you might need to set [config.language](https://ckeditor.com/docs/ckfinder/ckfinder3/#!/api/CKFinder.Config-cfg-language) 
    if the language detection mechanism turns on a different language by default.

Finally create an appropriate language file in the `lang` folder of CKFinder. Use `_template.json` as a base for creating 
your language file. Use the two-letter [ISO 639-1](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) language code 
as a name for the language file, optionally adding the two-letter [ISO 3166-1](http://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) 
country code as a suffix.

Example: For French (Canada), copy the `_template.json` file and save it as `fr-ca.json`.

When your translation is ready, you can share it by submitting a [pull request](https://github.com/ckfinder/ckfinder-translations/pulls) on GitHub or sending it to us to [info@cksource.com](info@cksource.com). We will be happy to add it to the official repository. Thank you for your help!

## Translating Edit Image Options

CKFinder includes some image editing options provided by [CamanJS](http://camanjs.com/). If you find some captions from this section unclear (like some filters or presets) and would like to see working examples of what these effects do, visit the CamanJS [Interactive Example](http://camanjs.com/examples/) page. Another idea is to check your favorite (localized) photo editing application for clues.

## License

Copyright (C) 2007-2015, CKSource - Frederico Knabben. All rights reserved.
