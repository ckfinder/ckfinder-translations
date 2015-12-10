# CKFinder 3 Translations

This repository contains language files for **CKFinder 3**.

## Contributing

This repository was created to simplify the process of updating or providing new language files.

You are welcome to help **localize CKFinder** into your native language and update existing localizations. You can use one of the methods described below to submit your translation. **Your help will be much appreciated!**

**Important note:** CKFinder language files are in JSON format. A few language strings contain some HTML tags like `<strong>` or placeholders such as `{pleaseWait}` or `{count}`. Please leave these untouched as changing them may prevent CKFinder from working correctly.

## Creating a Pull Request

If you are familiar with Git, you can fork this repository and submit a [pull request](https://github.com/ckfinder/ckfinder-translations/pulls) with your changes.

## Editing Files on GitHub

Alternatively, you can edit existing language files directly on GitHub using its online code editor. Check the [step-by-step instructions](http://docs.cksource.com/ckfinder3/#!/guide/dev_translations-section-editing-files-on-github) for more information.

## Sending Translations by E-mail

Last but not least, if you are not familiar with Git and GitHub, please send us the translations to [info@cksource.com](info@cksource.com) and we will do the rest. Thank you!

## Adding New Languages

To add a new language file and use it in CKFinder, you need to adjust the configuration first:
  
  * [config.languages](http://docs.cksource.com/ckfinder3/#!/api/CKFinder.Config-cfg-languages) must be edited
    to include information about the newly added translation.
  * Optionally, you might need to set [config.language](http://docs.cksource.com/ckfinder3/#!/api/CKFinder.Config-cfg-language) 
    if the language detection mechanism turns on a different language by default.

Finally create an appropriate language file in the `lang` folder of CKFinder. Use `en.json` as a base for creating 
your language file. Use the two-letter [ISO 639-1](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) language code 
as a name for the language file, optionally using the two-letter [ISO 3166-1](http://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) 
country code as a suffix.

Example: use `fr-ca` for French (Canada).

When your translation is ready, you can share it by submitting a [pull request](https://github.com/ckfinder/ckfinder-translations/pulls) on GitHub or sending it to us to [info@cksource.com](info@cksource.com). We will be happy to add it to the official repository. Thank you for your help!

## Translating Edit Image Options

CKFinder includes some image editing options provided by [CamanJS](http://camanjs.com/). If you find some captions from this section unclear (like some filters or presets) and would like to see working examples of what these effects do, visit the CamanJS [Interactive Example](http://camanjs.com/examples/) page. Another idea is to check your favorite (localized) photo editing application for clues.

## License

Copyright (C) 2007-2015, CKSource - Frederico Knabben. All rights reserved.
