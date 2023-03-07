# RapidPHP

:warning: Disclaimer: RapidPHP is currently in its early stages of development and is subject to change. Use at your own risk and please report any issues or bugs you encounter. We appreciate your feedback and contributions to the project.

## About 

RapidPHP is a lightweight and flexible PHP framework designed to help you quickly build web applications with a focus on simplicity. It is inspired by the minimalist design and speed of Go Fiber, but with the flexibility to fit your specific needs.

## Installation

You can install RapidPHP using Composer:

```bash
composer require unrealjo/rapidphp
```

## Getting Started

To get started with RapidPHP, simply create a new PHP file and require the RapidPHP autoloader:

```php
require_once 'vendor/autoload.php';
```

Then, create a new RapidPHP application:

```php
$app = new RapidPHP\Application();
```

You can now add routes to your application:

```php
$app->get('/', function() {     echo 'Hello, world!'; });
```

Finally, start the application:

```php
$app->run();
```

## Current Roadmap

- [ ] Basic routing system
- [ ] Middleware support
- [ ] Basic error handling
- [ ] Composer integration
- [ ] Documentation

## Contributing

We welcome contributions to RapidPHP! If you'd like to contribute, please open an issue or pull request on GitHub.

## License

RapidPHP is released under the MIT License. See the `LICENSE` file for details.
