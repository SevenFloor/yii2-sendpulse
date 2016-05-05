Client for service sendpulse
============================
Client for service sendpulse

This API client base on official API  [client](https://github.com/sendpulse/sendpulse-rest-api-php)

[![Latest Stable Version](https://poser.pugx.org/sevenfloor/yii2-sendpulse/v/stable)](https://packagist.org/packages/sevenfloor/yii2-sendpulse) [![Total Downloads](https://poser.pugx.org/sevenfloor/yii2-sendpulse/downloads)](https://packagist.org/packages/sevenfloor/yii2-sendpulse) [![Latest Unstable Version](https://poser.pugx.org/sevenfloor/yii2-sendpulse/v/unstable)](https://packagist.org/packages/sevenfloor/yii2-sendpulse) [![License](https://poser.pugx.org/sevenfloor/yii2-sendpulse/license)](https://packagist.org/packages/sevenfloor/yii2-sendpulse)

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist sevenfloor/yii2-sendpulse "*"
```

or add

```
"sevenfloor/yii2-sendpulse": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Add this to your main configuration's components array:

```php
'sendpulse' => [
            'class' => \sevenfloor\sendpulse\SendPulse::className(),
            'userId' => 'your_userId_',
            'secret' => 'your_secret',
            'storageType' => 'session'
        ],
```
