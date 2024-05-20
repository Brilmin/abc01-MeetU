# MeetU - Backend
![image](https://github.com/Brilmin/abc01-MeetU/assets/118905157/2236f264-64a0-4a73-9ecd-673b4697a4e3)

## 프로젝트 개요 및 배경
- MBTI와 관심사를 통한 새학기 친구찾기 플랫폼 (팀 프로젝트) https://github.com/codestates-seb/abc02_002
- 새학기 같은 반 친구를 보다 쉽게 사귀기 위해 동일한 Mbti와 관심사를 가진 친구를 추천해주고 쪽지를 주고 받는 서비스를 기획하였습니다

## 프로젝트 기간 & 인원
- 프로젝트 기간 : 24.12.27 ~ 24.01.23
- 개발인원 : 프론트엔드 4명 , 백엔드 5명

## 나의 역할 (마이페이지)
- 배경색 저장 기능
- 저장된 배경색 목록 조회 기능
- 배포 환경 구성 및 배포(AWS)

  ### 공동
-  ERD 작성
-  요구사항 정의서 작성
-  Api 명세서(회원가입,로그인,회원정보,마이페이지 파트)
-  테이블 정의서(멤버,Mbti,관심사 파트)
-  Postman을 활용한 Api 테스트
  

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


- 개인 브런치에서 레이어드 아키텍처 패턴에 따라 코드 작성 및 수정
구현 코드 사진 또는 저장소의 파일 주소 등록 및 설명 기재

- Postman을 활용한 Api 테스트 및 머지 진행
    포스트맨을 이용한 api 테스트 사진 첨부 및 설명 기재

- AWS를 활용한 배포 진행 후 발표
  EC2, RDS 사진과 수동 로컬 실행과, 백그라운드 실행 사진 및 설명 기재

## 회고 및 개선방안
- 코드 구현에 있어 어떤 방식으로 접근 할지 신중을 기할 필요가 있을 듯 하다
- 너무 이른 도움 요청은 좋지 않겠지만 혼자 해결 하고자 매달리는 것도 독인듯 하다 (적절히 조절하자)<br>
  (진행 하다 벽에 봉착 했고 뚫어 보고자 노력 해봤으나 어려움을 느껴 멘토링을 신청 했고 답 해주시길 그 방식으로는 구현이 어렵다라는 말을 듣고 처음부터 다시 시작 했던 경험을 얻게 되었습니다)
- 위 와 같은 이유로 미 구현된 항목들. 다음 프로젝트에선 같은 실수를 하지 말고 부족함을 보완해 가도록 하자 <br>
  (Mbti와 관심사 저장,조회 기능 , 동일 Mbti와 관심사를 활용한 친구 추천 기능 , 멤버 닉네임 배경색 수정 기능(회원정보수정에 접목) , 전반적인 멤버 관련 기능(보조)
