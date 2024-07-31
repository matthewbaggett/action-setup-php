# action-setup-php

Sets up a PHP project with GitHub Actions, including detecting PHP version and running composer install.

![Tests Status](https://img.shields.io/github/actions/workflow/status/benzine-framework/action-setup-php/test.yml?logo=github&label=Tests)
![QC Status](https://img.shields.io/github/actions/workflow/status/benzine-framework/action-setup-php/trunk.check.yml?logo=github&label=QC)

## Inputs

- `working_directory`: The directory to run the PHP setup in. Default: `.`.
- `php_tools`: The PHP tools to install.

## Outputs

- `php_version`: The PHP version that was detected.

## Exported Envs

- `PHP_VERSION`: The PHP version that was detected.
