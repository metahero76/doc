
====== [ 생활코딩 ] Python 제어문 1강~11강 </span> ====== 
--------------------------------------------------

1강 Python : 제어문 - 1. 오리엔테이션
--------
<a href="" target="_blank">

https://www.youtube.com/watch?v=ySlod5oxoV8&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=1

2강 Python 제어문 - 2. Boolean
--------
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

3강 Python 제어문 - 3. 비교 연산자
--------
https://www.youtube.com/watch?v=fKxh7xpGZig&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=3

4강 Python 제어문 - 4.1. 조건문의 기본형식
--------
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
 
5강 Python 제어문 - 4.2. 조건문 - else
--------
https://www.youtube.com/watch?v=13-M9GNq_CI&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=5

6강 Python 제어문 - 4.3. 조건문 elif
--------
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
 

7강 Python 제어문 - 4.4. 조건문 중첩
--------
https://www.youtube.com/watch?v=N3Tisvuxw74&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=7

8강 Python 제어문 - 5.1. 반복문 - for 기본형식 
--------
https://www.youtube.com/watch?v=lMp-bLDZ7TM&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=8
![image](https://user-images.githubusercontent.com/96629767/153634497-756b3cba-02bd-49ee-9518-74d6069f7f57.png)
```
names = ['egoing', 'basta', 'blackdew', 'leezche']

for name in names:
    print('Hi, '+name+' . Bye, '+name+'.') 
```

9강 Python 제어문 - 5.2. 반복문 - 다차원배열의 처리
--------
https://www.youtube.com/watch?v=xcz1WwPm1kM&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=9

10강 Python 제어문 - 5.3. 반복문 - Dictionary
--------
https://www.youtube.com/watch?v=QBsXqzM4CQM&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=10

11강 Python 제어문 - 6. 수업을 마치며
--------
https://www.youtube.com/watch?v=ATNPfFxUjyU&list=PLuHgQVnccGMA4ZgmqgKZhY9X39Ew8O9k5&index=11

<br>
<br>

====== [ 생활코딩 ] Python Django Web Framework - 1강~14강 ======
--------------------------------------------------

1강 Python Django Web Framework - 1/14. 수업소개
--------
https://www.youtube.com/watch?v=pbKhn2ten9I&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=1&t=36s


2강 Python Django Web Framework - 2/14. 설치
--------
https://www.youtube.com/watch?v=xGdUNyVkAto&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=2


3강 Python Django Web Framework - 3/14. 포트의 개념
--------
https://www.youtube.com/watch?v=fv7mer7cWW8&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=3


4강 Python Django Web Framework - 4/14. app 만들기
--------
https://www.youtube.com/watch?v=QX8CQMycDa0&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=4

5강 Python Django Web Framework - 5/14. Routing URLConf
--------
https://www.youtube.com/watch?v=AafeZ6dxMzo&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=5

6강 Python Django Web Framework - 6/14. django를 쓰는 이유
--------
https://www.youtube.com/watch?v=drPvtMNJOoM&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=6

7강 Python Django Web Framework - 7/14. 홈페이지 읽기 기능 구현하기
--------
https://www.youtube.com/watch?v=7ovAmZjDWmk&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=7

8강 Python Django Web Framework - 8/14. 읽기기능 상세보기 페이지 만들기 (수정본)
--------
https://www.youtube.com/watch?v=T2yw6o6BIi4&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=8

9강 Python Django Web Framework - 9/14. 생성기능 구현 (form)
--------
https://www.youtube.com/watch?v=MZqIjlJqeR0&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=9

10강 Python Django Web Framework - 10/14. 생성기능 (method=GET,POST)
--------
https://www.youtube.com/watch?v=JVoKGD9nrY0&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=10

11강 Python Django Web Framework - 11/14. 생성기능 (request response object)
--------
https://www.youtube.com/watch?v=rIr0TAVgrS4&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=11

12강 Python Django Web Framework - 12/14. DELETE
--------
https://www.youtube.com/watch?v=bycMlzNMuiM&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=12

13강 Python Django Web Framework - 13/14. 수정기능
--------
https://www.youtube.com/watch?v=YDDE0Nnxob4&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=13

14강 Python Django Web Framework - 14/14. 수업을 마치며
--------
https://www.youtube.com/watch?v=hhDSBedPOOs&list=PLuHgQVnccGMDLp4GH-rgQhVKqqZawlNwG&index=14

<br>
<br>

Python Django React연동
--------
https://junlab.tistory.com/187
