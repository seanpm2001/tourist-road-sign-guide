# Розділ 4. Типи знаків

## 4.1 Набір типових знаків

<span class="p-number">4.1.1</span> У відповідності до типів об’єктів та типового сценарію відвідування цих об’єктів ми розробили набір типових знаків, що вкладається в матрицю.

<p class="caption">Таблиця 4.1 — Матриця типів знаків туристичної дорожньої навігації</p>

<style>
   table strong{
      font-size: 1.6em;
      font-weight: 600;
   } 
</style>

<table style="font-size: 0.8em; line-height: 120%;">
  <tr valign="top">
   <td>
   </td>
   <td>
      <strong>A</strong>
      <p>
         Попередній
      </p>
   </td>
   <td><strong>B</strong>
      <p>
         Напрямний
      </p>
   </td>
   <td><strong>C</strong>
      <p>
         Підтверджувальний
      </p>
   </td>
  </tr valign="top">
  <tr>
   <td><strong>1</strong>
      <p>
      Окрема точка інтересу
   </td>
   <td><strong>A1</strong>
      <p>
      Попереджає, що скоро буде з’їзд до точки інтересу
   </td>
   <td><strong>B1</strong>
      <p>
      Направляє на з’їзд до точки інтересу
   </td>
   <td><strong>C1</strong>
<p>
Підтверджує прибуття до точки інтересу
   </td>
  </tr>
  <tr valign="top">
   <td><strong>2</strong>
<p>
Туристичний маршрут
   </td>
   <td><strong>A2</strong>
<p>
Попереджає, що скоро буде виїзд на туристичний маршрут (або з’їзд до нього)
   </td>
   <td><strong>B2</strong>
<p>
Направляє до туристичного маршруту
   </td>
   <td><strong>C2</strong>
<p>
Підтверджує виїзд на туристичний маршрут
   </td>
  </tr>
  <tr valign="top">
   <td><strong>3</strong>
<p>
Туристичний населений пункт
   </td>
   <td><strong>A3</strong>
<p>
Попереджає, що скоро буде з’їзд до туристичного населеного пункту
   </td>
   <td><strong>B3</strong>
<p>
Направляє до туристичного населеного пункту
   </td>
   <td><strong>C3</strong>
<p>
Підтверджує прибуття до туристичного населеного пункту
   </td>
  </tr>
</table>


## 4.2 Попередні знаки (тип А)

<span class="p-number">4.2.1</span> Попередні знаки завчасно попереджають водія, що скоро буде з’їзд до окремої точки інтересу, туристичного маршруту (або виїзд на нього) чи туристичного населеного пункту.

Попередній знак до окремої точки інтересу (тип А1)

![4-1.png](assets/img/4-sign-types/4-1.png "")
<p class="caption">Ілюстрація 4.1 — Приклад знака А1</p>

Попередній знак до туристичного маршруту (тип А2)

На схемі вказують не більше двох туристичних об’єктів (точок інтересу та населених пунктів) в одному напрямку. Для відображення обирають найбільш значущі об’єкти.

Для кільцевих маршрутів верхній об’єкт на знаку — найбільш віддалений, що має високу значущість. Якщо до цього об’єкту водій рухатиметься поточною дорогою (не змінюватиме автошляху), на нього вказують стрілкою.

![4-2.png](assets/img/4-sign-types/4-2.png "Приклад знака А2")
<p class="caption">Ілюстрація 4.2 — Приклад знака А2</p>

Попередній знак до туристичного населеного пункту (тип А3)

Для населеного пункту відображають не більше трьох точок інтересу. Варто обирати найбільш значущі точки інтересу з різних категорій, щоб відобразити спектр вражень, що може отримати турист, відвідуючи цей населений пункт. 

![4-3.png](assets/img/4-sign-types/4-3.png "Приклад знака А3")
<p class="caption">Ілюстрація 4.3 — Приклад знака А3</p>



## 4.3 Напрямні знаки (тип B)

<span class="p-number">4.3.1</span> Напрямні знаки показують маневр, який потрібно зробити водієві, щоб дістатися певного туристичного об’єкта або декількох об’єктів.
Напрямний знак до окремої точки інтересу (тип B1)
Для деяких напрямних знаків трапляється так, що напрямок до точки інтересу відрізняється від напрямку до певного сервісу. У такому разі даний сервіс (або декілька сервісів) не вказують на відповідному знаку. Тобто деякі напрямні знаки, що скеровують до певної точки інтересу, можуть відображати певний сервіс, а деякі ні. Що ближче напрямний знак до точки інтересу, то ймовірніша ця ситуація. 

![4-4.png](assets/img/4-sign-types/4-4.png "Приклади знаків B1: з однією та декількома точками.")
<p class="caption">Ілюстрація 4.4 — Приклад знака B1</p>

На знаках B1 вказують не більше трьох окремих точок інтересу. Якщо існує потреба відобразити більше, ніж три точки, їх відображають на окремих знаках, згрупувавши за напрямками (для розміщення окремих знаків див.  5.3 Напрямні знаки (тип В)).

<p class="caption">Ілюстрація 4.5 — Два окремі знаки для чотирьої точок, на кожному знаку свій напрямок</p>
![4-5.png](assets/img/4-sign-types/4-5.png "Напрямний знак до туристичного маршруту (тип B2)")
Напрямний знак до туристичного маршруту (тип B2)

На знаках B2 відображають до трьох об’єктів (точок інтересу та туристичних населених пунктів). Об’єкти, відображені до цього на знаку A2, відображають і на знаках B2. Останнім відображають кінцевий об’єкт, а для кільцевих маршрутів — найбільш віддалений, що має високу значущість.

Перед в’їздом на кільцевий маршрут встановлюють два напрямних знаки — в обох напрямках. Останній об’єкт в переліках об’єктів на цих двох знаках має збігатися. Таким чином водій матиме можливість зрозуміти, що може дістатися двома альтернативними шляхами до одного й того ж самого об’єкта.

![4-6.png](assets/img/4-sign-types/4-6.png "Приклад знака B2")
<p class="caption">Ілюстрація 4.6 — Приклад знака B2</p>

Напрямний знак до туристичного населеного пункту (тип B3)

На знаку B3 відображають ті самі точки інтересу, що були відображені до цього на знаку A3.

![4-7.png](assets/img/4-sign-types/4-7.png "Приклад знака B3")
<p class="caption">Ілюстрація 4.7 — Приклад знака B3</p>



## 4.4 Підтверджувальні знаки (тип С)

<span class="p-number">4.4.1</span> Підтверджувальні знаки дають розуміння, що водій дістався певної точки інтересу, туристичного маршруту або туристичного населеного пункту.

Підтверджувальний знак окремої точки інтересу (тип C1)

Якщо в безпосередній близькості до точки інтересу або всередині точки є один або декілька сервісів, наведених у списку вище (див. 2.4 Сервіси), напрямки до них відображають на додатковій синій панелі. Також на цій панелі вказують напрямок до входу, якщо підтверджувальний знак встановлено на парковці.


![4-8.png](assets/img/4-sign-types/4-8.png "Приклади знака C1")
<p class="caption"><p class="caption">Ілюстрація 4.8 — Приклад знака С1</p></p>

Підтверджувальний знак туристичного маршруту (тип C2)

На знаку C2 відображають ті самі об’єкти, що й на знаку A2 до цього.


![4-9.png](assets/img/4-sign-types/4-9.png "Приклад знака С2")
<p class="caption">Ілюстрація 4.9 — Приклад знака С2</p>



Підтверджувальний знак туристичного населеного пункту (тип C3)

На знаку C3 відображають ті самі точки інтересу, що відображалися до цього на знаках A3 та B3.

![4-10-2.png](assets/img/4-sign-types/4-10-2.png "Приклад знака C3")
<p class="caption">Ілюстрація 4.10 — Приклад знака C3</p>
