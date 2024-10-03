"""
#1
number = int(input("Введите первую цифру: "))
number = number * 100
number += int(input("Введите вторую цифру: ")) * 10
number += int(input("Введите третью цифру: "))
print("Число, содержащее введенные цифры:", number)
"""
"""
#2
number = int(input("Введите число из четырех цифр: "))
product = 1

while number > 0:
digit = number % 10
product *= digit
number //= 10

print("Произведение цифр числа:", product)
"""
"""
#3
meters = float(input("Enter the number of meters: "))

cm = meters * 100
dm = meters * 10
mm = meters * 1000
miles = meters * 0.000621371

print(f"{meters} meters is equal to:")
print(f"{cm} centimeters")
print(f"{dm} decimeters")
print(f"{mm} millimeters")
print(f"{miles} miles")
"""
"""
#4
base = float(input("Введите длину основания треугольника: "))
height = float(input("Введите высоту треугольника: "))

area = 0.5 * base * height

print("Площадь треугольника равна:", area)
"""
"""
#5
num = input("Введите четырехзначное число: ")

if len(num) != 4:
print("Введите четырехзначное число.")
else:
reversed_num = num[::-1]
print("Перевернутое число:", reversed_num)
"""

