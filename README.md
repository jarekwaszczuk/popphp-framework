Pop PHP Framework
=================

<img src="http://www.popphp.org/assets/img/pop-php-logo.png" width="180" height="180" />

[![Join the chat at https://gitter.im/pop-php-framework/Lobby](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/pop-php-framework/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

RELEASE INFORMATION
-------------------
Pop PHP Framework 4.0.1  
Released February 9, 2019

OVERVIEW
--------
This repository contains the composer.json file to install the full Pop PHP Framework.
The core Pop PHP components and the additional components will be installed:

|                                                      | Components                                               |                                                          |
|------------------------------------------------------|----------------------------------------------------------|----------------------------------------------------------|
| [pop-acl](https://github.com/popphp/pop-acl)         | [pop-debug](https://github.com/popphp/pop-debug)         | [pop-mail](https://github.com/popphp/pop-mail)           |
| [pop-audit](https://github.com/popphp/pop-audit)     | [pop-dir](https://github.com/popphp/pop-dir)             | [pop-nav](https://github.com/popphp/pop-nav)             |
| [pop-auth](https://github.com/popphp/pop-auth)       | [pop-dom](https://github.com/popphp/pop-dom)             | [pop-paginator](https://github.com/popphp/pop-paginator) |
| [pop-cache](https://github.com/popphp/pop-cache)     | [pop-form](https://github.com/popphp/pop-form)           | [pop-pdf](https://github.com/popphp/pop-pdf)             |
| [pop-code](https://github.com/popphp/pop-code)       | [pop-ftp](https://github.com/popphp/pop-ftp)             | [popcorn](https://github.com/popphp/popcorn)             |
| [pop-config](https://github.com/popphp/pop-config)   | [pop-http](https://github.com/popphp/pop-http)           | [popphp](https://github.com/popphp/popphp)               |
| [pop-console](https://github.com/popphp/pop-console) | [pop-i18n](https://github.com/popphp/pop-i18n)           | [pop-session](https://github.com/popphp/pop-session)     |
| [pop-cookie](https://github.com/popphp/pop-cookie)   | [pop-image](https://github.com/popphp/pop-image)         | [pop-validator](https://github.com/popphp/pop-validator) |
| [pop-css](https://github.com/popphp/pop-css)         | [pop-kettle](https://github.com/popphp/pop-kettle)       | [pop-view](https://github.com/popphp/pop-view)           |
| [pop-csv](https://github.com/popphp/pop-csv)         | [pop-loader](https://github.com/popphp/pop-loader)       |                                                          |
| [pop-db](https://github.com/popphp/pop-db)           | [pop-log](https://github.com/popphp/pop-log)             |                                                          |

NEW FEATURES
------------
* A number of components have been improved and refactored. 
* Support for PHP 7.1+ only.
* PHPUnit tests refactored for PHPUnit 7.0+.
* Reference the `CHANGELOG.md` for further details.


INSTALL
-------
There are multiple ways you can get Pop PHP Framework into your project.

You can add it to an existing project:

```console
$ composer require popphp/popphp-framework
```

You can add it your project's `composer.json` file:

    "require": {
        "popphp/popphp-framework": "^4.0.1"
    }

You can create a new project and install it into that project:

```console
$ composer create-project popphp/popphp-framework project-folder
```

Or, you can clone this repository and install it directly:

```console
$ composer install
```

## DISCUSSION

There is a Gitter chat room for Pop PHP over at https://gitter.im/pop-php-framework/Lobby
