# CSS Properties example
## 아는 부분도 다시한번 체크 
- 박스 모델
- 글꼴, 문자
- 배경
- 배치
- 플렉스 (정렬)
- 전환
- 변환
- 띄움
- 애니메이션
- 그리드
- 다단
- 필터

## 단위 (비교적 자주사용하는 단위)
- px : 화면에 출력하는 하나의 점
- % : 특정한 기준으로 1~100% 상대적 배분율
- em : 요소의 글꼴 크기
- rem : 루트 요소(html(최상위 요소)) 글꼴 크기
- vw : 뷰포트 가로 너비 백분율 (페이지 전체넓이)
- vh : 뷰포트 세로 너비의 백분율 (페이지 전체 넓이 )

## margin 속성
- 요소의 외부 여백(공간)을 지정하는 단축 속성 (음수, 양수 사용가능)
 1. 0  : 여백없음
 2. auto : 브라우저가 여백을 계산
 3. 단위 : px, em, vw 등 단위로 지정
 4. % : 부모 요소의 가로 너비에 대한 비율로 지정 (잘 사용하지 않는 방법)

- margin 적용 방법 4가지 
 1.  margin : (top,right,bottom,left);
 2.  margin : (top,bottom),(left,right)
 3.  margin : top, (left,right), bottom
 4.  margin : top,right,bottom,left

 ## padding 속성
 - 요소의 내부 여백(공간)을 저장하는 단축 속성
  1. 0  : 여백없음
  2. 단위 : px, em, vw 등 단위로 지정
  3. % : 부모 요소의 가로 너비에 대한 비율로 지정 (자주 사용하는 방법)

 - padding 적용 방법 4가지 (개별 속성으로 제어 가능 ex-> padding_leftm padding_right, padding_bottom, padding_top)
  1.  padding : (top,right,bottom,left);
  2.  padding : (top,bottom),(left,right)
  3.  padding : top, (left,right), bottom
  4.  padding : top,right,bottom,left

## border 속성(border :선-두께 선-종류 선-색상)
- 요소의 테두리 선을 단축 속성 

 - border 요소 테두리 선의 두께 적용 속성 (border-width)
  1.  medium : 중간 두께  - 잘 사용하지 않는 방법
  2.  thin : 얇은 두께 - 잘 사용하지 않는 방법
  3.  thick : 두꺼운 두께 - 잘 사용하지 않는 방법
  4.  px, em,% 등 : 단위로 지정 (정확
  한 수치로 지정하는 방식을 선호함 )

- border_width 적용 방법 4가지 
  1.  border_width : (top,right,bottom,left);
  2.  border_width : (top,bottom),(left,right)
  3.  border_width : top, (left,right), bottom
  4.  border_width : top,right,bottom,left

- border-style 종류
  1.  none : 선없음
  2.  solid : 실선 - 자주사용
  3.  totted : 점선 (......)
  4.  dashed : 파선 (------) - 자주사용
  5.  double :  두줄선

- border-style 적용 방법 4가지 
  1.  border-style : (top,right,bottom,left);
  2.  border-style : (top,bottom),(left,right)
  3.  border-style : top, (left,right), bottom
  4.  border-style : top,right,bottom,left

- border-color (기본값: black, 투명색 지정방법: transparent) 적용 방법 4가지
  1.  border-color : (top,right,bottom,left);
  2.  border-color : (top,bottom),(left,right)
  3.  border-color : top, (left,right), bottom
  4.  border-color : top,right,bottom,left

 - 색상 표현 방법
  1. 색상이름
  2. hex 색상코드 (#ffffff) - 가장많이사용
  3. rgb 삼원색
  4. rgba 삼원색 + 투명
  5. HSL 색상 채도 명도 - 잘사용하지 않음
  6. HSLA 색상 체도 명도 + 투명 -잘 사용하지 않음

 - 요소의 테두리 선을 지정하는 기타 속성
  1. border-방향,border-방향-속성
   - border-top : 두께 종류 색상
   - border-right-width: 두께
   - border-left-style: 종류
   - border-left-color:색상

## border-radius 속성
-  요소의 모서리를 둥글게 깍음

- border-radius 적용 방법 4가지 
  1.  border-radius : (top,right,bottom,left);
  2.  border-radius : (top,bottom),(left,right)
  3.  border-radius : top, (left,right), bottom
  4.  border-radius : top,right,bottom,left

## box-sizing 속성
- 요소의 크기 계산 기준을 지정
 1. content-box : 요소의 내용(content)으로 크기 계산
 2. border-box : 요소의 내용 + padding + border로 크기 계산

 ## overflow 속성
 - 요소의 크기 이상으로 내용이 넘쳤을 때, 보여짐을 제어하는 단축 속성
  1. visible : 넘친 내용을 그대로 보여줌
  2. hidden : 넘친 내용을 잘라냄
  3. scroll : 넘친 내용을 잘라냄, 스크롤 생성
  4. auto :  넘친 내용이 있는 경우에만 잘라내고 스크롤바 생성

## display 속성
 - 요소의 화면 출력(보여짐) 특성
  1. block : 상자(레이아웃) 요소
  2. inline : 글자 요소
  3. inline-block : 글자 + 상자 요소
  4. flex : 플렉스 박스 (1차원 레이아웃)
  5. grid : 그리드 (2차원 레이아웃)
  6. none : 보여짐 특성 없음, 화면에서 사라짐
  7. 기타 : table, table-row, table-cell 등...

## opacity 속성
 -  요소 투명도
  1. 1 : 불투명
  2. 0~1 : 0~1 사이의 소수점 숫자 (소수점을 나타낼때 0생략 가능 .5로 표현 가능 )

## 글꼴 속성
 1. font-style 속성
  - normal : 기울기 없음
  - italic : 이텔릭체
  - obllque : 기울어진 글자 (잘 사용하지 않음 )
 2. font-weight 속성 : 글자의 두께(가중치)
  - 평소 사용하는 두께 400, 700 주로 사용 (단위는 100~900)
 3. font-size : 글자의 크기
  - 기본크기 16px (일반적으로 단위로 명시)
 4. line-height : 한 줄의 높이 행간과 유사
  - 숫자(요소의 글꼴 크기의 배수로 지정) - 배수로 사용하는걸 권장 
  - 단위 : px, em, rem등의 단위로 지정
 5. font-family: 글꼴(서체) 
  - 후보를 몇개 지정가능 (사용가능한 글꼴 가져와서 사용)
  - 글꼴계열 필수로 작서해줘야함(ex-> sans-serif)
    1. seif 바탕체
    2. sans-serif 고딕체 계열 - 많이 사용함 
    3. monospace 고정너비 (가로폭이 동등) 글꼴 계열
    4. cursive 필기체 계열
    5. fantasy 장실 글꼴 계열

## 문자 속성
 1.  color : 글자 색상
  - rgb : 기분값 검정색
  - 색상 : 기타 지정 가능한 색상
 2. text-align
  - left, right, center, justify(잘안씀)
 3. text-decoration : 문자 장식 
  - none, underline(밑줄), ovrerkube(윗줄->잘안씀), line-through(중앙)
 4. text-indent : 문자 첫 줄의 들여쓰기
  - 0 : 들여쓰기 없음
  - 단위 : px, em, rem 등 단위로 지정 (% 잘안씀)

## 배경 속성
 1. background-color : 요소의 배경 색상
 2. background-image : 요소의 배경 이미지 삽입
 3. background-repeat : 요소의 배경 이미지 반복
  - repeat 이미지 수직,수평 반복 (여러개 찍힘)
  - repeat-x 이미지를 수평 반복 
  - repeat-y 이미지 수직 반복
  - no-repeat 반복없음
 4. background-position : 요소의 배경 이미지 위치
  - 방향 : top, bottom, left, right, center 방향
  - 단위 : px, em, rem 등 단위로 지정 (% 잘안씀)
 5. background-size
  - auto : 이미지 실제 크기
  - 단위 : px, em, rem 등 단위로 지정
  - cover : 이미지 비율 유지 요소의 더넓은 너비에 맞춤
  - contain : 이미지 비율 유지 요소의 더 짧은 너비에 맞춤 
 6. background-attachment : 요소의 배경 이미지 스크롤 특성
  - scroll : 이미지가 요소를 따라서 같이 스크롤
  - flxed : 이미지가 뷰포트에 고정, 스크롤 X
  - local : 요소 내 스크롤 시 이미지가 같이 스크롤 (잘안씀)

## 배치 속성
 1. position : 요소의 위치 지정 기중 (top, bottom, left, right, z-index)
  - static : 기준 없음
  - relative : 요소 자신을 기준
  - avsolute : 위치 상 부모 욧를 기준
  - fixed : 뷰포트(브라우저)를 기준
  - sticky : 스크롤 영역 기준 (잘안씀)
  - top, bottom, left, right 
   1.  브라우저가 계산 (특정 단위 입력)
  - 요소 쌓임 순서 (Stack order) : 어떤 요소가 사용자와 더 가깝게 있는지(위에 쌓이는지) 결정
   1. 요소에 posigtion 속성의 값이 있는 경우 위에 쌇임 (기본값 static 제외)
   2. 1번 조건이 같인 경우, z-index 속성의 숫자 값이 높을 수록 위에 쌓임
   3. 1번과 2번 조건까지 같은 경우, HTML의 다음 구조일 수록 위에 쌓임
  - z-index : 요소 쌓임 정도를 지정 (postion 1순위 그다음  z-index 2순위)
  - 요소의 display가 변경됨
   1. postion 속성의 값으로 absolute,fixed가 지정된 요소는 display 속성이 block으로 변경됨

## 플렉스 정렬 속성
 1. display : Flex Container의 화면 출력(보여짐) 특성
  - flex : 블록 요소와 같이 Flex Container정의
  - inline-flex : 인라인 요소와 같이 Flex Container 정의 
 2. flex-direction
  - row : 행 축 (좌=>우)
  - row-reverse 행 축 (우 => 좌)
  - column 열 축 (위 => 아래)
  - column-reverse 열 축 (아래 => 위)
 3. flex-wrap : Flex Items 묶음(줄 바꿈) 여부 
  - nowrap 묶음 없음 (기본)
  - wrap 여러 줄로 묶음
  - wrap-reverse  반대방향으로 묶음 
 4. justify-content : 주 축의 정렬 방법
  - flex-start : Flex Items 를 시작점으로 정렬(왼쪽)
  - flex-end : Flex Items 를 끝점으로 정렬(오른쪽)
  - center : Flex Items 를 가운데 정렬
 5. align-content : 교차 축의 여러 줄 정렬 방법
  - stretch : Flex Items를 시작점으로 정렬
  - flex-start : Flex Items 를 시작점으로 정렬(왼쪽)
  - flex-end : Flex Items 를 끝점으로 정렬(오른쪽)
  - center : Flex Items 를 가운데 정렬 
 6. align-items : 교차 축의 한 줄 정렬 방법
  - stretch : Flex Items를 교차 축으로 늘림
  - flex-start : Flex Items 를 시작점으로 정렬(왼쪽)
  - flex-end : Flex Items 를 끝점으로 정렬(오른쪽)
  - center : Flex Items 를 가운데 정렬 
 7. order : Flex Item의 순서
  - 0 : 순서 없음
  - 숫자 : 낮은 숫자 우선 
 8. flex-grow : Flex Item의 증가 너비 비율
  - 0 : 증가 비율 없음
  - 숫자: 증가 비율 
 9. flex-shrink : Flex Item의 감소 너비 비율
  - 1 : Flex Container 너비에 따라 감소 비율 적용
  - 숫자 : 감소 비율 
 10. flex-basis : Flex Item의 공간 배분 전 기본 너비 
  - auto : 요소의 Conten 너비
  - 단위 : px, em, rem 등

## 전환 속성
 1. transition : 요소의 전환(시작과 끝) 효과를 지정하는 단축 속성 (대기시간)
   - 속성명 지속시간(필수값) 타이밍 함수 대기시간 
 2. transition-property : 전환 효과를 사용할 속성 이름을 지정
   - all : 모든 속성에 적용
   - 속성이름 : 전환 효과를 사용할 속성 이름 명시 
 3. transition-duration
   - 0s : 전환 효과 없음
   - 시간 : 지속시간(s)을 지정 (react에서 대기시간을 지정할때는 transition_delay 따로 선언해줘야된다.)
 4. transition-timing-function
   - ease : 느리게 - 빠르게 - 느리게
   - liner : 일정하게
   - ease-in : 느리게 - 빠르게
   - ease-out : 빠리게 - 느리게
   - ease-in-out : 느리게 - 빠르게 - 느리게

## 변환 속성
 1. transform : 요소의 변환 효과
  - 변환함수1 변환함수2 변환함수3 ...;
  - 원근법 이동크기 회전 기울임;
 2. 2D 변환 함수 (자주 쓰는 함수)
  - translate(x,y) :  이동(x->y)
  - translateX : 이동x
  - translateY : 이동y
  - scale(x,y) : 크기(x,y)
  - rotate(degree) : 회전각도
  - skewX(x) : 기울임(x축)
  - skewY(y) : 기울임(y축)
 3. 3D 변환 함수
  - routeX(x) : 횐전축 (x)
  - routeY(y) : 횐전축 (y)
  - perspective(n) : 원근법(거리 )
 4. perspective : 하위 요소를 관찰하는 원근 거리를 지정 (함수가 아니라 css 속성임)
  - 단위 : px 등의 단위로 지정 
 5. backface-visibility : 3D 변환으로 회전된 요소의 뒷면 숨김 여부 
  - visible : 뒷면 보임
  - hidden : 뒷면 숨김 

## 