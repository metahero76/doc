## ====== [ 생활코딩 ] Python 제어문 1강~11강 </span> ======

## 1강 Python : 제어문 - 1. 오리엔테이션

<a href="" target="_blank">

https://www.youtube.com/watch?v=ySlod5oxoV8&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=1

## 2강 Python 제어문 - 2. Boolean

https://www.youtube.com/watch?v=7ATvsRgzkIU&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=2

```
print(True)
print(False)
print(1 == 1)
print("1" == 1)
print("하늘" == "바다")
print("하늘" == "하늘")
print("하늘" == "바다")
print("하늘" == "하늘" and "바다" == "바다" or "바다" == "시냇물")
print("하늘" == "하늘" or "바다" == "바다")
print('1 == 1', 1 == 1)
print('2 == 2', 2 == 1)
print('1 < 2' , 1 < 2 )
print('1 > 2' , 1 > 2 )
print('1 >= 1', 1 >= 1)
print('2 >= 1', 2 >= 1)
print('1 != 1', 1 != 1)
print('1 != 1', 2 != 1)
```

## 3강 Python 제어문 - 3. 비교 연산자

https://www.youtube.com/watch?v=fKxh7xpGZig&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=3

## 4강 Python 제어문 - 4.1. 조건문의 기본형식

https://www.youtube.com/watch?v=uQb4AdS8yiA&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=4

![image](https://user-images.githubusercontent.com/96629767/153629385-b0d0894f-2fd8-42a3-a36e-1a8398edc3d2.png)

```
# 012
if True:
    print(1)
print(2)

print('---')

print(0)
if False:
    print(1)
print(2)
```

![image](https://user-images.githubusercontent.com/96629767/153630510-983fd4cf-3692-4269-855c-7a512ddc2f0d.png)

```
# 기본아이디
id = "egoing"

# 입력값
input_id = input('id : ')
print("입력내용", input_id)

if input_id == id:
    print('Welcome')
```

## 5강 Python 제어문 - 4.2. 조건문 - else

https://www.youtube.com/watch?v=13-M9GNq_CI&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=5

## 6강 Python 제어문 - 4.3. 조건문 elif

https://www.youtube.com/watch?v=SJ5k8AtZYm0&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=6

```
# 기본아이디
id = "egoing"

# 입력값
input_id = input('id : ')
print("입력내용", input_id)

# if
if input_id == id:
   print('Welcome')

if input_id != id:
   print('Who?')

# if else
if input_id == id:
   print('반가워!')
else:
   print('누구니?')

# if elif
if input_id == id:
   print(id+' 반가워!')
elif input_id == 'myId001':
   print('myId001 반가워?')
elif input_id == 'myId002':
   print('myId002 반가워?')
else:
   print('누구세요?')
```

## 7강 Python 제어문 - 4.4. 조건문 중첩

https://www.youtube.com/watch?v=N3Tisvuxw74&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=7

## 8강 Python 제어문 - 5.1. 반복문 - for 기본형식

https://www.youtube.com/watch?v=lMp-bLDZ7TM&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=8
![image](https://user-images.githubusercontent.com/96629767/153634497-756b3cba-02bd-49ee-9518-74d6069f7f57.png)

```
names = ['egoing', 'basta', 'blackdew', 'leezche']

for name in names:
    print('Hi, '+name+' . Bye, '+name+'.')
```

## 9강 Python 제어문 - 5.2. 반복문 - 다차원배열의 처리

https://www.youtube.com/watch?v=xcz1WwPm1kM&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=9
![image](https://user-images.githubusercontent.com/96629767/153636529-acb95b9e-f265-456b-a6f5-02b71ff28d5e.png)

```
persons = [
    ['egoing', 'Seoul', 'Web'],
    ['basta', 'Seoul', 'IOT'],
    ['blackdew', 'Tongyeong', 'ML'],
]
print(persons[0][0])

for person in persons:
    print(person[0]+','+person[1]+','+person[2])

person = ['egoing', 'Seoul', 'Web']
name = person[0]
address = person[1]
interset = person[2]
print(name, address, interset)

name, address, interest = ['egoing', 'Seoul', 'Web']
print(name, address, interset)

for name, address, interest in persons:
    print(name+','+address+','+interest)
```

## 10강 Python 제어문 - 5.3. 반복문 - Dictionary

https://www.youtube.com/watch?v=QBsXqzM4CQM&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=10
![image](https://user-images.githubusercontent.com/96629767/153637883-03f0bfab-da05-41e6-bbcd-cc87b347cc4a.png)

```
person = {'name': 'egoing', 'address': 'Seoul', 'interset': 'Web'}
print(person['name'])

for key in person:
    print(key, person[key])

persons = [
    {'name': 'egoing', 'address': 'Seoul', 'interset': 'Web'},
    {'name': 'basta', 'address': 'Seoul', 'interset': 'IOT'},
    {'name': 'blackdew', 'address': 'Tongyeong', 'interset': 'ML'}
]

print('==== persons ====')
for person in persons:
    # print(person)
    for key in person:
        print(key, ":", person[key])
    print('------------')
```

## 11강 Python 제어문 - 6. 수업을 마치며

https://www.youtube.com/watch?v=ATNPfFxUjyU&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=11

## Python Django React연동

https://junlab.tistory.com/187
