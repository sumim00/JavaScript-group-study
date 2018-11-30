# JavaScript 스터디 작업 정리

> 자바스크립트 스터디 작업 정리. 많이 쌓아서 부자되자. <g-emoji class="g-emoji" alias="smirk" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f60f.png">😏</g-emoji>



### DAY1.  (2018.09.16)

1. 자바스크립트로 테이블 5*5 만들고 1~25까지 각 셀에 숫자 넣기 
2. 테이블은 마크업으로 만들어둔 상태에서 숫자만 스크립트로 넣기 
3. 1번을 제이쿼리로 만들기 
4. 숫자를 역순으로 25 ~ 1 까지 넣기 
5. 구구단 만들기 5. 1부터 100까지 합 



### DAY2.  (2018.09.30)

1. 테이블이 여러개일때에도 각각의 테이블에 1~25까지 숫자 입력 
2. 탭 - 기본탭  - 탭안에 탭 - 탭이 여러개일때 탭 안에 탭 
3. 아코디언 - 클릭시 본문 열림 닫힘 
4. 아코디언 += 다른 리스트 닫힘 
5. 아코디언 += 전체 펼침 닫힘 버튼 
6. 체크박스 전체 선택 전체해제 



### DAY3.  (2018.10.14)

> jQuery Effect & Event

1. 상단 헤더 스크롤 내리면 헤더 전체 background-color 변경
2. 헤더 버튼을 클릭하면 해당 버튼과 연결된 box로 스크롤 이동
3. 헤더 버튼 클릭하면 클릭된 버튼 background-color 변경
4. 버튼에 마우스 커서 들어가면 애니메이션 진행
5. 스크롤 되어있는 장소에 위치하면 연결된 버튼 컬러도 바뀌게끔



### DAY4.  (2018.10.14)

> jQuery Scroll



### DAY5. (2018.10.28)

> jQuery Pop-up

1. 풀팝업
 - 화면을 꽉 채운 팝업
    1) 버튼을 클릭했을때 해당 팝업이 노출된다. 
    show , fadeIn, fadeIn + animate
     2) 포커스가 레이어 안에서만 돌아야된다.
    focus() , blur(), keyup, keydown, function(e), e.keyCode, tabindex
     3) 닫기 버튼을 눌렀을때 팝업 노출을 시켰던 버튼으로 다시 포커스가 가야한다.

  2. 모달레이업팝업
  - 딤이 있는 팝업 
  - 화면의 가운데에 노출되어야한다.
  - 화면의 사이즈가 레이어팝업보다 작을때 :

   1) 레이어팝업은 화면의 최상단에 붙는다.
   2) 전체 높이, 전체 너비의 한가운데에 뜨고, 화면의 스크롤을 조절해서 레이업팝의 최상단으로 화면을 맞춘다. 


      3. 팝업 구성 방법
         1) 팝업의 본문만 두고, 껍데기는 가상으로 그려준다.
            2) html에 팝업의 모든 내용을 다 넣어두고 노출만 시킨다.
            3) 버튼과 레이어팝업의 매칭 ( 팝업이 여러개일때 )
            4) 팝업안에 팝업 ( 딤 중복되면 안됨 )




### DAY6. (2018.11.18)

> jQuery plugins

종류

form 디자인 플러그인 (select)

https://plugins.jquery.com/chosen/

pc만 지원 -> M에선 -webkit-apperence : none 처리로 해결 가능

rtl : right to left, 중동 같이 언어 방향이 다른 경우 변경해준다.

html css direction 에서 rtl, ltr 을 확인할 수 있다.



스크롤바 디자인 플러그인

iscroll

https://github.com/cubiq/iscroll

id로 제어하는 경우가 많기 때문에 multiple일 때 사용하는 방법도 확인해야 함.

(each 문으로 attr를 넣어준 뒤에 id값을 매칭시키기)



달력

datepicker

https://jqueryui.com/datepicker/



slide 디자인 플러그인



### DAY7. (2018.12.02)

> jQuery Pop-up

- 레이어 화면 노출 위치 조절하기 (레이어 타입별  조절) 
- 레이어 활성화 함수 만들기 
- 레이어 비활성화 함수 만들기 
- 이중 레이어 
- 윈도우팝업 



### 추가로 찾아볼 것

- ecma6 추가된 부분
- javascript로 짠 코드는 jQuery로, jQuery로 짠 코드는 javascript로 바꿔서 만들어보기.



