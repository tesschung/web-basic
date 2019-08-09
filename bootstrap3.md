https://booolean.tistory.com/758

**html은 위에서 아래로 읽는다**



css를 편하게 적용 시켜주는 것

https://getbootstrap.com/docs/4.3/getting-started/introduction/

css

```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
```

해당 부분을 html 에 작성하여 bootstrap의 정보를 가져온다.

**head태그에 넣고, 다른 css를 넣기 전에 넣어야 한다!**



JS

**CDN**: Content Delivery(Distribution) Network

```html
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
```

**body 태그가 끝나는 아래쪽**에 넣는다.





```
컨텐츠(CSS,JS,Image,Text등)을 효율적으로 전달하기 위해
여러 노드에 가진 네트워크에 데이터를 제공하는 시스템은 무엇인가?

1.CDM
2.CPM
3.CDN #정답
4.CPN
```





CSS reset



1. utilities: 클래스를 사용해서 css를 적용 시킬 수 있다.

   1.1 spacing

   - .mr-0 -> margin을 0 을 주겠다는 뜻

   - .mx-0

   - .py-0 -> padding의 y축

   - .mt-1 > margin의 top을 rem 기준

   - 1단위를 0.25rem기준으로 한다.

     .mt-2 0.5 8px

     .mt-3 1 16px

   - 그냥 m만하면 상하좌우 모두 적용

   - .mx-auto    x면 양옆 (인라인만)

     

   1.2 color

   - 



​		1.3 border



​		1.4 display

​			sm md lg xl



class 등 적용 시키는법

p -> padding

etc..

components

form 중요

grid

modal



grid system 에서보면,

class="row"이고,

3가지 갈래로 나누었음

![1565246079191](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1565246079191.png)





homeworkshop위주

html tag 기본구조

head/body

domtree구성

semantic tag들

그냥 div가 아니라 header section

a, img 태그

css는 property의 값 단위들

키워드

크기단위

색깔단위 3가지 16진수 rgb



display 속성 block none

relative absolute position



bootstrap 개념 뭐하는 건지

ml-0 margin left 0

primary secondary



grid system 12개의 컬럼이 하나의 row가 된다



특정 element에 사용가능한 class 사용 불가능한 class  

img에 텍스트 관련한거 안됨 등등