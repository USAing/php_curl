# php_curl

Curl is an open source file transfer tool that uses URL syntax to work on the command line, where the basic functions of curl are encapsulated, such as COOKIES / encrypted transport / HTTP authentication / analog forms / upload files, etc.


### Travis CI

[![Travis-ci](https://api.travis-ci.org/yakeing/php_curl.svg)](https://travis-ci.org/yakeing/php_curl)

### Packagist

[![Version](http://img.shields.io/packagist/v/yakeing/php_curl.svg)](https://packagist.org/packages/yakeing/php_curl)
[![Downloads](http://img.shields.io/packagist/dt/yakeing/php_curl.svg)](https://packagist.org/packages/yakeing/php_curl)

### Github

[![Downloads](https://img.shields.io/github/downloads/yakeing/php_curl/total.svg)](https://github.com/yakeing/php_curl)
[![Size](https://img.shields.io/github/size/yakeing/php_curl/src/php_curl/curl.php.svg)](https://github.com/yakeing/php_curl)
[![tag](https://img.shields.io/github/tag/yakeing/php_curl.svg)](https://github.com/yakeing/php_curl)
[![Language](https://img.shields.io/github/license/yakeing/php_curl.svg)](https://github.com/yakeing/php_curl)
[![Language](https://img.shields.io/github/languages/top/yakeing/php_curl.svg)](https://github.com/yakeing/php_curl)

BY: [yakeing](http://weibo.com/yakeing)

### Installation

Use [Composer](https://getcomposer.org) to install the library.

```

    $ composer require yakeing/php_curl

```

### init

- [x] example
```php
    $Curl = new curl();
    $Curl->LocationQuantity = 1;
    $Curl->Timeout = 10;
```

### GET

- [x] example
```php
      $Url = 'https://github.com/yakeing';
      $Header = array(
        'User-Agent: Mozilla/5.0 (iPad; CPU OS 11_0 like Mac OS X) AppleWebKit/604.1.28'
      );
      $Curl->Get($Url, $Header);
```

### POST

- [x] example
```php
      $Url = 'https://github.com/yakeing';
      $Vars = array(
        'u'=>'admin',
        'upload'=>new CURLFile(realpath('image.jpg')) //php 5.5 Edition
        );
      $Header = array(
        'User-Agent: Mozilla/5.0 (iPad; CPU OS 11_0 like Mac OS X) AppleWebKit/604.1.28'
      );
      $Curl->Post($Url, $Vars, $Header);
```


Donate
---
Your donation makes CODE better.

 Bitcoin (比特币赞助)

 1Ff2hTfr4EioWv2ZDLKTedUiF9wBBVYSbU

 ![Bitcoin](https://raw.githubusercontent.com/yakeing/Content/master/Donate/Bitcoin.png)

 WeChat (微信赞助)

 ![WeChat](https://raw.githubusercontent.com/yakeing/Content/master/Donate/WeChat.png)

 Alipay (支付宝赞助)

 ![Alipay](https://raw.githubusercontent.com/yakeing/Content/master/Donate/Alipay.png)
