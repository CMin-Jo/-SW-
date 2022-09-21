# -SW-


수업시간중 나왔던 문제1
```
a = "Life is too short, you need python"

if "wife" in a:
    print("wife")
elif "python" in a and "you" not in a:
    print("python")
elif "shirt" not in a:
    print("shirt")
elif "need" in a:
    print("need")
else:
    print("none")
```

문제2
```
sum_of_3 = 0
i = 0
while i <= 1000:
    if i % 3 == 0:
        sum_of_3 = sum_of_3 + i
    i = i+1
print(sum_of_3)
```
문제3
```
for i in range(5):
    for j in range(i+1):
        print("*", end='')
    print("")
```
문제4
```
for i in range(1, 101):
    print(i, end=' ')
```
문제5
```
A_score_list = [70, 60, 55, 75, 95, 90, 80, 80, 85, 100]
sum = 0
for i in range(len(A_score_list)):
    sum += A_score_list[i]
print("AVG is "+ str(sum/len(A_score_list)))
```
문제6
```
numbers = [1,2,3,4,5]
result = []
for n in numbers:
    if n % 2 == 1:
        result.append(n*2)

result_by_lh = [n*2 for n in numbers if n%2 == 1]
print(result_by_lh)
```


2022봄 문제1
```
for i in range(0,51,5):
    Celsius = i
    Fahrenheit = i * 9 / 5 + 32
    print("섭씨 : " + str(Celsius) + ", 화씨 : "+ str(Fahrenheit))
```

문제2
```
a = 2*2//2
b = 3//2*3
print(a,b)
```
문제3
```
sums = 0
for i in range(0,1000):
    if i % 3 == 0 or i % 5 == 0:
        sums += i

print(sums)
```


Lab3
```
1번
print("Enter your game score : ", end = '')
score = input()

if int(score) >= 1000:
    print("game_score = " + str(score))
    print("당신은 고수입니다.")
else:
    print("game_score = " + str(score))
```
```
2번
print("Enter num_a : ", end = '')
num_a = input()
print("Enter num_b : ", end = '')
num_b = input()

print("num_a = " + str(num_a) + ", num_b = " + str(num_b))
if num_a == num_b:
    print("두 값이 일치합니다.")
```

Lab2
```
1번
print("정수를 입력하세요 : ", end = '')
n = input()

print(n)

if int(n) % 2 == 0:
    print( n +" 은(는) 짝수입니다.")
```
```
2번
print("정수를 입력하세요 : ", end = '')
n = input()

print(n)

if int(n) > 0:
    print( n +" 은(는) 자연수 입니다.")
```

Lab3
```
1번
print("Enter your game score : ", end = '')
score = input()

if int(score) >= 1000:
    print("game_score = " + str(score))
    print("당신은 고수입니다.")
else:
    print("game_score = " + str(score))
    print("입문자 입니다.")
```
```
2번
print("Enter num_a : ", end = '')
num_a = input()
print("Enter num_b : ", end = '')
num_b = input()

print("num_a = " + str(num_a) + ", num_b = " + str(num_b))
if num_a == num_b:
    print("두 값이 일치합니다.")
else:
    print("두 값이 일치하지 않습니다.")
```
```
3번
print("당신은 성인인가요(성인이면 1, 미성년이면 0) : ", end = '')
is_adult = input()

if int(is_adult) == 1:
    print("결혼을 하셨나요(기혼이면 1, 미혼이면 0) : ", end='')
    is_married = input()

    if int(is_married) == 1:
        print("당신은 결혼한 성인입니다.")
    else:
        print("당신은 결혼하지 않은 성인입니다.")
```

Lab4
```
1번
print("num = ", end = '')
num = input()
if int(num) > 1 and int(num) < 10:
    print("True")
```
```
2번
print("age = ", end = '')
age = input()
print("age = " + age)
if int(age) > 10 and int(age) < 19:
    print("청소년 입니다.")
```

Lab5
```
print("자동차의 속도를 입력하세요(단위 : km/h): ", end = '')
speed = input()

if int(speed) >= 100:
    print("고속")
elif int(speed) < 100 and int(speed) >= 60:
    print("중속")
else:
    print("저속")
```
Lab6
```
1번
for i in range(5):
    print("Hello, Python!")
```
```
2번
for i in range(5):
    print(i)
```

Lab7
```
list =[]
odd = []
even = []
mi = []
for i in range(101):
    list.append(i)
    
for i in range(101):
    if i%2 == 0:
        even.append(i)

for i in range(101):
    if i%2 == 1:
        odd.append(i)
        

for i in range(-100,0):
    mi.append(i)
```
Lab 8
```
sum = 0
even = 0
odd = 0
for i in range(1,100):
    sum += i
    
for i in range(0,100,2):
    even += i
    
for i in range(1,100,2):
    odd += i
```
Lab9
```
for i in range(7,0,-1):
    for j in range(i):
        print(" ", end='')
    print("#")
```
