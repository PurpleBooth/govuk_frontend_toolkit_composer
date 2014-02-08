# GOV.UK Frontend Toolkit

A satis repository for the [govuk_frontend_toolkit](http://github.com/alphagov/govuk_frontend_toolkit).

Already hosted at [govuk-frontend-toolkit.appspot.com](https://govuk-frontend-toolkit.appspot.com).

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