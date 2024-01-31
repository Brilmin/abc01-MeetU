# MeetU - Backend

## 프로젝트 개요 및 배경
- MBTI와 관심사를 통한 새학기 친구찾기 플랫폼 (팀 프로젝트)
- 새학기 같은 반 친구를 보다 쉽게 사귀기 위해 동일한 Mbti와 관심사를 가진 친구를 추천해주고 쪽지를 주고 받는 서비스를 기획하였습니다

## 프로젝트 기간 & 인원
- 프로젝트 기간 : 24.12.27 ~ 24.01.23
- 개발인원 : 프론트엔드 4명 , 백엔드 5명

## 나의 역활 (마이페이지)
- 배경색 저장 기능
- 저장된 배경색 목록 조회 기능
- 배포 환경 구성 및 배포(AWS)

  ### 공동
-  ERD 작성
-  요구사항 정의서 작성
-  Api 명세서(회원가입,로그인,회원정보,마이페이지 파트)
-  테이블 정의서(멤버,Mbti,관심사 파트)
-  Postman을 활용한 Api 테스트
  
## 미완수 나의 역활
- Mbti와 관심사 저장,조회 기능
- 동일 Mbti와 관심사를 활용한 친구 추천 기능
- 멤버 닉네임 배경색 수정 기능(회원정보수정에 접목)
- 전반적인 멤버 관련 기능(보조)

##  개발 환경
![GIT](https://img.shields.io/badge/GIT-%23E34F26.svg?style=for-the-badge&logo=GIT&logoColor=white)
![GITHUB](https://img.shields.io/badge/GITHUB-%2320232a.svg?style=for-the-badge&logo=GITHUB&logoColor=%2361DAFB)
![INTELLIJIDEA](https://img.shields.io/badge/INTELLIJIDEA-%231572B6.svg?style=for-the-badge&logo=INTELLIJIDEA&logoColor=white)
![WINDOWS](https://img.shields.io/badge/WINDOWS-%23007ACC.svg?style=for-the-badge&logo=WINDOWS&logoColor=white)
![POSTMAN](https://img.shields.io/badge/POSTMAN-%23E34F26.svg?style=for-the-badge&logo=POSTMAN&logoColor=white)

## 기술 스택
<img src="https://img.shields.io/badge/JAVA-5A29E4?style=for-the-badge&logo=JAVA&logoColor=white">   <img src="https://img.shields.io/badge/GRADLE-5A29E4?style=for-the-badge&logo=gradle&logoColor=white">
<img src="https://img.shields.io/badge/mySQL-4479A1?style=for-the-badge&logo=mySQL&logoColor=white">
<img src="https://img.shields.io/badge/spring security-6DB33F?style=for-the-badge&logo=spring security&logoColor=white"> 
<img src="https://img.shields.io/badge/spring boot-6DB33F?style=for-the-badge&logo=spring boot&logoColor=white">
  <img src="https://img.shields.io/badge/JWT-6DB33F?style=for-the-badge&logo=jwt&logoColor=white">
  <img src="https://img.shields.io/badge/AWS EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white">
  <img src="https://img.shields.io/badge/AWS RDS-FF9900?style=for-the-badge&logo=amazonrds&logoColor=white">

  ## 프로젝트 진행 과정
  - 주제 선정을 위해 후보 쇼핑몰, 운동기록, 여행일기, 친구 만들기 중에서 논의와 투표를 통해 친구 만들기가 선정됨 </br>
    (기존 여행일기가 선정되어 요구사항 정의서 및 테이블 정의서 진행중 멤버 변동 이슈로 인해 재 진행)
    
  - [요구사항 정의서](https://docs.google.com/spreadsheets/d/1L4wACPQCKQ7hr-v-saBtJC0c9OAXE6tAE3GvGZy0RnM/edit#gid=461303735), [ERD](https://ifh.cc/v-xBxVPw), 
[테이블 명세서](https://docs.google.com/spreadsheets/d/1L4wACPQCKQ7hr-v-saBtJC0c9OAXE6tAE3GvGZy0RnM/edit?usp=sharing), [Api 명세서 작성](https://www.notion.so/codestates/API-bb14e1c350b347f6afcaca266ca21112)

- 열고 닫는 목록 형식이 겉으로 보기엔  깔끔하나 보는 사람 입장에서 번거로움이 동반되는데  그냥 표시 되는 방식이 나을지 고민.
<details>
  <summary>개인 브런치에서 레이어드 아키텍처 패턴에 따라 코드 작성 및 수정</summary>
  <ul>
    <li>구현 코드 사진 또는 저장소의 파일 주소 등록 및 설명 기재</li>
  </ul>
</details>

<details>
  <summary>Postman을 활용한 Api 테스트 및 머지 진행</summary>
  <ul>
    <li>포스트맨을 이용한 api 테스트 사진 첨부 및 설명 기재</li>
  </ul>
</details>

<details>
  <summary>AWS를 활용한 배포 진행 후 발표</summary>
  <ul>
    <li>EC2, RDS 사진과 수동 로컬 실행과, 백그라운드 실행 사진 및 설명 기재 </li>
  </ul>
</details>

## 회고 및 개선방안
- 코드 구현을 어떻게 할지 고민을 했고 진행해보았으나 계속해서 막혔고 멘토링을 통해 해당 방식으로는 그렇게 구현하기가 어렵다라는 말을 듣고 모두 지우고 재작성을 했던거 다듬어서 기재
- 기타 다른 이슈, 아쉬운점 1~2개 더 찾아서 넣기
- 위에 언급된 내용들의 개선방안으로는 부분적인 내용을 채우는것이 아닌 전체적인 재 교육이 더 좋을듯한데 어떤 부분은 어떤분의 교육을 들을 예정이고 진행하며 추가로 궁금한점, 알게된 부족한 점을 매꿔 이후 기재할 다른 프로젝트에서 성장 성과를 보일것임 이런식으로 기재할 예정
이후 강의를 수강하고나서 하단에 강의를 듣고나서 다시 이 프로젝트를 보고 드는 생각이나 아쉬웠던점을 추가로 기재하는것도 좋을듯함
  (ㅁㅁ님의 자바~스프링, DB ㅁㅁ님꺼 AWS ㅁㅁ님꺼)

## 완성본 볼 수 있는 사진, 링크 첨부(가능한 사진이 좋을듯홤)
