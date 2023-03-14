# maths_working
import math as m

x = m.sqrt(int(input('Enter a number: ')))
y = m.sqrt(int(input('Enter a number: ')))
a = 10283
z = x ** y // a - 12

print(f"x = {x:.2f}")
print(f"y = {y:.2f}")
print(f"x ** y = {x ** y:.2f}")
print(f"x ** y // a = {x ** y // a:.2f}")
print(f"x ** y // a - 12 = {z:.2f}")

if m.ceil(z) > 10000:
	print('Good', z)

else:
	print('End program', z)

