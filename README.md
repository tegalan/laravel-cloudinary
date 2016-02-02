# flysystem-cloudinary
Adapter for theleague php flysystem for Cloudinary

[![Author](https://img.shields.io/badge/autor-@carlosocarvalho-blue.svg?style=flat-square)](https://twitter.com/carlosocarvalho)
[![Latest Stable Version](https://poser.pugx.org/carlosocarvalho/flysystem-cloudinary/v/stable)](https://packagist.org/packages/carlosocarvalho/flysystem-cloudinary) [![Total Downloads](https://poser.pugx.org/carlosocarvalho/flysystem-cloudinary/downloads)](https://packagist.org/packages/carlosocarvalho/flysystem-cloudinary) [![Latest Unstable Version](https://poser.pugx.org/carlosocarvalho/flysystem-cloudinary/v/unstable)](https://packagist.org/packages/carlosocarvalho/flysystem-cloudinary) [![License](https://poser.pugx.org/carlosocarvalho/flysystem-cloudinary/license)](https://packagist.org/packages/carlosocarvalho/flysystem-cloudinary)
[![Build Status](https://travis-ci.org/carlosocarvalho/flysystem-cloudinary.svg?branch=master)](https://travis-ci.org/carlosocarvalho/flysystem-cloudinary)


Install

```bash
  composer require carlosocarvalho/flysystem-cloudinary
```
Example

```php

use CarlosOCarvalho\Flysystem\Cloudinary\CloudinaryAdapter as Adapter;

$config = [
    'api_key' => ':key',
    'api_secret' => ':secret',
    'cloud_name' => ':name',
];

$container = new Adapter($config);

$filesystem = new League\Flysystem\Filesystem( $container );

```

