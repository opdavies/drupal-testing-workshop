# Drupal Testing Workshop

A base Drupal 8 installation for use in the Drupal testing workshop. Pre-configured with Docksal, including the PHPUnit add-on.

## Initial Setup

```
git clone https://github.com/opdavies/drupal-testing-workshop.git
fin init
```

Open `http://drupaltest.docksal`.

Run `fin phpunit web/modules/contrib/examples/phpunit_example` to run the first tests!

## Running Tests

```
fin phpunit path/to/module
```
