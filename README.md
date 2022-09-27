# js_training_1

<h2> 좌표를 이용한 007 play </h2>

<h3> 실습을 통해 알게된 점 </h3>

<p> document.querySelector를 통한 요소접근 <br>
document.addEventListener를 통한 이벤트 불러오기 <br>
getBoundingClientRect를 통한 요소 위치 구하기 <br>
clientX, clientY와 pageX,pageY의 차이점 <br>
자바스크립트를 이용한 동적 구현</p>

<b> 성능 개선 </b>
<p>top과 right를 이용하면 ---> 레이아웃과 페인트가 계속해서 일어남 ---> 성능 저하 <br>
해결법 ---> transform: translate를 이용하면 composite만 일어남 ---> 성능 개선 </p>

# js_training_2

<h2> 스크롤을 이용한 토끼를 찾아라 </h2>

<h3> 실습을 통해 알게된 점 </h3>

<p> scrollIntoView() 메소드 : 특정 element를 기준으로 스크롤을 이동 <br>
1. element.scrollIntoView(); <br>
2. element.scrollIntoView(alignToTop);// Boolean  <br>
3. parameterelement.scrollIntoView(scrollIntoViewOptions); // Object parameter <br>
  - behavior : 전환 애니메이션 정의 (auto || smooth) <br>
 - block : 수직 정렬 (start || center || end || nearest) <br>
 - inline : 수평 정렬 (start || center || end || nearest)
</p>
