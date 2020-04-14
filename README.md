[![pipeline status](https://gitlab.com/wpdesk/wp-code-sniffer/badges/master/pipeline.svg)](https://gitlab.com/wpdesk/wp-code-sniffer/pipelines) 
[![coverage report](https://gitlab.com/wpdesk/wp-code-sniffer/badges/master/coverage.svg?job=integration+test+lastest+coverage)](https://gitlab.com/wpdesk/wp-code-sniffer/commits/master) 
[![Latest Stable Version](https://poser.pugx.org/wpdesk/wp-code-sniffer/v/stable)](https://packagist.org/packages/wpdesk/wp-code-sniffer) 
[![Total Downloads](https://poser.pugx.org/wpdesk/wp-code-sniffer/downloads)](https://packagist.org/packages/wpdesk/wp-code-sniffer) 
[![Latest Unstable Version](https://poser.pugx.org/wpdesk/wp-code-sniffer/v/unstable)](https://packagist.org/packages/wpdesk/wp-code-sniffer) 
[![License](https://poser.pugx.org/wpdesk/wp-code-sniffer/license)](https://packagist.org/packages/wpdesk/wp-code-sniffer) 


Library for Wp Desk Coding Standards in plugins.
===============================================

# Installation

`composer require --dev wpdesk/wp-code-sniffer`

# Usage

Copy `phpcs.xml.dist` file to plugin root directory. Change `enter-plugin-text-domain-here` to plugin text domain.

# PHP Storm

Goto Settings->Languages & Frameworks->PHP->Quality Tools, in PHP_Codesniffer select Local in Configuration. Click `...` and empty path. Click OK.
Next open composer.json file and click `Update` (on top of file).