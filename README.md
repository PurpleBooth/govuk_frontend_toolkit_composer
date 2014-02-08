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

The alphagov/govuk_frontend_toolkit package is a component-installer component. See the [component-installer](https://github.com/RobLoach/component-installer) project for details on how to change the directory it installs JS and SASS files to.

### Symfony

An example configuration for Symfony would be the following config in your composer.json
```json
"config": {
    "component-dir": "web/components",
    "component-baseurl": "/components"
}
```

If you ran the require step before adding this configuration, update.

```bash
composer.phar update
```

JS and SASS is installed to ```web/components/govuk_frontend_toolkit```

## Updating the satis repository

For your convenience this satis repository is hosted on google app engine. However feel free to host it wherever you'd like.
See the [satis page](https://getcomposer.org/doc/articles/handling-private-packages-with-satis.md) for more details. 
