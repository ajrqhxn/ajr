---
layout : posts
title : 파이썬 언더스코어
date : 2020-05-20 19:42:00 +0900
categories: python
---

<h1>'_'  파이썬 용도??</h1>
<br>

<br><br>

**1. 값을 무시하고 싶은 경우** 

*인덱스 쓸모 없을때*<br>
*값을 무시할때*<br>
```python 

for _ in range(3) :
    print("언더스코어_")

def return_two_var (a):
    return a, a*2

_, mul = return_two_var(5)

```
<br><br>

**2. 숫자 자리수 구분할때**<br>

```python 

print(1_000)
print(1000)

1000
1000

```
<br><br>

**3. private 으로 선언**

*외부에서 보듈을 불러올때 언더스코어로 사용된 변수, 함수, 클래스는 직접 import 하지 않으면사용할수 없다.* <br>

```python 

def _hello() : 
    print('hello world')

_private_var = "p"

```
<br><br>

**4. 중복된 이름을 피하고 싶을때**<br>

**5. 인터프리터에서 사용할때**<br>
*마지막 값을 일시적으로 가지고 있는다.*<br><br>

```

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> a = 10 <br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> b = 20<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> a + b<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;30<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>> _<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;30<br>

 ```
<br><br>

<u>문모모님 https://doorbw.tistory.com/153</u>