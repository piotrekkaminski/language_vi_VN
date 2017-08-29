# Vietnamese (Tiếng Việt) Magento2 Language Pack (vi_VN)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Vietnamese (Tiếng Việt) translations used can be found [here](https://crowdin.com/project/magento-2/vi).

# Version & progress
This translation is generated from the branch [2.1.8](https://crowdin.com/project/magento-2/vi#/2.1.8) at Crowdin and based on the Magento 2.1.8 sourcefiles.
There have been  12160 strings translated of the 12160 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/100)

# Instalation
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_vi_vn:dev-master
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_vi_vn/archive/master.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_vi_vn`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/vi_VN/vi_VN.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Vietnamese (Vietnam)*'

# Contribute
To help move the '*Vietnamese (Tiếng Việt) Magento2 Language Pack (vi_VN)*' forward please goto [this](https://crowdin.com/project/magento-2/vi) crowdin page and translate the untranslated string or propose better translations.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Composer package generation originally written by [Wijzijn.Guru](http://www.wijzijn.guru/).
