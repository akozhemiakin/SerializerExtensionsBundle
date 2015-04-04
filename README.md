# SerializerExtensionsBundle
This bundle provides Symfony2 integration with [SerializerExtensions](https://github.com/numesmat/SerializerExtensions)
library. This library allows you to use **array** format with [JMSSerializer](https://github.com/schmittjoh/serializer)
library.
## Installation
### 1. Install using composer
```
php composer.phar require arko/serializer-extensions-bundle "dev-master@dev"
```
### 2. Enable this bundle in your AppKernel.php
```php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new Arko\SerializerExtensionsBundle\ArkoSerializerExtensionsBundle()
    );
}
```
### 3. Use
From now you can use **array** format when serializing and deserealizing your objects with *JMSSeralizer*
