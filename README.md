## Symbol (ES2015):

![image](https://github.com/Khhiro/Khhiro/assets/171818366/d31a07ba-8db9-4b1d-aa5d-1db77c1ff833)


- ``Symbol`` - это новый примитивный тип данных в JavaScript, введенный в ECMAScript 2015 (ES6).<br><br>
- Основная цель ``Symbol`` - создание уникальных идентификаторов, которые не будут конфликтовать с другими значениями в программе.
 <br><br>
- Каждый ``Symbol`` уникален и неизменен, что означает, что он не может быть изменен после создания и не может быть скопирован.
<br><br>
- ``Symbol`` полезен для создания скрытых или частных свойств объектов, и он может использоваться в качестве ключей для свойств объектов.

<h4>Пример использования Symbol:</h4>

```cs
const mySymbol = Symbol();
const obj = {};

obj[mySymbol] = 'hello';

console.log(obj[mySymbol]); // Выведет: 'hello'
```

 ![hodo](https://i.pinimg.com/originals/7b/6d/ef/7b6def1234d467fcc28e77c9cc7e3eda.gif)



 ## BigInt (ES2020):

 - BigInt - это новый тип данных в JavaScript, представляющий целые числа произвольной длины.
<br><br>

- Чтобы создать ``BigInt``, просто добавьте n к концу числа (например, ``10n``).
<br><br>

- В отличие от чисел типа number, которые ограничены своим диапазоном ``(Number.MAX_SAFE_INTEGER и Number.MIN_SAFE_INTEGER)``, BigInt может представлять целые числа любой длины без потери точности.
<br><br>

<h4>Пример использования BigInt:</h4>

```c#
const bigNumber = BigInt(Number.MAX_SAFE_INTEGER) + BigInt(1);
console.log(bigNumber); // Выведет: 9007199254740992n

```


 ![lofo](https://i.pinimg.com/originals/ab/6e/dc/ab6edc53577c4fdc39a9ba4151ab9d41.gif)
