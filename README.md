# IBK 기업은행
메인 페이지 HTML, CSS, JavaScript 코드

## Text
코딩에 필요한 text

```
자동화기기 지연인출, 이체제도 변경 안내
9월2일부터 100만원 이상 입금된 통장에서 자동화기기를 통해 인출 및 이체하는 경우 30분 동안 인출 및 이체가 되지 않습니다.

씨크리트카드 번호 입력 주의 및 사진촬영 금지
보안강화 등의 사유로 씨크리트카드 번호 2개 초과 또는 OTP번호를 요구하는 경우는 금융사기이오니 절대 응하지 마시기 바랍니다.

「IBK ONE뱅킹(개인,태블릿,금융센터)」서비스 종료 안내
홈페이지 SMS문자전송 서비스 종료 안내
제52회 저축의 날 기념 그림 공모전
「전자금융사기 예방서비스」변경사항 안내

2015년 하반기 신입행원 공채 서류전형 합격자발표
「IBK CS교육방송」제작기업 선정을 위한 입찰공고
문화체육관광부「문화콘텐츠 강소기업 육성」5차...
2015년 중소기업은행 정기재물조사 용역

개인ㆍ신용정보 처리방침
전자민원접수
보호금융상품등록부
권익위 부패.공익광고
상품공시실
채용안내
웹메일
고객센터 국내 1566-2566, 1588-2588 / 해외 82-31-888-8000
서민금융종합지원센터 1644-0533
모바일웹

Copyright 2015. IBK(INDUSTRIAL BANK OF KOREA) All rights reserved.

개인뱅킹
조회 이체 예금/펀드/보험 신용카드 대출 외환 공과금 수표/어음 부가서비스 정보관리

기업뱅킹
조회 이체 예금/펀드/보험 신용카드 B2B전자결제 대출 외환 공과금 자금관리 부가서비스 환경설정

금융상품
예금 대출 펀드 신탁 외환 보험 상품트리 퇴직연금

금융서비스
스마트금융 뱅킹서비스 알림서비스 제휴서비스 부가서비스

금융정보
재테크 부동산 경매/공매 세무 증권

카드
카드안내/신청 카드금융(대출) 나의카드관리 카드서비스 혜택/우대 카드가이트

고객센터
고객상담 분실신고 자료실 VIP우대서비스 은행이용안내 이벤트 개인정보보호정책

보안센터
전자금융사기예방 보안수단 금융거래유의사항 PC보안서비스 신입금계좌지정서비스 이용시간제한서비스 보안FAQ 전기통신금융사기 지급정지계좌 국제보안인증

```

## jQuery Plugin
### [BXSLIDER](http://bxslider.com)
### [BXSLIDER Options](http://bxslider.com/option)
이미지 슬라이드 기능을 제공하는 jQuery 플러그인

```js
$('CSS선택자').bxSlider({
    mode: 'horizontal', // 슬라이드의 종류
    speed: 500, // 슬라이드가 움직이는 속도
    slideMargin: 0, // 각각의 슬라이드 사이의 간격
    startSlide: 0, // 시작 슬라이드 번호를 정할 수 있습니다
    randomStart: false, // 시작 슬라이드 번호를 랜덤하게 정할 수 있습니다.
    easing: null, // 'easing' 타입을 설정
    captions: false, // 이미지에 타이틀(캡션) 포함 여부
    responsive: true, // 반응형 슬라이드 유무
    preloadImages: 'visible', // 보이는 이미지만 로드할 것인지, 미리 전부 로드할 것인지 설정
    pager: true, // 페이지 번호를 보일 것인지 설정 --------------------------------------------------------------------
    pagerSelector: '', // 페이지 번호가 들어갈 선택자 입력
    controls: true, // 이전/다음 버튼 표시 유무------------------------------------------------------------------------
    prevText: 'Prev', // 이전 버튼의 텍스트
    nextText: 'Next', // 다음 버튼의 텍스트
    prevSelector: null, // 이전 버튼이 들어갈 선택자 입력
    nextSelector: null, // 다음 버튼이 들어갈 선택자 입력
    autoControls: false, // 시작/정지 버튼 유무(!! auto 옵션이 true 일 때 적용 가능)-----------------------------------
    startText: 'Start', // 시작 버튼 텍스트
    stopText: 'Stop', // 정지 버튼 텍스트
    autoControlsCombine: false, // 시작과 정지 버튼 중 한가지만 보이고 눌렀을 때 토글 기능
    autoControlsSelector: null, // 시작/정지 버튼이 들어갈 선택자 입력
    auto: true, // 자동 슬라이드 유무
    pause: 4000, // 자동 슬라이드 시간
    autoStart: true, // 처음부터 시작할 것인지, 시작 버튼을 눌렀을 때 시작할 것인지, true = 처음부터 시작
    autoDirection: 'next', // 자동 슬라이드 방향
    autoHover: false, // 마우스 오버 이벤트 발생했을 때 자동 슬라이드 정지 여부
    autoDelay: 0, // 자동 슬라이드 전 대기시간 설정
    minSlides: 1, // 최소한으로 보여줄 슬라이드 갯수
    maxSlides: 1, // 최대한으로 보여줄 슬라이드 갯수
    moveSlides: 0, // 1개 이상의 슬라이드가 보일 때 한번에 움직일 슬라이드의 갯수
    slideWidth: 0, // 슬라이드의 가로 사이즈(꼭 설정하세요!)------------------------------------------------------------
    onSliderLoad: function(currentIndex){}, // 슬라이드가 준비되었을 때 실행
    onSlideBefore: function($slideElement, oldIndex, newIndex){}, // 슬라이드 전환 직전에 실행
    onSlideAfter: function($slideElement, oldIndex, newIndex){} // 슬라이드 전환 완료 후 실행
});
```