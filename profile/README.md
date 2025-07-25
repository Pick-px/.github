# 🎨 실시간 픽셀 아트 게임 Pick-Px

<img width="652" height="652" alt="image" src="https://github.com/user-attachments/assets/1753df73-5b8a-4d61-b5a5-1f9a489bb6ec" />

</br>

## 프로젝트 소개

Pick-Px는 사용자들이 실시간으로 함께 픽셀 아트를 그릴 수 있는 협업 플랫폼입니다.
캔버스 공유, 실시간 채팅, 게임 모드 등 다양한 기능을 제공합니다.

- 배포 URL : [https://pick-px.com/](https://pick-px.com/)

</br>

## 팀원

| [<img src="https://avatars.githubusercontent.com/u/80505099?v=4" width="230px;" alt=""/>](https://github.com/BusChanny) | [<img src="https://avatars.githubusercontent.com/u/202524188?v=4" width="230px">](https://github.com/yoominlee00) | [<img src="https://avatars.githubusercontent.com/u/202568995?v=4" width="230px" >](https://github.com/anonymity-developer) | [<img src="https://avatars.githubusercontent.com/u/97867254?v=4" width="230px" >](https://github.com/seonghyeon0312) | [<img src="https://avatars.githubusercontent.com/u/70210457?v=4" width="230px">](https://github.com/Anas-wg) |
| :---------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------: |
|                                       [👑 박창현](https://github.com/daven-park)                                        |                                     [이유민](https://github.com/yoominlee00)                                      |                                      [백지원](https://github.com/anonymity-developer)                                      |                                     [박성현](https://github.com/seonghyeon0312)                                      |                                     [조완기](https://github.com/Anas-wg)                                     |
|    [<img src="http://mazassumnida.wtf/api/mini/generate_badge?boj=buschanny">](https://solved.ac/profile/buschanny)     |  [<img src="http://mazassumnida.wtf/api/mini/generate_badge?boj=yumin606">](https://solved.ac/profile/yumin606)   |        [<img src="http://mazassumnida.wtf/api/mini/generate_badge?boj=dld2820">](https://solved.ac/profile/dld2820)        |    [<img src="http://mazassumnida.wtf/api/mini/generate_badge?boj=gkdms325">](https://solved.ac/profile/gkdms325)    | [<img src="http://mazassumnida.wtf/api/mini/generate_badge?boj=false90">](https://solved.ac/profile/false90) |

</br>

## 주요 기능

- 🎨 **실시간 픽셀 아트 캔버스**: 다중 사용자가 동시에 픽셀을 그릴 수 있는
  협업캔버스
- 💬 **실시간 채팅**: 캔버스 내에서 실시간으로 소통할 수 있는 채팅 기능
- 🎮 **게임 모드**: 퀴즈를 통한 게임형 캔버스 경험
- 👥 **그룹 시스템**: 캔버스를 그룹 단위로 관리하고 공유
- 📱 **반응형 디자인**: 데스크톱과 모바일 환경 모두 지원
- 🔐 **OAuth 로그인**: Google 로그인 지원
- 🎵 **사운드 효과**: BGM 및 효과음으로 몰입감 있는 경험 제공

</br>

## 기술스택

<img width="569" height="350" alt="image" src="https://github.com/user-attachments/assets/c130f82c-dc27-4c7e-ad5c-6d009c650cc7" />

</br>

## 아키텍처

<img width="1290" height="594" alt="image" src="https://github.com/user-attachments/assets/baae97f2-000f-47c4-ba96-29e0c892ccd5" />

</br>

## 브랜치 전략

Git-flow 전략을 기반으로 main, develop 브랜치와 feature 보조 브랜치를 운용했습니다.

- main, develop, Feat 브랜치로 나누어 개발을 하였습니다.
- main 브랜치는 배포 단계에서만 사용하는 브랜치입니다.
- develop 브랜치는 개발 단계에서 git-flow의 master 역할을 하는 브랜치입니다.
- Feat 브랜치는 기능 단위로 독립적인 개발 환경을 위하여 사용하고 merge 후 각 브랜치를 삭제해주었습니다.

</br>

## 발표 및 시연 영상

[시연 영상 링크](https://drive.google.com/file/d/1_6sUWeImzXtCVJP6TgkXGxc7J5MaAzxY/view?usp=sharing)

</br>

## 게임 설명 영상

[게임 설명 영상 링크](https://youtu.be/9MYnUduKhLQ?si=DiZa1nxFdAFxkWcp)

</br>

### 목차

- [로그인](#로그인)
- [픽셀 찍기](#픽셀-찍기)
- [3초간 쿨다운](#3초간-쿨다운)
- [이미지 가이드 기능](#이미지-가이드-기능)
- [이미지 가이드 따라그리기](#이미지-가이드-따라-그리기)
- [그룹 커뮤니케이션 : 이미지 가이드 공유](#그룹-커뮤니케이션--이미지-가이드-공유)
- [그룹 커뮤니케이션 : 채팅](#그룹-커뮤니케이션--채팅)
- [앨범](#앨범)
- [마이페이지](#마이페이지)
- [게임](#게임-공지)

### [로그인]

![](https://velog.velcdn.com/images/yoominlee00/post/86e24093-96b8-41e7-9d7b-e7c07206aca6/image.gif)

- 간편한 게스트 로그인 혹은 Google OAuth 로그인이 가능합니다.

### [픽셀 찍기]

![](https://velog.velcdn.com/images/yoominlee00/post/caf2e600-fa18-4d35-a055-749b33df4001/image.gif)

- 마우스 휠로 확대/축소
- 클릭 후 드래그로 캔버스 이동

![](https://velog.velcdn.com/images/yoominlee00/post/53538087-d279-4079-9923-c1e0ee7a087e/image.gif)

- 픽셀을 클릭한 후 팔레트에서 색상 선택
- 체크 버튼 클릭 -> 픽셀 칠하기

### [3초간 쿨다운]

![](https://velog.velcdn.com/images/yoominlee00/post/10415d86-87e3-4b88-bb61-b9c31105dc71/image.gif)

- 색을 칠하고 나면 3초간 쿨다운이 발생합니다
- 3초 후 다음 픽셀을 칠할 수 있습니다.

### [이미지 가이드 기능]

> 픽셀 아트로 그리고 싶은 이미지를 더 쉽게 완성할 수 있도록 이미지 가이드 기능을 제공

![](https://velog.velcdn.com/images/yoominlee00/post/10415d86-87e3-4b88-bb61-b9c31105dc71/image.gif)
![](https://velog.velcdn.com/images/yoominlee00/post/55ac32de-3b1c-4b39-b789-815433f9fcb8/image.gif)
![](https://velog.velcdn.com/images/yoominlee00/post/a8e18e55-05e3-4495-9232-ea55025a5f70/image.gif)

### [이미지 가이드 따라 그리기]

![](https://velog.velcdn.com/images/yoominlee00/post/5346067e-2530-426d-8e72-2dc79d4a2785/image.gif)

### [그룹 커뮤니케이션 : 이미지 가이드 공유]

![](https://velog.velcdn.com/images/yoominlee00/post/c2196a18-7370-4678-b6d8-21dc2b7c73bb/image.gif)
![](https://velog.velcdn.com/images/yoominlee00/post/ff0f2160-1c30-40dc-89e2-7ed10616f33c/image.gif)

### [그룹 커뮤니케이션 : 채팅]

![](https://velog.velcdn.com/images/yoominlee00/post/35b0d5ab-9e81-41cc-b5b2-d617f9dccd70/image.gif)

- 첫 접속시 해당 캔버스의 전체 그룹 채팅방에 입장
- 그룹 참가시 그룹원들과 소통 가능

### [앨범]

![](https://velog.velcdn.com/images/yoominlee00/post/518b12c5-6b67-4501-955a-09c26c5a712b/image.gif)

- 지금까지 캔버스 히스토리를 확인할 수 있습니다.

### [마이페이지]

![](https://velog.velcdn.com/images/yoominlee00/post/bda26525-6329-4c9c-bd2a-00fcad4b5dd8/image.gif)

## [게임 모드]

더 많은 픽셀을 자신의 색상으로 칠하면 이기는 게임.

### 게임 공지

![](https://velog.velcdn.com/images/yoominlee00/post/fa5acef5-45fb-40e4-85e8-778b48ac1fa6/image.png)

- 게임 시작 30초 전 접속한 모든 유저에게 전체 공지창이 나타남

### 게임 대기 및 색상 할당

![](https://velog.velcdn.com/images/yoominlee00/post/4d970306-26c6-4bd2-b5fb-38f8b5b8f999/image.gif)

- 대기 화면에서 플레이어 마다 고유의 색상이 랜덤 배정
- 게임 모드에서는 미리 배정받은 색상으로 만 색칠이 가능

### 자유 색칠

![](https://velog.velcdn.com/images/yoominlee00/post/278231d4-438a-479f-b86a-62943ca78053/image.gif)

- 검은색 픽셀은 아직 주인이 없는 빈 공간
- [조작법]
  - PC: 방향키 이동 + Enter키로 칠하기
  - 모바일: 더블 탭

### 픽셀 탈취 시도

![](https://velog.velcdn.com/images/yoominlee00/post/7373ad0d-18f0-4634-9c6b-7d0e98b61814/image.gif)

### 문제 풀이

![](https://velog.velcdn.com/images/yoominlee00/post/6cf402a6-a5f7-43b7-bdf9-496a35c4646b/image.gif)

- 정답을 맞히면 탈취 성공, 해당 픽셀이 내 색상으로 변경
- 오답일 경우 생명 1개 차감
- 생명은 2개가 주어짐

### 탈락

![](https://velog.velcdn.com/images/yoominlee00/post/3de66a94-6cfd-4e50-b6f6-37d7db768164/image.gif)

- 생명을 모두 소진시 탈락
- 탈락시 보유하던 픽셀이 모두 검은색으로 처리
