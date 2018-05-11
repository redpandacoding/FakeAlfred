FakeAlfred
=======================

Dry Bulk Material names generated using fzaninotto/Faker


Installation
------------

Add FakeAlfred library to your `composer.json` file:

```
composer require redpandacoding/fakealfred
```

Usage
-----

To  use this with [Faker](https://github.com/fzaninotto/Faker), you must add the `Alfred\Provider\Material` class to the Faker generator:

```php
<?php

$faker = \Faker\Factory::create();
$faker->addProvider(new \Alfred\Provider\Material($faker));

// Generator
$faker->materialName();      // A random Material Name