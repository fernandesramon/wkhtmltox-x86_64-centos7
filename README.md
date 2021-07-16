wkhtmltox
================

This repository contains the static compiled binaries from the [wkhtmltopdf project](http://wkhtmltopdf.org/) for CentOS 7 x86_64.
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

## Installation

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package with:

    composer require fernandesramon/wkhtmltox-x86_64-centos7 "0.12.6"

The binary will then be located at:

    vendor/fernandesramon/wkhtmltox-x86_64-centos7/bin/wkhtmltoimage
    vendor/fernandesramon/wkhtmltox-x86_64-centos7/bin/wkhtmltopdf

A symlink will also be created in your configured bin/ folder:

    vendor/bin/wkhtmltoimage
    vendor/bin/wkhtmltopdf
