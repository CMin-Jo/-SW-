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
