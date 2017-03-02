# Estonian (eesti) Magento2 Language Pack (et_EE)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Estonian (eesti) translations used can be found [here](https://crowdin.com/project/magento-2/et).
This translation is usefull for people living in the Estonia (Eesti).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [Head](https://crowdin.com/project/magento-2/et#/Head) at Crowdin and based on the Magento 2.1.4 sourcefiles.
There have been  2042 strings translated of the 8458 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/24)

# Instalation
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_et_ee:dev-master
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_et_ee/archive/master.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_et_ee`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/et_EE/et_EE.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Estonian (Estonia)*'

# Contribute
To help push the '*Estonian (eesti) Magento2 Language Pack (et_EE)*' forward please goto [this](https://crowdin.com/project/magento-2/et) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).