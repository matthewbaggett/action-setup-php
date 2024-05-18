# action-setup-php
Sets up a PHP project with GitHub Actions, including detecting PHP version and running composer install.

## Inputs:
- `working_directory`: The directory to run the PHP setup in. Default: `.`.
- `php_tools`: The PHP tools to install. 

## Outputs:
- `php_version`: The PHP version that was detected.

## Exported Envs:
- `PHP_VERSION`: The PHP version that was detected.