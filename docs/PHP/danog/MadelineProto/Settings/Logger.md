---
title: "danog\\MadelineProto\\Settings\\Logger: Logger settings."
description: ""
image: "https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png"
parent: "MadelineProto API"

---
# `danog\MadelineProto\Settings\Logger`
[Back to index](../../../index.html)

> Author: Daniil Gentili <daniil@daniil.it>  
  

Logger settings.  




## Method list:
* `getType()`
* `setType()`
* `getExtra(): null|callable|string`
* `setExtra(null|callable|string $extra)`
* `getLevel()`
* `setLevel()`
* `getMaxSize()`
* `setMaxSize(int $maxSize)`

## Methods:
### `getType()`

Get $type Logger type.



### `setType()`

Set $type Logger type.



### `getExtra(): null|callable|string`

Get extra parameter for logger.



### `setExtra(null|callable|string $extra)`

Set extra parameter for logger.


Parameters:

* `$extra`: `null|callable|string` Extra parameter for logger.  



### `getLevel()`

Get logging level.



### `setLevel()`

Set logging level.



### `getMaxSize()`

Get maximum filesize for logger, in case of file logging.



### `setMaxSize(int $maxSize)`

Set maximum filesize for logger, in case of file logging.


Parameters:

* `$maxSize`: `int` Maximum filesize for logger, in case of file logging.  



---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)
