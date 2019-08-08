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

   - .mx-auto    x면 양옆

     

   1.2 color