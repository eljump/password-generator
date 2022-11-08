# Библиотека для генерация пароля

Генерирует пароль на заданное количество символов.

## Инструменты
- `PHP: v8.1`

## Установка

```bash
composer require elias/password-generator
```

## Использование:
```php
<?php
$generator = new PasswordGenerator();
echo $generator->run(6) //A1g23E 
```