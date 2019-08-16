https://drive.google.com/drive/folders/1P-5eWvULmJkOHvxFI7nmwP0WdpsOmLtE

# css: cascading style sheet

html이 있어야만 css가 존재

tree/계층 구조를 가진다





selector : 어떤 element에 css를 적용 시킬지 정의

h1{property: value; property: value;}





3가지 방법 존재

 <!-- 1. Inline -->

<!-- 2.Embedding -->

<!-- 3. Link File --> -> 실제 프로젝트에서 사용하는 방법



프로퍼티 값의 단위

값

1. keyword 키워드 단위

   bold, italic, pink

   display: inline-block.. etc

2. size 크기 단위 (! 시험)

   2.1. **px**

   (픽셀: 화면을 구성하는 단위, 픽셀수가 많으면 해상도가 높다.)

   2.2. **%** 

   백분율 단위의 상대 단위

   요소에 지정된 사이즈에 상대적인 사이즈

 	  2.3. **em**

​	   배수 단위로 상대  단위

​		2.4. **rem**

​		em의 기준은 상속의 영향을 바뀔 수 있다.

​		2.5. **viewport**

​		호환이 되지 않는 경우가 있어서 사용 지양

3. color 색깔 단위

   blue



**box model**(! 시험)

content 

padding

border

margin



**두개씩 정의하는 경우 어떻게 되는지! (! 시험)



2. display 속성(! 시험)

   - block : 

     - 가로폭을 전부 차지해서 css로 가로폭을 줄여도 공간을 내주지 않는다.

     - float안쓰면 옆에 있는걸 밑으로 다 내려버린다

     - 그래서 inline 레벨 요소를 포함한다. (! 시험)

     - 안빈번히 쓰는 애들을 외우고 나머지를 생각하기 (! 시험)

     - inline으로 바꿀 수 있다.

       ```css
       li {
         display: inline;
       }
       ```

   - inline

     - content 크기만큼만 자리를 차지

     - a 태그가 대표적인 inline요소이다.
     - 왜 a태그는 inline인가? 문장사이에 링크가 삽입되어야하기 때문이다.
     - **width/height/margin-top/margin-bottom**을 지정할 수 없다.
     - inline은 margin-left, margin-right 지정 가능하다.
     - padding은 전부 가능하다. (padding은 다른 태그와 겹치게 됨)

     

   - inline-block

     - 기본적으로 inline처럼 움직이지만 block에서 지정하는 width/height/margin-top/margin-bottom을 지정할 수 있다.

     - inline을 block으로 만들고 싶을때,

       ```css
       li {
         display: inline-block;
         width: 100px;
         height: 100px;
       }
       ```

     

   - none (! visibility 차이점 시험)

     - 요소 자체를 없앤다.

     ```css
     #bye {
       display: none;
     }
     ```

     

3. visibility

   보이지 않지만 **자신의 공간을 유지** 하고 있다.

```css
#hollow {
  visibility: hidden
}
```

option
- visible

- hidden

  

서로 margin을 주려고 하면, browser가 알아서 margin을 합친다.

![1565142163519](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1565142163519.png)

```css
h1 {
  margin: 0px;
}
```

그래서 margin을 0px으로 **reset**하여 작업해야 수월해진다. (normalization)

## background&Font&Text(! 시험)

```css
body {
  background-image: url("https://a0.muscache.com/pictures/febbaef0-cf0b-4ecd-a8e3-a629385d6e33.jpg");
  background-size: 100%; /*  background-size: cover;*/
}
```



background-size: 100% 100%; 은 width와 height를 잡은 것

background-size: 100%; 으로 하면 cover과 같이 작동한다.



```css
body {
  background-image: url("https://a0.muscache.com/pictures/febbaef0-cf0b-4ecd-a8e3-a629385d6e33.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;
}
```

no-repeat으로 바둑판식 정제



background-size: contain;



https://fonts.google.com/

font-size
font-family
letter-spacing
text-align
white-space



**font -> *font-family, font-size는 필수값!***



homework해보면 좋음!

html 약자

홈워크풀기

html은 어떤걸 하는지?

semantic tag 정의

div 정의

semantic tag란?

a img 는 어느 속성에 url을 걸지

form안의 type확인

적용가능 css 확인

property 값의 단위 px rem etc..

박스모델

block

inline

inline-block이란? 하지만 block처럼 한줄을 전체 차지하진 않는다.

fixed 포지션







