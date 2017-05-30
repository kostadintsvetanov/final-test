## Финален изпит по теория - задачи

### Практическа задача 1 - (25т.)
Реализирайте следващите подзадачи, като използвате кода в папка `task1` и като работите само в CSS файла (на указаните места).
- **Задача 1.а**
   Направете така, че да се показват по 6 картинки на ред при ширина на екрана над 1000px, по 3 картинки на ред при ширина на екрана над 600px, по две при ширина над 400px и по една картинка във всички останали случаи.

   _Картинките не трябва да се застъпват! Задачата ви е да направите responcive дизайн._

   _Забележка: Нека тези стилове са валидни за всички картинки картинки на страницата (+ тези от следващияте подточки)_
- **Задача 1.b**
   Направете фона на всички картинки на четни позиции светло син (`lightblue`)
- **Задача 1.c**
   Направете така, че при преминаване с мишката над всяка картинка, тя да се завърта около себе си (хоризонтално или вертикално) в рамките на 1 секунда и фонът й да става светло син.
   _Подсказка: използвайте `transform: rotate` пропъртито_
- **Задача 1.d**
   Без да променяте HTML-a, направете така, че върху всяка картинка (`<li>` елемент), да стои черен полу-прозрачен слой така, че картинката да изглежда затъмнена
   _Подсказка: използвайте следния CSS за основа на решението ви:_
   `li::after { content: ""; position: absolute; }`
- **Задача 1.e**
   Без да променяте HTML-a, направете така, че при преминаване с мишката над всяка картинка (`<li>` елемент), върху нея да се появява текст "IMAGINE THAT!", който да е вертикално и хоризонтално центриран
   _Подсказка: използвайте решението от задача 4 за основа_

### Практическа задача 2 - (25т.)

Реализирайте следващите подзадачи, като използвате кода в папка `task2` и като работите само в js файла (на указаните места).
- **Задача 2.1**
   Сортирайте следния списък от числа във възходящ ред: `var arr = [2, 5, 8, 4, 1, 12]`
- **Задача 2.2**
   Напишете функция, която да изважда всички думи, с дължина над 4 символа от следния текст: "The quick brown fox jumps over the lazy dog"
- **Задача 2.3**
   Напишете код, който на всяка секунда закача към `body` елемента следния html: `<p>repetition is fun</p>`
- **Задача 2.4**
   Направете така, че 2 секунди след зареждането на дадена страница, всички картинки в нея да се завъртят по вертикалната си ос (по Y)
- **Задача 2.5**
   Напишете функция, която да сортира следния списък от обекти по полето `price`:
   ```
   var items = [
     {
       id: 1,
       title: "Item 1",
       price: 4.3
     },
     {
       id: 2,
       title: "Item 2",
       price: 2.0
     },
     {
       id: 3,
       title: "Item 3",
       price: 6.5
     },
     {
       id: 4,
       title: "Item 4",
       price: 1.5
     }
   ];
   ```

### Практическа задача 3 - (50т.)

Една детска градина на име "Калпазани" решила да направи страница с дечицата, които я посещавали.

Наели си програмист, но той свършил работата само на половина.

Помогнете им като завършите страницата, за да могат всички да я ползват и да й се радват.

За целта трябва да направите така, че да показва профилите на всички 6 дечица (виж `kids.json`), и да може да се прави търсене по текст (име + цвят), сортиране по възраст/име или филтриране по любима игра.

Кодът е наличен в папката `task3`.

За да решите задачата е необходимо да работите по всички файлове без `kids.json` и папката `img`.

Оценяване на 3-та задача:

- Показване на данните от json файла: (10т.)
- Търсене по текст: (10т.)
- Сортиране по име: (10т.)
- Сортиране по възраст: (10т.)
- Филтриране по любима игра: (10т.)
- **Неспазване** на конвенцията за писане на чист, четим код без повторения: (-10т.)

