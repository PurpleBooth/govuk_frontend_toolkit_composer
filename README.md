# GOV.UK Frontend Toolkit

A satis repository for the [govuk_frontend_toolkit](http://github.com/alphagov/govuk_frontend_toolkit).

Already hosted at [govuk-frontend-toolkit.appspot.com](https://govuk-frontend-toolkit.appspot.com/index.html).

## Installing

Adding the repository to composer.json:
```json
{
    "repositories": [
        {
            "type": "composer",
            "url": "https://govuk-frontend-toolkit.appspot.com"
        }
    ]
}
```

Add the package:

```bash
composer.phar require alphagov/govuk_frontend_toolkit:dev-master
```

## Usage

This repository is a component-installer component. See the [component-installer](https://github.com/RobLoach/component-installer) project for more details.

## Updating the satis repository

For your convenience this satis repository is hosted on google app engine. However feel free to host it wherever you'd like.
See the [satis page](https://getcomposer.org/doc/articles/handling-private-packages-with-satis.md) for more details. 
