# CKFinder 3 Translations

This repository contains language files for **CKFinder 3**.

## Contributing

To simplify the process of updating or providing new language files, this repository was created.

You are welcome to help localizing CKFinder into your native language and/or update existing localizations by 
forking this repository and sending a pull request.

### Adding new languages

To add a new language file and use it in CKFinder, you need to adjust it's configuration first:
  
  * [config.languages](http://docs.cksource.com/ckfinder3/#!/api/CKFinder.Config-cfg-languages) must be adjusted
    to include information about the newly added translation.
  * Optionally, also set [config.language](http://docs.cksource.com/ckfinder3/#!/api/CKFinder.Config-cfg-language) 
    if the language detection mechanism turns on different language by default.

Last but not least, create the language file in the `lang` folder of CKFinder. Use `en.json` as a base for creating 
own language file. Use the two-letter [ISO 639-1](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) language code 
as a name for the language file, optionally using the two-letter [ISO 3166-1](http://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) 
country code as a suffix.

For example for French (Canadian) use `fr-ca`.

## License

Copyright (C) 2007-2015, CKSource - Frederico Knabben. All rights reserved.
