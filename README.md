# Drupal Testing Workshop

A base Drupal 8 installation for use in the Drupal testing workshop. Pre-configured with Docksal, including the PHPUnit add-on.

## Setup

```bash
git clone https://github.com/opdavies/drupal-testing-workshop.git
cd drupal-testing-workshop
fin init
fin phpunit web/modules/contrib/examples/phpunit_example
```

## Running Tests

```
fin phpunit path/to/module
```
