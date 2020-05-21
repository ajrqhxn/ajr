---
layout : post
title : 파이썬 포스트 언더스코어
date : 2020-05-20 19:42:00 +0900
update : 2020-05-22
categories: python
---

<h1>'_'  파이썬 용도??</h1>
<br>

<br><br>

1. 값을 무시하고 싶은 경우 
'''python 
*#인덱스 쓸모 없을때*
for _ in range(3) :
    print("언더스코어_")

#값을 무시할때
def return_two_var (a):
    return a, a*2

_, mul = return_two_var(5)
'''
<br><br>

2. 숫자 자리수 구분할때
'''python 
print(1_000)
print(1000)

1000
1000
'''
<br><br>
3. private 으로 선언
'''python
#*외부에서 보듈을 불러올때 언더스코어로 사용된 변수, 함수, 클래스는 직접 import 하지 않으면사용할수 없다.*
def _hello() : 
    print('hello world')

_private_var = "p"
'''
<br><br>

4. 중복된 이름을 피하고 싶을때
<br><br>

**5. 인터프리터에서 사용할때**
마지막 값을 일시적으로 가지고 있는다.
'''python 
'>>> a = 10
'>>> b = 20
'>>> a + b
'30
'>>> _
'30
'''
<br><br>

<u>문모모님 https://doorbw.tistory.com/153</u>