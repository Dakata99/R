#  Допълнителни задачи 3

<details>
    <summary>Задача 1</summary>

Намерете 95% доверителния интервал на нормално разпределена случайна величина Х ~ N(10, 3).

a) 10 + qnorm(0.05) * 3; 10 + qnorm(0.95) * 3
b) 10 + pnorm(0.025) * 3; 10 + pnorm(0.975) * 3  
c) 10 + qnorm(0.025) * 3; 10 + qnorm(0.975) * 3
d) 10 + dnorm(0.05) * 3; 10 + dnorm(0.95) * 3

Отговор: c)?
</details>

<details>
    <summary>Задача 5</summary>

Интервалите между пристиганията на клиенти в работно време в магазин са експоненциално разпределени със средно 30 клиента на час.
a) Симулирайте интервалите между пристиганията на 500 клиента, като вземете предвид само работното време.
b) Намерете вероятността интервала между пристиганията на 2 клиента да е между 1 и 2 часа.
c) Намерете минималния интервал, в който клиентите пристигат с вероятност поне 0.91.
</details>

<details>
    <summary>Задача 8</summary>

Първите 6 реда на data frame-a "students" изглеждат така:

|   |  gender | age | height | weight |
|---|---------|-----|--------|--------|
| 1 |  Male   | 45  | 170    | 85     |
| 2 |  Female | 22  | 155    | 57     |
| 3 |  Female | 36  | 162    | 60     |
| 4 |  Male   | 32  | 185    | 100    |
| 5 |  Female | 42  | 172    | 69     |
| 6 |  Male   | 28  | 180    | 80     |

Напишете код в R, с който да нарисувате скептърплот на височината и теглото на студентите, на който наблюденията за различните полове са оцветени в различен цвят.
</details>

<details>
    <summary>Задача 9</summary>

Изследван е ръстът на 20-годишни студенти и с помощта на ф-ята fivenum са получени следните резултати:
160.4231 168.9164 173.0512 179.0420 189.1009
Избройте описателните статистики, които описват тези числа.
</details>