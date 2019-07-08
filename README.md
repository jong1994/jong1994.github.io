# Google Home(Dialogflow)와 AWS를 <br>연동하여 독거노인의 주거 환경 개선 

#### Cross-Platform을 통하여 현실적으로 독거노인들에게 도움을 주는 방법 

1. 최신 IT기술에 익숙하지 못한 독거노인들에게 음성으로 기술들을 쉽게 접근하게 도와준다.
   - 최신 IT기술에 익숙하지 못한 독거노인들에게 음성을 통한 Smart Devices 통제
   - 음성(Google Home)으로 위험 알림 서비스 제공
   
2. 혼자 사는 독거노인들의 겪는 외로움의 부분적 해소에 도움
   - Chat Bot 
   - 감정 파악을 통하여 감정에 맞는 대화 서비스 제공
---

### 구현이 완료되면 아래와 같은 어플리케이션을 볼 수 있습니다.

![](images/iOS_guide/2.png)

---

### 해당 세션을 진행하기 위해서는 아래와 같은 것들이 필요합니다.

#### 1. AWS 계정

AWS 서비스를 사용하여 서버를 구축하기 때문에 AWS 계정이 필요합니다.

- AWS 계정 만들기 [이동](https://aws.amazon.com/ko/)

본 세션에서는 아래와 같은 서비스를 이용합니다.
~~~
- AWS RDS
- AWS Elastic Beanstalk
~~~

본 세션의 일환으로 시작하는 모든 리소스는 AWS 계정이 12개월 미만인 경우, 제공하는 AWS 프리티어로 충분히 가능합니다. 프리티어를 넘어서는 경우, 과금 될 수도 있습니다. 따라서, 새로운 실습용 계정을 만드시길 권장합니다. 자세한 내용은 [AWS 프리 티어 페이지](https://aws.amazon.com/free/)를 참조하세요.

---

#### 2. Xcode

본 세션은 iOS 어플리케이션을 통해 클라이언트를 구현하기 때문에 Xcode 및 CocoaPods 등이 필요합니다.

- Xcode 설치 가이드 [이동](https://github.com/AUSG/ausg-seminar-2019/tree/master/iOSTrack/Preparation)

---

### 준비가 끝났으니 단계에 따라 천천히 따라와 주세요! 👋

- [RDS 생성하기](https://github.com/jaehui327/AUSG-iOS-MapOfRestaurant/blob/master/guide/RDS_guide.md)

- [Node.js 코드 만들기](https://github.com/jaehui327/AUSG-iOS-MapOfRestaurant/blob/master/guide/Nodejs_guide.md)

- [Elastic Beanstalk으로 배포하기](https://github.com/jaehui327/AUSG-iOS-MapOfRestaurant/blob/master/guide/Beanstalk_guide.md)

- [iOS 앱과 API 서버 연동하기](https://github.com/jaehui327/AUSG-iOS-MapOfRestaurant/blob/master/guide/iOS_guide.md)

- [삭제 가이드](https://github.com/jaehui327/AUSG-iOS-MapOfRestaurant/blob/master/guide/delete_guide.md)
