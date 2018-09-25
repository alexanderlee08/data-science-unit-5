

```python
#1

total = 0
for i in range(1000):
    if (((i % 3) == 0) | ((i % 5) == 0)):
        total += i
print(total)
```

    233168



```python
#2
total = 2
i = 2
j = 1
while (i < 4000000):
    temp = i
    i = i + j
    j = temp
    if (i % 2 == 0):
        total += i
print(total)
```

    4613732



```python
#3

def is_factor(term, i):
    if term % i == 0:
        return is_factor(term / i, i)
    else:
        return term
    
term = 600851475143
i = 3
while (i != term):
    term = is_factor(term, i)
    i += 1
print(term)
```

    6857.0



```python
#4 largest palindrone number of 3 digits times 3 digits
def is_p(num):
    string = str(num)
    for i in range(len(string)):
        if (string[i] != string[len(string) - i - 1]):
            return False
    return True

def is_three(num):
    for i in range(999, 100, -1):
        if (num % i == 0):
            div = num / i
            if ((99 < div) & (div < 1000)):
                print(div)
                print(i)
                return True
    return False

for i in range(998001, 10000, -1):
    if (is_p(i)):
        if is_three(i):
            break
print(i)
            

```

    913.0
    993
    906609



```python
#5
232792560 = 4*3*5*7*4*3*11*13*17*19
```


```python
#6
#Find the difference between the sum of the squares of the first one hundred natural numbers and the square of the sum.
squares = 0
for i in range(1, 101):
    squares += i ** 2

summ = 0
for i in range(1, 101):
    summ += i
print((summ ** 2) - squares)
```

    25164150



```python
#7
def is_prime(i, primes):
    for prime in primes:
        if i % prime == 0:
            return False
    return True

primes = [2]
i = 3
while (len(primes) < 10001):
    if (is_prime(i, primes)):
        primes.append(i)
    i += 1
print(primes[-1])
```

    104743



```python
#8
string = '7316717653133062491922511967442657474235534919493496983520312774506326239578318016984801869478851843858615607891129494954595017379583319528532088055111254069874715852386305071569329096329522744304355766896648950445244523161731856403098711121722383113622298934233803081353362766142828064444866452387493035890729629049156044077239071381051585930796086670172427121883998797908792274921901699720888093776657273330010533678812202354218097512545405947522435258490771167055601360483958644670632441572215539753697817977846174064955149290862569321978468622482839722413756570560574902614079729686524145351004748216637048440319989000889524345065854122758866688116427171479924442928230863465674813919123162824586178664583591245665294765456828489128831426076900422421902267105562632111110937054421750694165896040807198403850962455444362981230987879927244284909188845801561660979191338754992005240636899125607176060588611646710940507754100225698315520005593572972571636269561882670428252483600823257530420752963450'

def product(sliced):
    total = 1
    for i in range(13):
        total *= int(sliced[i])
    return total

biggest = 0
sliced = ""
for i in range(987):
    k = i + 13
    if (biggest < product(string[i:k])):
        biggest = product(string[i:k])
        sliced = string[i:k]
print(biggest)
print(sliced)
```

    23514624000
    5576689664895



```python
#9
import math

def pyth():
    for a in range(1,1001):
        for b in range(1,1001):
            c = math.sqrt(a ** 2 + b ** 2)
            if (c % 1 == 0) & (a + b + c == 1000):
                print(str(a) + str(b) + str(c))
                return a * b * c
    return 0
print(pyth())
```

    200375425.0
    31875000.0



```python
math.sqrt(200*200+375*375)
```




    425.0




```python
#10
def is_prime(i, primes):
    root = math.sqrt(i)
    for prime in primes:
        if i % prime == 0:
            return False
        if prime > root:
            return True
    return True

primes = [2]
i = 3
while (i < 2000000):
    if (is_prime(i, primes)):
        primes.append(i)
    i += 1
print(len(primes))
```

    148933



```python
sum(primes)
```




    142913828922


