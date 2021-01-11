## 보안동향 2021년 01월 11일  

  
### 1. 새로운 공격으로 해커가 Google Titan 2FA 보안 키를 복제 할 수 있음  
     
https://thehackernews.com/2021/01/new-attack-could-let-hackers-clone-your.html?&web_view=true
 

2 단계 인증 (2FA) 장치에 내장 된 칩의 채널을 이용하여 어떻게 복제 할 수 있는지 보여줌  
  

취약점 (**CVE-2021-3011** )으로 인해 악의적인 행위자가 Google Titan Key 또는 YubiKey와 같은 FIDO U2F (Universal 2nd Factor) 장치에서 피해자의 계정에 연결된 암호화 키 또는 ECDSA 개인키를 추출 하여  손상 할 수 있음  


---


### 2. TeamTNT 봇넷은 이제 Docker API 및 AWS 자격 증명을 훔침  
   
  
https://securityaffairs.co/wordpress/113228/malware/teamtnt-botnet-docker-aws.html  

  
TeamTNT 봇넷이 이제 AWS 자격 증명과 함께 Docker API 로그인을 훔칠 수 있음을 발견  
  

TeamTNT 봇넷은 2020 년 4 월부터 활성화 된 암호화 채굴 악성 코드 작업으로 Docker 설치를 목표  
  
  
AWS 서버에서 실행되는 Docker 및 Kubernetes 시스템을 감염 시키면 봇   은 AWS CLI가 암호화되지 않은 파일 에 자격 증명 및 구성 세부 정보를 저장하는 경로인  

~ / .aws / credentials* 및  ~ / .aws / config 를 검색

이 악성 코드는 XMRig 마이닝 도구를 배포하여 Monero 암호 화폐를 채굴
  
---
  
  
### 3. 다운로드 및 배포 할 수 있는 악성 소프트웨어 인프라가 쉽게 구성되어 있음
  
https://threatpost.com/malicious-software-infrastructure-easier-deploy/162913/    

   
corded Future는 악성 인프라에 대한 정기적 인 연말 관찰 결과를 발표하였음  
  
  
80 개 악성 코드 제품군에서 10,000 개 이상의 고유 한 명령 및 제어 (C2) 서버를 식별  
  
  
연구자들이 오픈 소스 도구가 사용하기 쉽고 깊은 기술 전문 지식 없이도 범죄자가 접근 할 수 있기 때문에 더 많이 채택 될 것으로 예상한다고 설명함  
  
    
지난 11 월 GitHub에서 유출 된 이후 로 사용이 증가했으며 APT41, Mustang Panda, Ocean Lotus 및 FIN7을 포함한 주목할만한 APT에서 크랙 또는 평가판을 주로 사용하고 있다고 설명하였음  
  

코발트 스트라이크는 또한 작년에 관측 된 가장 많은 C2 서버와 연결되었다고 보고서는 밝힘 