# HTML Template Repository with HTML Proofer

This template repository includes preconfigured GitHub Action that will validate html files in a project with (HTMLProofer)[https://github.com/gjtorikian/html-proofer/].

Validation is performed with dynamic pre-rendering of html files so it will allow to construct them with JavaScript on the fly.

HTML files with 'partial.html' suffix will be ignored, so validator is compatible with dynamic construction of website with html includes like (HTML Data Include)[https://github.com/programmingmentor/html-data-include].

#### 1. Оголошення змінних:
   - **const**: 
     ```javascript
     const pi = 3.14; // Значення pi не може бути змінено
     ```
   - **let**:
     ```javascript
     let score = 10; // Значення score може змінюватися
     score = 15;
     ```
   - **var** (застарілий спосіб):
     ```javascript
     var oldWay = "Це старий спосіб";
     ```

#### 2. Типи даних:
   - **Number**: 
     ```javascript
     const age = 30; // ціле число
     const temperature = -4.5; // дробове число
     ```
   - **String**: 
     ```javascript
     const name = "Олексій"; // текстовий рядок
     const greeting = "Привіт, " + name; // конкатенація рядків
     ```
   - **Boolean**: 
     ```javascript
     const isAdult = true; // логічне значення
     const isStudent = false;
     ```

#### 3. Умовні оператори:
   - **if**:
     ```javascript
     if (age >= 18) {
       console.log("Повнолітній");
     } else {
       console.log("Неповнолітній");
     }
     ```

#### 4. Арифметичні операції:
   - **Приклади**:
     ```javascript
     const sum = 5 + 3; // 8
     const difference = 10 - 5; // 5
     const product = 4 * 3; // 12
     const quotient = 20 / 4; // 5
     const remainder = 7 % 2; // 1
     ```

#### 5. Функції:
   - **sum(a, b)**:
     ```javascript
     function sum(a, b) {
       return a + b;
     }
     const total = sum(5, 3); // 8
     ```
   - **checkEvenOrOdd(number)**:
     ```javascript
     function checkEvenOrOdd(number) {
       if (number % 2 === 0) {
         return "Even";
       } else {
         return "Odd";
       }
     }
     const result = checkEvenOrOdd(7); // "Odd"
     ```

#### 6. Ключове слово `typeof`:
`typeof` використовується для визначення типу змінної або виразу.
   - **Приклади**:
     ```javascript
     console.log(typeof 42); // "number"
     console.log(typeof "Привіт"); // "string"
     console.log(typeof true); // "boolean"
     ```

#### 7. Основні типи даних у JavaScript:
   - **Number**: Числовий тип, включає цілі та дробові числа.
   - **String**: Текстовий тип, представляє рядки символів.
   - **Boolean**: Логічний тип, приймає значення `true` або `false`.
   - **undefined**: Тип для невизначених змінних або невизначених значень.
   - **null**: Представляє відсутність будь-якого значення або об'єкта.
   - **Object**: Складний тип даних, який може містити колекцію даних або більш складні сутності.
   - **Symbol** (доданий в ES2015): Унікальний та незмінний тип, часто використовується для створення унікальних ідентифікаторів об'єктів.

Ці концепції є основою для розуміння JavaScript та його практичного використання.

