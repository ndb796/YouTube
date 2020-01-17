## YouTube 방송 준비하기

* YouTube 방송용 준비물 Repository

### 방송용 BGM

* [bgm](./bgm) 폴더에 있는 Copyright Free 음악을 이용할 수 있습니다.

### 방송용 Software

* [OBS](https://obsproject.com/ko/download)

### 방송용 Hardware

* Blue Yeti USB Microphone
* Logitech C920 Webcam
* 크로마키 천

### 방송용 설정

#### [유튜브 라이브 스트리밍 설정](https://www.youtube.com/live_dashboard)
* 기본 정보에 진행할 방송의 제목 및 설명 기입
* '다음 스트림 예약'을 통해 구독자들에게 방송 예정 시간 알림
* '주요 채팅' → '새 창에서 채팅 열기'로 댓글창을 화면에 띄우기 → OBS 소프트웨어 → [소스 목록] → [브라우저]

#### OBS 설정

* 초기 설정: [구성 마법사] → [방송 최적화, 녹화는 부차적으로 사용] → [1920x1080 해상도, 30 FPS] → [비트레이트 2500]
* 화면 설정: [소스 목록] → [디스플레이 캡처], [오디오 출력 캡처], [비디오 캡처 장치] 추가 
* 기타 설정: [설정] → [일반: 방송 시 자동으로 녹화] → [출력 - 녹화 형식: mp4] → [오디오 설정]
* 투명 채팅창 설정: [소스 목록] → [브라우저] → [CSS 설정](./chat.css) 혹은 [CSS 만들기](https://chatv2.septapus.com/)
