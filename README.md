TransportationWsBundle
======================

Symfony2 bundle to handle all the webservices between Transportation website and its partners


Installation
============

To install this bundle please follow the next steps:

First add the dependency in your `composer.json` file:

```json
"require": {
        ...,
        "transportation/ws-bundle": "dev-master"
    },
```

Then install the bundle with the command:

```sh
php composer update
```

Enable the bundle in your application kernel:

```php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        //
        new Transportation\Bundle\WsBundle\TrepiaRestApiBundle(),        
    );
}
```

Now the Bundle is installed.