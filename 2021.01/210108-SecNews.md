## 보안동향 2021년 01월 08일  

  
### 1. Grinchbots에서 Parasitic Bots-as-a-Service의 악성 봇 진화   
     
  
https://www.imperva.com/blog/the-evolution-of-bad-bots-from-grinchbots-to-parasitic-bots-as-a-service/?web_view=true  


스캘핑 봇의 사용은 한때 스포츠 이벤트나 콘서트 티켓의 영역이였음  
  

그러나 최근에는 전자 상거래 및 온라인 소매에서 점점 더 널리 사용되고 있으며, 최근 출시 된 게임 콘솔은 휴가 기간 동안 Grinchbots에 의해 스캘핑됨  
  

악성 봇은 인터넷 트래픽의 1/4로 모든 트래픽의 존재의 24.1 % 이며 이 문제는 중요하고 최근 몇 년 동안 성장함  
  

프리미엄으로 재판매하기 위해 운동화, 티켓, 게임 콘솔 또는 수요가 많거나 한정판 품목을 구매하기 위해 이러한 봇을 구매하고 실행하는 봇들로 인한 불량 봇 사용 사례의 수가 증가 이유   
  

많은 생계 수단이 봇에 투자되고 있음  
     

---


### 2. Git 리포지토리 잘못된 구성 후 Nissan 소스 코드가 온라인으로 유출  
   
  
https://www.zdnet.com/article/nissan-source-code-leaked-online-after-git-repo-misconfiguration/?&web_view=true   
  
  
Nissan North America에서 개발하고 사용하는 모바일 앱 및 내부 도구의 소스 코드는 회사가 Git 서버 중 하나를 잘못 구성한 후 온라인으로 유출  
  
   
익명의 출처에서 유출 된 사실을 알고 월요일에 Nissan 데이터를 분석 한 Kottmann은 Git 저장소에 다음과 같은 소스 코드가 포함되어 있다고 말함  
  
   
- Nissan NA 모바일 앱  
- Nissan ASIST 진단 도구의 일부  
- 딜러 비즈니스 시스템 / 딜러 포털  
- Nissan 내부 코어 모바일 라이브러리  
- Nissan / Infiniti NCAR / ICAR 서비스  
- 고객 확보 및 유지 도구  
- 판매 / 시장 조사 도구 + 데이터  
- 다양한 마케팅 도구  
- 차량 물류 포털  
- 차량 연결 서비스 / Nissan Connect Things  
- 기타 다양한 백엔드 및 내부 도구  
  
---
  
  
### 3. Linux 악성 코드 작성자는 제로 탐지를 위해 Ezuri Golang 크립터를 사용
  
https://www.bleepingcomputer.com/news/security/linux-malware-authors-use-ezuri-golang-crypter-for-zero-detection/   

   
여러 악성 코드 작성자가 "Ezuri"크립터 및 메모리 로더를 사용하여 바이러스 백신 제품에서 코드를 탐지 할 수 없도록 함  
  

Golang으로 작성된 Ezuri의 소스 코드는 누구나 사용할 수 있도록 GitHub에서 제공    
   

Ezuri는 메모리 내 악성코드 페이로드를 해독  
  

AT & T Alien Labs에서 발표 한 보고서에 따르면 여러 위협 행위자가 Ezuri 크립 터를 사용하여 맬웨어를 압축하고 바이러스 백신 탐지를 회피하고 있다고 보고하였음


VirusTotal의 0에 가까운 탐지율을 보이고 있음   
  

감염된 시스템에 네트워크 스캐너를 설치하고 메모리에서 AWS 자격 증명을 추출하는 "Black-T"와 같은 TeamTnT 악성 코드의 최신 변종도 Ezuri와 결합 된 것으로 밝혀짐  
  