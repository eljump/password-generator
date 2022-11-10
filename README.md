# Библиотека для генерация пароля

Генерирует пароль на заданное количество символов.

## Инструменты
- `PHP: v7.0`

## Установка

```bash
composer require eliasjump/password-generator
```

## Использование:
```php
<?php
$generator = new PasswordGenerator();
echo $generator->run(6) //A1g23E 
```