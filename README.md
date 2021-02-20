# *JS Style *

# 1. Используй camelCase для названий переменных, объектов и функций

  Неправильно:
  ```
  const my_object = {};
  function myfunction() {};
  ```
  Правильно:
  ```
  const myObject = {};
  function myFunction() {};
  ```
# 2. Фигурные скобки. Блоки в коде должны выделяться фигурными скобками.
  Открывающаяся скобка должна находиться на строке с ключевым словом, и перед ней должен находиться пробел.

   Неправильно:

  ```
  if (a < 10)
  {
      doSmth();
  }
  ```
  ```
  if (a < 10)
      doSmth();
  ```
   Правильно:
  ```
  if (a < 21) {
      doSmth();
  }
  ```
# 3. Точка с запятой
 Нужно ставить практически в конце каждой строки, для правильной интерпретации кода

  Неправильно:
  ```
  if (a == 11) {
      doSmth()
      a++
  }
  ```
  Правильно:
  ```
  if (a == 11) {
      doSmth();
      a++;
  }
  ```
# 4. Наименование - давать понятные имена переменным, которые обозначают для чего они.
 Неправильно:
```
let a,
    b,
    c,
    v;
v = a * b * c;
```
 Правильно:
```
const name;
let height,
    length,
    width;
var weight;
```

#5. Объекты. Для объявления объекта используй фигурные скобки.
 Неправильно:
```
const item = new Object();

```
 Правильно:
 ```
const item = {};

```

#6. Массивы. Используй квадратные скобки для объявления массивов.
Неправильно:
```
let items = new Array();
```
 Правильно:
 ```
let items = [];
```
#7. Стрелочные функции. Лучше использовать их.
Стрелочные функции делают синтаксис лаконичным и устраняют некоторые трудности с ним.
Не очень:
```
[1, 2, 3].map(function (x) {
  const y = x + 3;
  return x * y;
});
```
 Очень:
 ```
[1, 2, 3].map((x) => {
  const y = x + 3;
  return x * y;
});
```

#8. Шаблонные строки. Используй шаблонные строки вместо конкатенации
Шаблонные строки могут занимать несколько строк.

Не очень:
```
function sayHi(name) {
  return 'How are you, ' + name + '?';
}

Очень:
```
function sayHi(name) {
  return `How are you, ${name}?`;
}
```

#9. Запятые. Не ставь запятые в начале строки

Неправильно:
```
let name
    , adress
    , age;
```
Правильно:
```
let name,
    adress,
    age;
```
#10. Кавычки для строк - везде в коде следует использовать одинаковые кавычки (либо одинарные, либо двойные).

Неправильно:
```
const name = 'Darya';
console.log("Name: " + name);
```
Правильно:
```
const name = 'Emil';
console.log('Name:  ' + name);
```
