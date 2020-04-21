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

## ch5
- [Block Format Context 블록 서식 문맥](https://developer.mozilla.org/ko/docs/Web/Guide/CSS/Block_formatting_context)
- [float와 정렬](https://www.zerocho.com/category/CSS/post/5881edef636a7f0b8e8507d8)
- 무조건 부모 태그라고해서 자식 태그를 다 감싸는 것이 아니다.
- overflow hidden 과 auto 의 차이는 부모의 높이가 있을 때 자식이 부모보다 높이가 크면 스크롤 바를 만든다. 
hidden 은 자식태그의 높이가 더 크면 잘라버린다.(숨긴다) 
- [쌓임 맥락 CSS](https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Positioning/Understanding_z_index/The_stacking_context)

## ch6
- [마진 상쇄 완벽 이해](https://velog.io/@raram2/CSS-%EB%A7%88%EC%A7%84-%EC%83%81%EC%87%84Margin-collapsing-%EC%9B%90%EB%A6%AC-%EC%99%84%EB%B2%BD-%EC%9D%B4%ED%95%B4)
- display: inline-block 과의 간격 문제 검색 ㄱㄱ
- 자식이 float면 둥둥 떠있기 때문에 부모 태그에서 영역이 안나타남 이럴 경우 부모태그에 display:inline-block 과 필요시 width:100% 추가할것

## ch7
- calc와 inline-block
- cacl() 를 사용하면 css안에서도 연산을 할 수 있다. (띄어 쓰기 유의할 것)
- inline block 간격 가로 간의 문제는 float로 해결하고 세로 간의 문제는 vertical-align : top을 주던지..float 주던지 해결해야함
- z-index 쌓임 맥락
- 형제들 끼리만 z-index가 중요하다.
- 부모 태그 에서의 z-index 싸움에서 자식태그에 있는 z-index가 아무리 높아도 위의 부모 태그가 z-index 크기에서 지면 저얼대 나타날 수 없다.


