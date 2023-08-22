2023 SW 경진대회 출품작 : 좀비 FPS 게임
===  

# PC 버전
## 파일명
Zombie_PC.zip
## 시점
* 마우스 이동 방향에 따라 플레이어의 시선 변화한다. 
## 제어
* 마우스 좌클릭으로 총을 발사할 수 있으며, R 키로 총알을 장전할 수 있다.
## 좀비
* 내비게이션 시스템을 시용하여 플레이어를 따라가도록 한다.  
* 좀비는 플레이어를 찾아 공격하고, 사망 시 추적을 중단한다.  
## 화면 구성
* 탄알, 남은 탄알, 현재 적 웨이브와 남은 적의 수, 점수를 나타낸다.  
* 게임오버 및 재시작을 표시한다.  

![제목을-입력해주세요_](https://github.com/this-is-hyeon/sungshin2023/assets/113247511/50b7b5bf-d021-4c01-9815-b4f0a0881388)


# 모바일 버전
## ARDUnity 애셋 활용
아래와 같은 아두니티의 특징을 적극 활용한다.
* 와이어 편집(시각적 프로그래밍)
* 아두이노 스케치 파일을 자동으로 생성한다.
* 모든 아두이노 시리즈를 지원한다. (호환 보드 포함)
* 코딩 초보자를 위한 최적의 솔루션. (GameObject용 PlayMaker 및 다양한 리액터 지원)
* 멀티 플랫폼(Windows, Mac, Android, iOS에서 작동)
## ARDUnity Deluxe 사용
Basic은 아두니티를 교육하거나 학습할 수 있도록 기본적인 기능 위주로 포함시켜서 요구되는 배경 지식이 많지 않고 사용되는 부품도 쉽고 저렴하게 구할 수 있게 구성되어 있으나, Deluxe는 보다 다양한 활용이 가능하도록 관심도가 높고 이슈가 될 만한 기능들을 포함시켜서 좋은 품질의 프로젝트가 만들어지도록 구성됐다. 따라서 Deluxe 버전을 사용한다.  


![2023-08-23 (2)](https://github.com/this-is-hyeon/sungshin2023/assets/113247511/06a0fe41-c5f3-4345-865a-8f89f204c36c)
## 파일 구성
* 유니티 파일 - Zombie.zip
* apk 파일 - Zombie_apk.zip
* 아두이노 파일 - Zombie_Controller.zip
## 컨트롤러 
![2023-08-22 (2)](https://github.com/this-is-hyeon/sungshin2023/assets/113247511/d07a78a2-c174-4ca5-880d-90dedd2f2ab9)


![KakaoTalk_20230822_032306730](https://github.com/this-is-hyeon/sungshin2023/assets/113247511/8ba06ec3-2d0e-4ac0-9f06-4cd4db9408fb)
위와 같이 구성한 Wire Editor를 스케치하여, 사진처럼 구성한 아두이노 보드에 업로드한다.

* HC-06: 블루투스 통신
* MPU6050: 컨트롤러 기울기 감지
* Joystick: 플레이어 위치 이동










