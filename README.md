# 🏃‍♀️다이어트 기록 서비스

다이어트 목표를 설정하고, 다이어트 과정으로 식단, 수분 섭취, 운동 계획과 실천 등을 기록할 수 있는 서비스를 제작하고자 합니다.



## 프로젝트 기능 및 설계
- 회원가입/로그인 기능
  - 이메일 인증 회원가입
  - 사용자는 회원가입을 할 수 있다. 일반적으로 모든 사용자는 회원가입시 USER 권한 (일반 권한)을 지닌다. 
  - 회원가입시 아이디와 패스워드를 입력받으며, 아이디는 unique 해야한다.
  - 사용자는 로그인을 할 수 있다. 로그인시 회원가입때 사용한 아이디와 패스워드가 일치해야한다.
 
- 회원 정보 조회 기능
  - 나의 목표 체중, 운동량, 수분 섭취량
  - 현재 체중
  - 오늘의 운동량
  - 오늘의 수분 섭취량
    
- 목표 설정
  - 현재 키와 목표 체중 설정
  - 목표 운동량/운동계획 등록
  - 목표 수분섭취량 설정
           
- 체중 기록
  - 오늘의 체중 등록
    
- 식단 기록
  - 아침,점심,저녁,간식 시기에 맞는 식단을 글과 사진을 통해 기록
  - 기록했던 식단 수정
  - 기록했던 식단 삭제
    
- 운동 기록
  - 오늘 진행한 운동종목과 운동횟수 또는 운동시간을 기록
  
- 수분섭취량 기록
  - 오늘 수분섭취량 기록
  
- 기록 조회
  - 원하는 특정 날짜의 모든 기록 조회

## ERD 
![ERD](doc/img/erd.png)

## Trouble Shooting
[go to the trouble shooting section](doc/TROUBLE_SHOOTING.md)

### Tech Stack
<div> 
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> 
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">
        
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
</div>
