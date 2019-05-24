## Переводчик на основании Yandex API

### Инструкции
Введите текст и получите первод

### Опции
- lang - Язык, на который будет переведен введенный текст (en по умолчанию)

### Команды
- help - Помощь
- exit - Выход

 ### Пример
````bash
 /usr/local/bin/rbenv exec ruby index.rb
 привет # ввод
 hello # вывод
 hello --lang=ru # ввод
 привет # вывод
 exit
````

### Тест

```bash
rspec
```