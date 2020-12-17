## 보안동향 2020년 12월 09일  

  
### 1. Microsoft Teams의 웜 가능한 크로스 플랫폼 결함에 대한 기술적 세부 사항을 공개  
  
  
https://securityaffairs.co/wordpress/112062/hacking/microsoft-teams-wormable-flaw.html?utm_source=rss&utm_medium=rss&utm_campaign=microsoft-teams-wormable-flaw   
  
  
보안 연구원 Oskars Vegeris는 비즈니스 커뮤니케이션 플랫폼 Microsoft Teams의 웜 가능한 크로스 플랫폼 취약점에 대한 기술적 세부 사항을 발표  
  
이 결함은 'teams.microsoft.com'도메인에 영향을 미치는 XSS (교차 사이트 스크립팅) 문제이며 공격자가 MS Teams 데스크톱 응용 프로그램에서 원격 코드를 실행하기 위해 악용 할 수 있음  
 

영향을 받는 제품
- MS Teams (teams.microsoft.com) – XSS(Cross-Site-Scripting)
- MS Teams macOS v 1.3.00.23764 (2020년 8월 31일 버전)
- MS Teams Windows v 1.3.00.21759 (2020년 8월 31일 버전)
- MS Teams Linux v 1.3.00.16851 (2020 년 8월 31일 버전)
  
---
  
  
### 2. 카자흐스탄 정부는 수도에서 HTTPS 트래픽을 가로 채고 있음  
  
  
https://www.zdnet.com/article/kazakhstan-government-is-intercepting-https-traffic-in-its-capital/  
  
  
카자흐스탄 정부는 "사이버 보안 훈련"을 가장하여 수도 누르 술탄 (이전 아스타나)에 거주하는 시민들이 외국 인터넷 서비스에 액세스하려는 경우 장치에 디지털 인증서를 설치하도록 강요하고 있음  
  
  
---
  
  
### 3. D-Link VPN 라우터는 원격 명령 주입 버그에 대한 패치를 얻음  
  
  
https://www.bleepingcomputer.com/news/security/ransomware-gangs-automate-payload-delivery-with-systembc-malware/
  
  
D-Link 펌웨어의 취약성은 공격자가 장치를 완전히 제어 할 수 있도록 함
  
이 버그는 펌웨어 버전 3.17 이하를 실행하는 라우터 모델 DSR-150, DSR-250 / N, DSR-500 및 DSR-1000AC에 영향을 줌
  
  
---
  
  
### 4. 패치되지 않은 MiTM 취약점의 영향을받는 Kubernetes 모든 버전    
  
  
https://securityaffairs.co/wordpress/112370/security/hpe-flaw-systems-insight-manager.html  
  
  
Kubernetes는 호스트 클러스터에서 컨테이너화 된 워크로드, 서비스, 애플리케이션의 배포, 확장, 관리를 자동화하도록 설계된 오픈 소스 시스템  
  
중간자 (MiTM) 공격에서 다중 테넌트 Kubernetes 클러스터의 다른 포드에서 트래픽을 가로 챌 수있는 취약성을 악용
  
- CVE-2020-8554
