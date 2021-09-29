# wkhtmlto
wkhtmltopdf and wkhtmltoimage are open source (LGPLv3) command line tools to render HTML into PDF and various image formats using the Qt WebKit rendering engine. These run entirely "headless" and do not require a display or display service.

wkhtmltopdf and wkhtmltoimage are command line tools to render HTML into PDF and various image formats using the QT Webkit rendering engine. These run entirely "headless" and do not require a display or display service.

See http://wkhtmltopdf.org for updated documentation.

================

This repository contains the static compiled binaries from the [wkhtmltopdf project](http://wkhtmltopdf.org/).
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

## Installation

_Hint_:
The version of the binary is equal to the git tag.
To install the version, use '0.12.5'.

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package for _i386_ with:

    php composer.phar require departamento-tecnico-aiudo/wkhtmlto "0.12.5"

And for _amd64_ with:

    php composer.phar require departamento-tecnico-aiudo/wkhtmlto "0.12.5"

The binary will then be located at:

    vendor/departamento-tecnico-aiudo/wkhtmlto/bin/wkhtmltoimage
    vendor/departamento-tecnico-aiudo/wkhtmlto/bin/wkhtmltopdf

Also a symlink will be created in your configured bin/ folder, for example:

    vendor/bin/wkhtmltoimage
    vendor/bin/wkhtmltopdf
