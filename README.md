## HTML + CSS Study 2일차

**DEMO** : https://stellular-salmiakki-1ce0d0.netlify.app/#top

### HTML태그에 스타일을주는 방법 

1. HTML 태그에 직접주는 방법 (앞으로 다룰 예정)

```css
      div {

         color:red;

      }
```

 어떤 태그에 공통적인 스타일을 주고싶을 때 사용하는 방법 

2. id 를 이용해 주는방법

```css
#new-style {

color:red;

}
```

```html
<div id="new-style">
```

class 와 사용방식이 비슷하지만 한번에 하나의 스타일만 줄수있음, 주로 자바스크립트에서 많이 쓰이고 스타일링에는 많이 안쓰이는 방식

3. class를 이용해 주는 방법 (강의에서 사용된 방법)

```css
.new-style {

color:red;

}
```

```html
<div class="new-style">
```

한번에 여러개의스타일을 줄수있다. 제일 많이 쓰이는 방법 



4. 복합 선택자

 * 일치 선택자:두가지 조건을 동시에 만족하는 요소 선택 

```css
div.new-style{

      /*div태그에 new-style클래스

}
```

* 자식선택자

```css
div>.new-style{

  /* div의 자식요소중 class="new-style"선택

}
```

* 후손 선택자

```css
div .new-style{

/* div 후손요소들 중에서 class="new-style"

}
```

### 수업중 사용된 스타일🎨

* color : 텍스트의 색을 바꿈 

* background-color: 배경색을 바꿈

* border : 테두리를 그려줌, 3개의 인자를 받음 (두께, 스타일, 색깔)

* width / height: 넓이와 높이를 지정하는데 쓰임

* text-align : 정렬 (left, center, right)

* margin : 내 영역 밖에 공간을 줌 (top, left, right, bottom)

* padding: 내 영역 안에서 공간을 줌 (top, left, right, bottom)

### 🚀 두번째 박스를 숨겨보자! display:none과 visibility:hidden의 차이는?

* `display:none` 은 화면 상 어떤 영역을 차지하지 않고 완전히 삭제된 것처럼 보임
* `visibility:hidden` 은 해당 요소가 보이지 않을 뿐 요소가 존재하는 영역은 확실히 보이게 됨


