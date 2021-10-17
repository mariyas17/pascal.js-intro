
Запуск:

```shell
node  --es-module-specifier-resolution=node run.js
```


## Учебные задачи


### 1. Унарный минус

Добавить поддержку вычислений выражений вида:

```
-1 + 5*3
```

### Критерии проверки 

Сейчас для выражения:

```
-1 + 5*-3
```
Получаем сообщение об ошибке:

```
int expected but - found!
```

Должны получить результат:
```
14
```
## 2. Вычисление выражений со скобками

Добавить поддержку вычислений выражений вида:

```
4*(5+3) + 2
```


