## Webpage Training(2)

webver03 : 사이트의 구축 <br/>
https://designus.netlify.app
```
- font-size, font-weight로 타이포 스타일 잡아주기
- css의 hover 선택자를 이용해 마우스 오버했을 때 관련 옵션들이 나오도록 구현
- display를 flex로 설정하여 각각의 하위 요소가 가로로 나오도록 설정
- 글자 수 차면 다음줄로 넘어가게 하기 (flex-wrap:wrap)
- box-shadow 그림자 속성
- '인라인 방식' : css 관련된 속성을 html 태그 내에 스타일 적용 (각 박스 항목마다 다른 썸네일 이미지를 적용하기 때문!!)
- 이미지 효과 : opacity, transition-duration 활용, 불투명도가 자연스럽게 바뀌도록 함
- Netlify를 활용한 사이트 도메인 제작

- 그림 파일은 html, css 파일과 동일 폴더에 위치시켜 링크 적을때 혼동 없도록 할 것
- absolute로 main 잡아줄 때 위치 맞지 않아 수동으로 바꾸었는데 이 부분 살펴볼 것..
- sass를 도입하면 반복적인 링크를 축약시킬 수 있다 -> 살펴볼 것
```
- 모바일 반응형이 완전히 적용되지 않은 부분에 대해서 어떻게 해야 깔끔하게 나타날지를 생각해볼 것
