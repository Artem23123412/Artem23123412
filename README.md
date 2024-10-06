#1
N = int(input("Введите число: "))
reversed_number = 0
while N > 0:
    reversed_number = reversed_number * 10 + N % 10
    N //= 10
print(reversed_number)
#2
N = int(input("Введите число: "))
count = 0
sum_cubes = 0
while N > 0:
    digit = N % 10
    sum_cubes += digit * digit * digit
    count += 1
    N //= 10
print(count, sum_cubes)
#3
N = int(input("Введите N: "))
M = int(input("Введите M: "))
A = int(input("Введите A: "))
tiles = (N // A) * (M // A)
print(tiles)
#4
N = int(input("Введите число: "))
binary = ''
while N > 0:
    binary = str(N % 2) + binary
    N //= 2
print(binary)
#5
binary = input("Введите двоичное число: ")
decimal = 0
i = 0
while binary:
    decimal += (ord(binary[-1]) - ord('0')) * (2 ** i)
    binary = binary[:-1]
    i += 1
print(decimal)
#6
S = int(input("Введите размер файла (МБ): "))
V = int(input("Введите скорость (Мбит/с): "))
time_sec = (S * 8) / V
minutes = int(time_sec / 60)
seconds = int(time_sec % 60)
print(f"{minutes} минут(ы) {seconds} секунд(ы)")
