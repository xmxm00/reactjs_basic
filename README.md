# ReactJS 기초 정리

> ### ReactJS 불러오기

```html
<script src="https://unpkg.com/react@17.0.2/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom@17.0.2/umd/react-dom.production.min.js"></script>
```

다음과 같이 react와 react-dom을 import 한다.

> ### JSX

번역을 위해 babel을 경유하나, 이 방식은 느릴 수 있으므로 추후 다른 방식을 이용함
JSX는 자바스크립트 내에서 html 태그처럼 이용할 수 있도록 되어있다. 따라서 태그 명의 혼동을 방지하기 위해 대문자 변수를 이용할 것을 추천한다. 또한 사용자가 정의하는 태그를 하나의 함수로 지정한다.
같이보면 좋을 내용 : 자바스크립트의 ArrowFunction

> ### 정보 출처

노마드코더 강의 : https://nomadcoders.co/react-for-beginners
