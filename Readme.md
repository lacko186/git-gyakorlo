# Üdv
** Ebben a repoban a git használatát, és a markdownt gyakorlom **


egy egyszerű python kód
```python
print('hello world')

a = int(input('Adj meg egy számot: '))
b = int(input('Adj meg mégegy számot: '))

c = input('add meg a műveleti jelet (+,-,*,/): ')

if c == '+': 
    print(a + b)
elif c == '-': 
    print(a - b)
elif c == '*': 
    print(a * b)
elif c == '/': 
    if b != 0:
        print(a / b)
    else:
        print('Nullával való osztás nem lehetséges!')
else:
    print('Érvénytelen műveleti jel!')
  
```