# 아두이노 컨트롤러를 이용한 유니티 게임 제작

## 1. 목차

[TOC]
> Visual Code에서는 [TOC]하면 목차 생성  
> Github 마크다운에서의 목차생성은 좀더 찾아봐야함

## 2. 팀원

|이름|기수|학과|github ID|담당 파트|
|:----:|:----:|:----:|:----:|:----|
| 강동민 | 30기 | 전자정보통신공학과 | [riyenas0925](https://github.com/riyenas0925)| 동물과 함께하는 협동 게임 |
| 김남훈 | 30기 | 스마트기기공학전공 | [nhk9680](https://github.com/nhk9680)| 큐브로드(포탈) |
| 박동섭 | 31기 | 기계항공우주공학부 | [0WILLE0](https://github.com/0WILLE0)| 제작 시스템 |
| 박상욱 | 31기 | 전자정보통신공학과 | [sw0501](https://github.com/sw0501)| 우연한 탈출 게임 |
| 주이식 | 29기 | 컴퓨터공학과 | [jkey20](https://github.com/jkey20)| 착시현상을 이용한 게임 |
| 황유진 | 31기 | 지능기전공학부 | [hyj378](https://github.com/hyj378)| 빛과 거울을 이용한 게임 |

---

## 3. 스터디
> 매주 목요일 3시에 회의 및 스터디 (3~4시간)

### a. 아두이노 스터디
    
    사용보드 : Arduino UNO
    개발환경 : Arduino IDE 
    사용언어 : C

#### 스터디 계획안 및 가이드

* 아두이노 보드는 동아리에서 지원
> 
* 1~2주는 아두이노 기초 학습
  * [X] Digital I/O - 7/19
    * LED ON/OFF, Button Input
  * [X] Analog I/O - 7/26
    * PWM, CDS
>
* 3주차 부터는 우리가 필요한 기술 학습 예정
  * [ ] I2C 통신 - 8/2
  * [ ] 자이로 센서 - 8/2
  * [ ] RF 통신
  * [ ] 블루투스
  * [ ] 가속도 센서
>
* 아두이노 인터넷 강의는 블루투스 연결하기 까지 듣기
>
* 보드를 안가져왔을땐 아래 사이트에서 시뮬레이션으로 실습 가능 
  * [tinkercad](https://www.tinkercad.com/)
>
* 아두이노 스터디 하면서 사용한 함수들은 정리해서 깃허브에 커밋하기

### b. 유니티 스터디(C#)

    개발환경 : Unity 
    사용언어 : C#

#### 스터디 계획안 및 가이드

* 8월 4일 까지 Unity로 배우는 C# 강의 듣기
> 정리나 실습코드 올리는 거는 자율적으로 하기
>
* 빠르게 스터디 진행후 개발을 하면서 필요한 기능들 구현

---

## 4. 개발 가이드 라인
    협업에 앞서 개발에 관한 공통적인 가이드 라인이 필요하다 생각하여 문서를 작성

### a. 작업 폴더
    E:.
    ├─Datasheet                 // 아두이노 부품 데이터 시트
    ├─Project                   // 유니티, 아두이노 프로젝트 폴더
    │  ├─Arduino_Controller     // 아두이노 스케치
    │  └─Unity_Game             // 유니티 프로젝트
    ├─Study                     // 스터디 개인 폴더
    │  ├─jkey20     
    │  ├─nhk9680
    │  ├─riyenas0925
    │  ├─Study_ds
    │  ├─study_hyj
    │  └─sw0501
    ├─강의 자료                 // 아두이노, 유니티 스터디 강의 
    ├─게임 기획                 // 게임 기획서, 아이디어 정리
    │  ├─게임 아이디어
    │  └─게임 기획
    └─회의록                    // 6팀 회의록
    
### b. 참고 자료 및 사이트
* [프로그래밍 전시회 6팀 위키](https://github.com/2018-Interface-Programming-Exhibition/6team-Arduino_Game_Controller/wiki)
    > 기능 개발중 작업 내용 정리

* [Unity로 배우는 C#](https://programmers.co.kr/learn/courses/1)
    > 프로그래머스 강의

* [C# 문법 정리](https://github.com/2018-Interface-Programming-Exhibition/2team_DotheG-ame/wiki/C%23-기본-문법)
    > 프로그래밍 전시회 2팀 위키

* [아두이노 강의](https://www.inflearn.com/course/%EC%95%84%EB%91%90%EC%9D%B4%EB%85%B8-%EA%B0%95%EC%A2%8C/)
    > 인프런 강의

* [Unity Speed Level Design](https://www.youtube.com/watch?v=DxTS0yyvY9s)
    > 맵 제작시 참고

* [아두이노 시뮬레이터](https://www.tinkercad.com/)
    > 아두이노가 없을때 참고

* [코딩 컨벤션이 필요한 이유](http://itmining.tistory.com/72)

---

> 아래는 아직 활용할지 미정, 회의를 통해서 결정할 예정


---

## 5. 개발 계획
### a. Unity 게임 제작
#### 개강전
* [X] C#으로 배운는 Unity 인터넷 강의 듣기
* [X] 게임 기획 - 맵기획
* [ ] 게임 기획 - 스토리기획
* [ ] 게임 기획 - 필요한 에셋 정하기
* [ ] 맵 제작
#### 개강후
* [ ] 리깅, 애니메이션 작업
* [ ] 유니티 기능 구현 (C# Script)

### b. 아두이노 컨트롤러 제작
#### 개강전
* [X] 아두이노 기초 인터넷 강의 듣기
* [X] 아두이노 Digital Analog I/O 학습 (오프라인 스터디)  
* [ ] 아두이노 통신 프로토콜 공부 (UART, I2C, SPI) (오프라인 스터디) 
* [ ] 자이로, 가속도 센서 공부(오프라인 스터디) 

#### 개강후
* [ ] 아두이노 컨트롤러 평가보드 제작
* [ ] 아두이노 컨트롤러 펌웨어 제작

---

## 6. 게임 기획

### a. 게임 엔진
* 유니티

### b. 게임 컨셉
* FPP(1인칭 시점)
* 키설정은 게임 완성후 결정
* 실사 그래픽으로

### c. 스토리

> 추후 내용 추가 예정

---
