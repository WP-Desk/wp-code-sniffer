# WP Desk Coding Standards

Set of general WordPress standards enhanced by WP Desk coding style.

## Installation & Usage

To install this set of standards simply add the library to your require-dev in `composer.json` or run:

`composer require --dev wpdesk/wp-code-sniffer`

Copy `phpcs.xml.dist` and `.editorconfig` to your project folder, then set needed config like `text_domain`, etc.

## Integration with PHP Storm

Go to *Settings→Languages & Frameworks→PHP→Quality Tools* in PHP_CodeSniffer select *Local* in Configuration.

You can also select more settings by clicking `...`. Clear the path or set it to globally installed `phpcs` if you have locally installed dependencies.

Secondly, in *Settings→Inspections→Quality Tools* check the box **PHP_CodeSniffer inspections** and set coding standards to custom path pointing to your `phpcs.xml.dist` file.
