# СОН-27: Заголовки
*Тип: дійсне правило*
## Заголовки у нотатках
### Формулювання проблеми
У нотатках часто доводиться записувати заголовки. Заголовки повинні бути різної важливості, привертати увагу, але при цьому ніяк не впливати на деревоподібну структуру
### Запропоноване вирішення
Пропонується вирішення: запис заголовків з початку рядка, починаючи символами "#", а потім " ". Чим більше символів "#", тим менша важливість заголовку. Заголовок, на відміну від примітки, не може опинитися посеред дерева, а лише між ними на початковому рівні. Приклад:
```
# Заголовок
## Підзаголовок 1
Категорія:
    Об'єкт
    Об'єкт
## Підзаголовок 2
Категорія:
    Об'єкт
    Об'єкт
Категорія:
    Об'єкт
    Об'єкт
```
### Інші популярні рішення та їхні недоліки
  - "> Заголовок" - "брудний" текст
