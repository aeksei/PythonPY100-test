Чтобы работать с циклом `for` используется следующая конструкция:

```python
for value in sequence:
    # Начало блока кода с телом цикла. Один отступ вправо от уровня объявления цикла
    ...
    ...
    ...
    # Конец блока кода с телом цикла
# Код который будет выполняться после цикла. Один отступ влево, чтобы закончить объявление цикла
```

В данном случае мы объявляем переменную `value` (название переменной вы выбираете сами), которая будет использоваться для того чтобы по порядку получать значения из любой последовательности `sequence` (списка, кортежа, словаря, строки, и т.д.).

- В строке, где вы объявляете цикл `for` в конце обязательно должно стоять **двоеточие** - так вы показываете интерпретатору, что дальше будет идти тело цикла.  
- Тело цикла должно состоять как **минимум из одного оператора**.  
- Чтобы интерпретатор мог понять, какие операторы входят в тело цикла, мы должны помещать эти операторы на **одном отступе вправо** от уровня объявления цикла.