# Процессор строк

Краткое описание пакета.

## Требования

- PHP ^7.0

## Установка

```bash
$ composer require amirniyaz/otus-composer-package
```

## Использование

```php
<?php
$processor = new StringProcessor();
echo $processor->getLength('my string'); // 9  
```