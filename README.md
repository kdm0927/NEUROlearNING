# 🧠 NEUROlearNING
치매 예방 지원 스토리 게임 <br>
Dementia Prevention Support Story Game
<br>
### ✅ Contact
![mailcontact](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white) <br>
팀장 배수연 | bsy5640@gmail.com
<br>

### ✅ Team
<table> <tr> <td align="center"> <a href="https://github.com/suyeonb"><img src="https://github.com/suyeonb.png" width="100px;" alt="배수연 프로필"/><br /><sub><b>배수연</b><br />팀장 / BE / DB</sub></a> </td> <td align="center"> <a href="https://github.com/kdm0927"><img src="https://github.com/kdm0927.png" width="100px;" alt="김다민 프로필"/><br /><sub><b>김다민</b><br />FE / BE</sub></a> </td> <td align="center"> <a href="https://github.com/ieeyesoi"><img src="https://github.com/ieeyesoi.png" width="100px;" alt="이예솔 프로필"/><br /><sub><b>이예솔</b><br />디자인 / PM</sub></a> </td> <td align="center"> <a href="https://github.com/jaeyeo0ng"><img src="https://github.com/jaeyeo0ng.png" width="100px;" alt="조재영 프로필"/><br /><sub><b>조재영</b><br />디자인 / FE</sub></a> </td> </tr> </table>

### ✅ Purpose
1. 치매 예방을 위한 인지 훈련 게임 <br>
2. 스토리 기반으로 기억력, 판단력 등 인지 능력 향상 유도 <br>
3. Android 앱으로 제공 <br>

![android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white) ![googleplay](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)
<br>

### ✅ Tools
![js](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white) ![html](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![css](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![react](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

![java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![kotlin](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white)

![androidstudio](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white) ![unity](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)

![notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) 👉 Notion 프로젝트 페이지 [notionlink](https://www.notion.so/NEUROlearNING-1a8f0c1d63f28071a1d5c167d4dddf59?pvs=4)
<br>

## 깃헙 사용 규칙
#### ✅1. 깃허브 플로우
브랜치 관리 방법:

각 팀원은 feature/* 브랜치에서 작업 → develop으로 병합

develop에서 충분히 테스트한 후 main으로 배포

#### ✅(B) 커밋 & PR (Pull Request) 규칙
📌 커밋 메시지 컨벤션 (명확한 기록을 위해!)

feat: 스토리 진행 기능 추가  

fix: UI 버튼 크기 수정  

refactor: 미니게임 로직 최적화  

docs: README 업데이트 
 
#### ✅ 예시 커밋 메시지:
✔ feat: 스토리 시스템에서 선택지 기능 추가

✔ fix: 미니게임 UI 깨지는 버그 수정

#### 📌 Pull Request (PR) 관리 규칙(고민중)
PR 제목은 [작업 내용]을 명확하게 작성

팀원 중 최소 1명이 코드 리뷰 후 승인 (자동 병합 방지)

develop에 머지 후 팀원에게 공유

## 📌 개발 순서 (각 팀원이 해야 할 작업)
### 🎯 1. 새로운 기능 개발할 때
##### 최신 develop 브랜치 가져오기
> git checkout develop
> 
> git pull origin develop


##### 새로운 기능 브랜치 생성
> git checkout -b feature/mini-game1


##### 코드 작성 후 커밋
> git add .
>
> git commit -m "feat: 십자말 풀이 미니게임 기본 로직 추가"


##### 원격 깃허브에 업로드
> git push origin feature/mini-game1

### 🎯 2. PR(Pull Request) 생성(고민중)
GitHub에서 feature/mini-game1 → develop 으로 Pull Request(PR) 생성

팀원이 코드 리뷰 후 승인 → 병합

### 🎯 3. 최신 코드 동기화
##### develop 브랜치 최신 상태 가져오기
> git checkout develop
>
> git pull origin develop

##### 새로운 작업 브랜치 생성 후 반복
> git checkout -b feature/next-task
