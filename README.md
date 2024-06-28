# Задание №8 - Динамические библиотеки
## Сборщик проекта
В качестве сборщика проекта используется Makefile. Для компиляции проекта необходимо ввести следующую команду в корне проекта:
``` bash
make
```

Для очистки бинарных файлов можно воспользоваться командой:
``` bash
make clean
```

Для запуска проекта необходимо использовать следующую команду в директории task1 (иначе линковщик не найдет библиотеку):
``` bash
make run 
```

## Задание
Переписать программу из задания на статические библиотеки так чтобы применялась динамическая библиотека. Т. е. чтобы весь функционал находился в динамической библиотеке.
## Результаты тестирования программы
- Сложение
```
___MENU___
1) Add
2) Substract
3) Multiply
4) Divide
5) Exit
Enter option: 1
Enter first number: 5
Enter second number: 2
Result of sum: 7
```
- Вычитание
```
___MENU___
1) Add
2) Substract
3) Multiply
4) Divide
5) Exit
Enter option: 2   
Enter first number: 5
Enter second number: 2
Result substraction: 3
```
- Умножение
```
___MENU___
1) Add
2) Substract
3) Multiply
4) Divide
5) Exit
Enter option: 3
Enter first number: 5
Enter second number: 2
Result of multiplication: 10
```
- Деление
```
___MENU___
1) Add
2) Substract
3) Multiply
4) Divide
5) Exit
Enter option: 4       
Enter first number: 5
Enter second number: 2
Result if division: 2
```
- Выход
```
___MENU___
1) Add
2) Substract
3) Multiply
4) Divide
5) Exit
Enter option: 5
```

## Демонстрация работы программ
![image](https://github.com/EltexHomework/DynamicLibrary/assets/70006380/e1b2fc71-23f9-4dd6-a0bb-77ce3b3fd5ae)

