# Задача 1
## Напишите псевдокод по блок-схеме
Найти среднее арифметическое среди всех элементов массива [2, 5, 13, 7, 6, 4]
## Решение
```
number = [2, 5, 13, 7, 6, 4];
size = 6;
sum = 0;
avg = 0;
index = 0;

while (index < size):
    sum = sum + numbers[index];
    index = index + 1;
end while

avg = sum/size;
print(avg);
```