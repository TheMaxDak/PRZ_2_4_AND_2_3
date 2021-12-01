## Задание 1

x = 3
a = 0
for i in range(0,51):
    a += ((5*i/3)+5)*x**(7*i)
print(a)    

## Задание 2

n = float(input("Введите числа: "))
x = 0 
while n < 0:
    x += 1 
    n = float(input("Введите числа: "))
print(x)

## Задание 3

x, y = 0, 0
while True:
    a = int(input())
    if a == 0:
        break
    elif a < 0:
        x += a
    elif a > 0:
        y += a
print(f'Сумма отрицательных числе = {y}', f'Сумма положительных числе = {x}', sep='\2n') 

## Задание 4

x1 = int(input())
y1 = int(input())
x2 = int(input())
y2 = int(input())
if abs(x1-x2) <= 1 and abs(y1-y2) <= 1:
    print("YES")
else:
    print("NO") 
    
## Задание 5
a = int(input())
b = int(input())
c = int(input())
if a == b == c:
    print("Равносторонний")
elif a == b or b == c or a == c:
    print ("Равнобедренный")
else:
    print("Разносторонний")
