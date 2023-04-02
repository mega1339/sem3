# Laba 3

1) Отсутствует файл README.MD с инструкцией по запуску (-10)

2) Некорректная струткра программы. Дожен быть файл main.c. (-10)

3) Почяему файлы без расшерения?
   
Если не умеешь разбивать программу на отдельные файлы, то можно было разбить по папкам, но должны быть файлы main.c

## 1.c Invalid

Некорректный вывод для случая
```
enter:
-a-z-a0-9-0-
abcdefghijklmnopqrstuvwxyzyxwvutsrqponmlkjihgfedcba0123456789876543210
```
Должно быть:
```
enter:
-a-z-a0-9-0-
-abcdefghijklmnopqrstuvwxyzyxwvutsrqponmlkjihgfedcba0123456789876543210-
```

## 2.c Invalid

 В задании требуется находить и удалять вхождение строки s2 в s1. А не удалять посимвольно из s1 s2. 

 ```
asdfgggddfrepre
fr
asdgggddee
 ```

 ```
asdfgggddfrepre
fr
asdfgggddepre
 ```

## 3.c

Нет вывода вертикальный гистограммы.