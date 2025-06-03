# -site--
코카콜라 리뉴얼

##프로젝트 소개
*칠성사이다 사이트, GDM코리아 자동차 사이트 참조하여 제작한 코카콜라 사이트 제작하였습니다.
제작기간은 약 일주일로, 기획부터 디자인 코딩까지 100% 기여하였습니다.
링크 - https://kimtanhyung.github.io/cocolasite/
---

###파일 구조 및 구성
1. [ ]역할별 파일 구분(/js, /css, /img)
2. main과 section 중복되는 코드 분리

내용 추가 작성하기

###코드 작성

- ` <div class="wrap">
        <div class="header">
```  <main class="main">
        <section class="main_visual">
     <section class="secotn-01">
     </section>

      <section class="secotn-02">
     </section-02>
     </main>
 </div>`
     
  [ ]title h1 가장먼저 사용하고 레이아웃 구조 순서에 맞게 작성
  [x]의미론적 태그를 적절히 사용이 부족함(<articl>, <section>, <header>, <main>, <nav>)
  
```
    반응형웹 사이트
    기술 작성할거고, 프로그램도 작성할거고...❤

### 체크리스트
- [ ] 체크리스트 1
- [x] 체크리스트 2

### 이미지 넣기
![Image](https://github.com/user-attachments/assets/534f6a6f-a63a-40ed-824b-7222f6104c9c)
<img src="![Image](https://github.com/user-attachments/assets/534f6a6f-a63a-40ed-824b-7222f6104c9c)" style="width: 500px"/>


⚒️ STACKS
HTML
CSS
JS
Vanila JS 100% ( Jquery 100% - 주석처리 )


🔎 웹표준 / 접근성
The W3C Markup Validation Service 검사 완료
크로스 브라우징(크롬, 사파리, 엣지, 파이어폭스, 오페라) 테스트 완료
헤딩(H1~H6) 태그를 활용한 계층 구조
논리적인 내용 순서에 따른 html 설계
img 태그(alt), a 태그(title), table(scope, thead, tbody) 등 태그 속성을 활용한 접근성 향상
🌈 UI / UX
기업소개 사이트에 걸맞는 기업에 대한 정보 전달을 중요시
불화수소를 활용한 제품 생산, 수출하는 기업으로써 제품 소개를 메인페이지 맨 앞에 배치하고 바로가기 버튼을 각각 생성하여 사용자의 접근성을 높임
글로 된 정보가 많은 서브페이지는 단락을 나누어 디자인하는 등 사용자가 읽기 쉽도록 디자인
기존 사이트보다 스크립트를 활용하여 인터랙티브한 UI 구현
좁은 gnb 디자인에서 한눈에 들어오는 1뎁스 gnb 디자인으로 개선
화려한 이미지 사용과 좁은 여백으로 답답한 메인페이지를 시원하고 깔끔한 레이아웃으로 개선
🪄 자바스크립트 구현 기능
이벤트리스너를 활용하여 이벤트(click, mouseover, mouseout, focus, blur)에 따른 메뉴/탭 여닫기
스크롤양에 따른 css 변화, 클래스 추가(그림자 생성, 위치 이동, 애니메이션 추가)
클릭시 상단 이동
반복 실행,중지 / 페이지 이동 버튼을 활용한 메인 슬라이드 구현
aJax를 이용하여 JSON, 오픈API(카카오맵) 데이터 불러오기 (비동기적 통신)
쿠키를 활용한 팝업 제어(오늘 이 창을 열지 않음)
