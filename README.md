# Проект библиотека 2 версия

SQL код, который нужен для того, чтобы вручную назначить Timestamp:
```
UPDATE Book SET taken_at='2021-05-07 08:00:00' WHERE id=1;
```

Добавлена реализация Spring Data JPA , пагинация с фильтрацией
