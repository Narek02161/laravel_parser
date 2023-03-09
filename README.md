# parser

## Запуск приложения
```bash
#для запуска или пересборки контейнеров
make rebuild 
# или что бы поднять уже собранные контейнеры 
make up 
```

- Запускается вместе с базой данных (MariaDB)
- Приложение доступно по адресу [http://localhost:8080](http://localhost:8080)

## Остановка приложения
```bash
make down
```

## Доступы к бд
**БД:** `parser`

**Юзер:** `parser`

**Пароль:** `secret`

**Порт:** `3307`

## Версии
**PHP-FPM:** 8.1.9 под Alpine 3.16

**MariaDB:** 10 под Alpine 3.16

**Nginx:** 1.23.1 под Alpine 3.16