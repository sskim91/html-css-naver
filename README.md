## ch1
- HTML과 CSS는 기본
- 자바스크립트가 현재 웹의 전체라고 해도 무방하다.

## ch2
- 세부적인 디자인은 나중에 하고 레이아웃 영역부터 먼저 만들기
- 레이아웃을 만들때는 가장먼저 `가로` 영역부터 잡자.
- 가로로 큰 구역을 잡고 그 안에서 가로로 또 나누기.
- 가로 구역을 잡고 더 이상 가로로 나눠지지 않을 때 `세로` 영역 잡기
- div 태그로 구역을 잡는다.
- 인라인 스타일은 지양할 것.
- 픽셀은 상대적인 개념이다. (모니터 해상도에 따라서)
- div나 html 태그같은 경우는 브라우저가 기본적으로 속성을 가지고 있다.
- display:block 인 경우 전체를 차지함 100%
- display:inline block 인 경우 width와 height를 지정해 줄 수 있음
- display:inline은 자기 컨텐츠 공간만 차지한다. (빈 공간을 마련할 수 없다.)

## ch3
- display:none 을 쓰면 스크린 리더에 안 읽힌다.
- 이미지 스프라이트 사용
- 웹 프론트엔드를 한다면 로딩시간이 길다고 하면 어떻게 하면 줄일 수 있을까 이런 고민도 필요하다.
- 하나의 태그는 margin, border, padding, content로 이루어진다.
- 기본적으로 html은 contents + padding + border 너비를 따로 잡는다. 이것을 content-box 라고 한다.
- box-sizing 태그 검색해보기

## ch4
- 블록 서식 문맥(block format context) 찾아 보기
- 쌓임 맥락(stacking context) 찾아 보기
- [컨테이닝 블록의 모든것](https://developer.mozilla.org/ko/docs/Web/CSS/All_About_The_Containing_Block)
- 모든 태그는 기본적으로 position : static 이다.
- [CSS 우선순위](https://www.zerocho.com/category/CSS/post/588cb95ca63e64132496a5d5)
