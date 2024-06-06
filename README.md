<h1>Что такое  Symbol (ES2015) в  BigInt (ES2020) на JS</h1>

![](https://i.pinimg.com/564x/f8/69/10/f869109f41754f72d38bcb85f0f47a17.jpg)



## Symbol (ES2015):





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


![](https://i.pinimg.com/originals/aa/59/d1/aa59d139b93dde70ff207187c9f1d8bd.gif)




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
![](https://i.pinimg.com/564x/93/fc/14/93fc14a00dc693a35204eae978f21a9d.jpg)
