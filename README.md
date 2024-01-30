# Hyvä Speak Search

**Hyvä Speak Search is a part of MageINIC Speak Search extension that adds Hyvä features.** This extension extends Speak Search definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/hyva-speak-search

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Speak Search requires installing [MageINIC Speak Search](https://github.com/mageinic/speak-search) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/speak-search
```

## 2. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
