# Операции над числами

Если бы с помощью Python можно было бы только хранить данные и печатать их на экран, программирование было бы не особо интересным занятием.

Хорошие новости в том, что в Python встроены все нужные операторы для арифметических действий, а их использование очень похоже на математические записи, которые мы используем в повседневной жизни. Синтаксис Python прост, и даже если вы начинающий программист, такой код наверняка будет вам понятен:

```python
a = 10 + 5
b = a + 20
c = (a + b) * 2
print(a, b, c)
```

После запуска такой программы на экран будет выведен текст

```python
15 35 100
```

В первой строке переменной a будет присвоено значение, которое получится в результате сложения двух чисел — 10 и 5. Вторая строка интересней — в ней мы складываем значение переменной a (15) и число 20. В итоге в переменную b будет записано число 35.

Приоритеты операторов в Python точно такие же, как и в обычной математике, а порядок выполнения можно изменить с использованием скобок. Именно это и происходит на третьей строке программы.

Четвертая строка программы выводит значения всех трех переменных на экран.