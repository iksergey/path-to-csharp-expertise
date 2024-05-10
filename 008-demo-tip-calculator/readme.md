**Задача: Калькулятор чаевых**

**Цель:**
Написать программу на C#, которая поможет пользователям рассчитать общую сумму счета, процент чаевых и сумму, которую каждый человек должен заплатить в группе.

**Описание:**
Вам необходимо создать консольное приложение, которое запрашивает у пользователя следующие данные:
1. Сумма счета.
2. Процент чаевых (в процентах).
3. Количество человек в группе.

После ввода данных программа должна рассчитать:
1. Сумму чаевых.
2. Общую сумму счета с учетом чаевых.
3. Сумму, которую каждый человек должен заплатить.

Расчеты должны быть осуществлены согласно следующим формулам:
- Сумма чаевых = (Сумма счета * Процент чаевых) / 100.
- Общая сумма счета = Сумма счета + Сумма чаевых.
- Сумма на каждого = Общая сумма счета / Количество человек.

После расчетов программа должна вывести результаты на экран в виде сообщений следующего формата:
- "Общий счет: [Общая сумма счета]"
- "Процент чаевых: [Процент чаевых]%"
- "С каждого: [Сумма на каждого]"

**Пример:**
```
Введите сумму счета: 50
Введите процент чаевых: 15
Введите количество человек: 4
Общий счет: 57.5
Процент чаевых: 15%
С каждого: 14.375
```

**Требования:**
1. Программа должна быть написана на языке C#.
2. Все вводимые данные должны быть корректными числами.
3. Программа должна обрабатывать ошибки ввода данных и сообщать пользователю об этом.
4. Вывод результата должен быть понятен и читаем для пользователя.