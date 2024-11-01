"""
 уикл с условием (while) - это цикл, который работает до тех пор, пока условие ИСТИНА.

 Итернация - это один шаг цикла.

 Синтаксис:

 while условие:
      код_для_повторения
      изменение_пкеременной

 break - остановка цикл
"""

"""
count = 10
while count > 0:
    count -= 1
    print(count, end="")
"""

"""
while True:
    userChoice = input("Выберите действие: [+][0 - выход] >>")

    if userChoice == '+':
        print('+')

    elif userChoice == '0':
        print('Всего вам хорошего')
        break
        
    continue - пропуск итерации
"""
#1
"""
begin = int(input("Введите диапазона:"))
end = int(input("Введите конец диапазона"))
while begin <= end:
    total_sum += begin
    begin += 1
print("Сумма чисел диапазона:",)
"""
#2
"""
begin = int(input("Введите начало диапазона:"))
end = int(input("Введите конец диапазона:"))
while begin <= end:
    if begin % 2 == 0:
        print(begin)
    begin == 1
"""

