# WP Desk Coding Standards

PHPCS ruleset for WP Desk WordPress plugins.

It builds on WordPress Coding Standards and PHPCompatibilityWP, with additional
WP Desk conventions and WooCommerce-aware configuration.

## Installation

```sh
composer require --dev wpdesk/wp-code-sniffer
```

## Usage

Copy the provided example files into your project:

```sh
cp vendor/wpdesk/wp-code-sniffer/phpcs.xml.dist phpcs.xml.dist
cp vendor/wpdesk/wp-code-sniffer/.editorconfig .editorconfig
```

Adjust the values in `phpcs.xml.dist`:

- `text_domain`
- `minimum_wp_version`
- `testVersion`

Then run:

```sh
vendor/bin/phpcs
```

The example configuration scans `src` and `templates` by default.

## Ruleset

The included standard is:

```xml
<rule ref="WPDeskPlugin"/>
```

It includes WordPress rules, PHP compatibility checks, short array syntax,
selected WooCommerce capabilities/functions, and excludes common generated or
dependency directories.

## PhpStorm

Configure PHP_CodeSniffer in:

`Settings → Languages & Frameworks → PHP → Quality Tools`

Then enable:

`Settings → Inspections → Quality Tools → PHP_CodeSniffer`

Use your project `phpcs.xml.dist` as the custom coding standard.
