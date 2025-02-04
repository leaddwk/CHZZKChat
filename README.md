# CHZZKChat
치지직 공식 채팅 URL에 CSS입혀서 API 따로 거치지 않고 쉽게 OBS에 투명 배경으로 송출하는 방법입니다
OBS 실행 -> `+`누르기 -> URL에 `https://chzzk.naver.com/live/{채널 ID}/chat` 입력
사용자 지정 CSS에 밑에 내용 복사해서 입력하면 끝
추가 디자인을 원하시면 AI같은거로 CSS 작성해서 추가로 더 넣으면 됩니다

채팅 내용 디자인
```
.live_chatting_message_text__DyleH {
    font-size: 12px !important; /*폰트 사이즈를 12픽셀로 설정*/
    color: #FF00FF !important; /*글자색을 보라색으로 설정*/
    font-weight: bold !important; /*글씨를 볼드체로 설정*/
    -webkit-text-stroke: 3px black !important; /*글씨를 3픽셀 만큼의 검은색 아웃라인(외곽선)을 만듦*/
}
```

이름 디자인
```
.name_text__yQG50 {
    채팅 내용 디자인과 같음
}
```

뱃지 디자인
```
.live_chatting_username_wrapper__iJpJB {
    display: none !important;
}
```


```
.live_chatting_ranking_container__RVHvS {
    display: none;
}

.live_chatting_header_container__k0hTT {
    display: none;
}

.live_chatting_area__hUPJw {
    display: none;
}

.live_chatting_list_fixed__Wy3TT {
    display: none;
}

.live_chatting_list_wrapper__a5XTV {
    padding: 0px;
    margin: 0px;
}

.live_chatting_list_big_padding__iG-3T {
    display: none;
}

.live_chatting_ranking_no_ranking_button__QBSRd {
    display: none;
}

::-webkit-scrollbar {
    display: none;
}

.live_chatting_fixed_mission_container__T6EY5 {
  display:none;
}

html, body{
    background-color: rgba(0,0,0,0) !important;
}

.live_chatting_container__SvtrD {
    background-color: rgba(0,0,0,0);
}

body {
    background-color: rgba(0,0,0,0) !important;
}

body * {
    background-color: inherit !important;
}
```
