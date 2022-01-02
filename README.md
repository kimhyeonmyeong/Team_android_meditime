## TeamProject_Android_MediNoticeApplication
약 알림 어플리케이션 '약Time'을 전계원씨, 정현재, 김민혁씨와 함께 팀 프로젝트로 개발하였습니다.


### 프로젝트 개요

약이나 영양제 복용에 있어서 적절한 복용횟수와 시간을 고려해 약알람을 설정하고 안내받는 앱을 만들고자 하였습니다.    
이를 위해 약 또는 영양제의 일정 시간, 주기, 복용횟수에 맞게 약알람을 추가하는 기능을 제공합니다.        
또 약 알람이 오면 '먹었어', '안 먹었어'와 같이 음성을 통해 알람을 확인할 수 있습니다.
이를 통해 편리하게 앱을 사용하고 약 복용 사실을 기억하는데에 도움을 주고자 했습니다.     

### 프로젝트 기능

- 음성인식 기반의 약알람 어플리케이션

- 여러 약알람들에 대해 복용시간(요일, 일주기, 월주기 설정 가능) 복용량(사용자 조작)에 맞추어 약알람 추가

- 약 복용일에 '오늘'화면에 먹어야 하는 약들 알람 표시

- 약 알람 시간이 되면 전화형식으로 '알람'제공, 음성 및 터치로 '알람'확인 가능

- 약 알람들 복용 확인시 주단위로 Calender형식으로 복용일지 자동 작성

- 복용 일지별 세부 확인 기능


### 진행기간

2021 - 03 - 02 ~ 06-02

### UI 흐름도 

![image](https://user-images.githubusercontent.com/44837403/147023934-10f192f8-bd34-4467-be39-bb1fb98500df.png)

### 최종 UI

![image](https://user-images.githubusercontent.com/44837403/147023884-0fd1bd9b-1ead-446d-a668-50d7de2059d0.png)



### Specification

- Android Kotlin
- Kakao Newtone 을 활용한 STT
- Kakao Newtone Talk 를 활용한 TTS
- FullScreenIntent Notification 을 활용하여 전화오는 화면 구현
- AlarmManager, BroadcastReceiver, JobIntentService을 활용하여 알람 시 Notification 생성하는 기능 백그라운드로 구현
- SQLiteOpenHelper 을 활용하여 데이터 관리
- Background에서 TTS, STT를 제어하기 위한 Coroutine 비동기 처리   

### 개발 환경
Complie SDK Version: Android 11 (API 30)    
Minimum SDK Version: Android 8.1 Oreo (API 27)    
Gradle Version: 6.5   
JDK version: jdk_1_8    
Android Studio 4.2.1    


