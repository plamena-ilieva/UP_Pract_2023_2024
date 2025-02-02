# Консултация СИ, 15.12.2023 - задачи

## Задача 1: 
Дадени са n числа a1, a2, a3, ..., an (ai < 1024), които се интерпретират като битови маски. Маска A е подмаска на аi, ако за всеки изключен бит в ai, битът на същата позиция в A също е изключен. Позициите, на които има включени битове в ai, могат да бъдат както включени, така и изключени в A. Да се напише функция, която приема цяло положително число n и масив от маски с големина n, и връща броят на подмаските.

**Пример:** 

Вход: 
```c++
2
6 3
```

Изход:
```c++
0 1 2 3 4 6
//000 001 010 011 100 110
```

## Задача 2: 
Напишете функция, която приема стринг. Функцията да премахва всички цифри от стринга и да връща произведението на числата в стринга.

**Пример:** 

Вход: 
```c++
“Abc23ffds3ff5” 
```

Изход:
```c++
345 
//Стрингът става “Abcffdsff” 
```

## Задача 3: 
„Префикс" на масив с елементи а1, а2, ..., аn наричаме всяка непразна последователност
a1, a2, …, ai за 1<= i <= n. Да се напише функция, която приема 2 масива от масиви от числа  с еднаква дължина  L и Р (матриците са с размери до 10х10), и връща броя на масивите в L, които имат префикс в Р.

**Пример:**
Вход:
```c++
L = { {1, 2, 3}, {2, 3, 4}, {3, 4, 5} }
P = { {3, 4}, {2, 4}, {1, 2} }
```

Изход:
```c++
2
// {1, 2, 3} and {3, 4, 5}
```
