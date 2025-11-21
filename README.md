# otus_democalc

Краткое описание пакета

# Требования
- Минимальная версия PHP: 7.4
- Работает на: PHP 7.4, 8.0, 8.1, 8.2, 8.3

# Composer.php в директории проекта

```
{
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/gnvs/otus_democalc"
        }
    ],
    "require": {
        "gnvs/otus-democalc": "dev-main"
    }
}
```

# Установка 

```sh
composer require gnvs/otus_democalc
```

# Использование

```php
require 'vendor/autoload.php';

use Gnvs\OtusDemoCalc\Democalc;

$calc = new Democalc();

echo $calc->add(5, 3); // 8
echo $calc->subtract(5, 3); // 2
```