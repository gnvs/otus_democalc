# otus_democalc

Краткое описание пакета

# Требования
- PHP.8.3

# Установка 

```sh
composer require gnvs/otus_democalc
```

# Использование

```php
require 'vendor/autoload.php';

use Gnvs\OtusDemoCalc\Calculator;

$calc = new Calculator();

echo $calc->add(5, 3); // 8
echo $calc->subtract(5, 3); // 2
```