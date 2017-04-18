# Loadtest examples

Occasionally I'll post tests here that are sanitized but have commonly-performed actions. Future tests will include OAuth2 and JWT.

These examples work on jMeter 3.x and up.

## Current examples:

1. Multisite.jmx - Shows managing testing a multisite with different URLs. Also some json stuff. All Drupal.

2. APIExample.jmx - A test that includes juggling APIs, a bunch of logic (if/while statements), and some beanshell scripting. This test was a collaboration amongst many colleagues.

## Required plugins

Plugins for jMeter 3.x can be found at https://jmeter-plugins.org/downloads/all/ and managed via the plugin manager. The following are required for these examples:

- jpgc - Standard Set (“Dummy Sampler” is part of the Standard
 Set)
- Console Status Logger
- JSON Plugins
