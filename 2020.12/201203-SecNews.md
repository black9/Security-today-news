## 보안동향 2020년 12월 03일  

  
### 1. iPhone 제로 클릭 Wi-Fi 익스플로잇 해킹
  
  
https://arstechnica.com/gadgets/2020/12/iphone-zero-click-wi-fi-exploit-is-one-of-the-most-breathtaking-hacks-ever/
  
  
iPhone 취약점 중 하나인 iOS 커널의 메모리 손상 버그를 패치하여 공격자가 Wi-Fi를 통해 사용자 상호 작용이 전혀 필요없이 전체 장치에 원격으로 액세스 할 수 있도록 함  
  
   
---
  
  
### 2. SSH 횡방향 움직임을 갖는 Multi-Vector Miner+Tsunami Botnet
  
  
https://securityaffairs.co/wordpress/111761/malware/multi-vector-miner-tsunami-botnet.html  
      
  
**이 봇넷 버전의 새로운 기능**

- 모네로 XMR 채굴 외에 Tsunami 봇넷이 두 번째 페이로드로 추가됨
	- 전파를위한 Oracle WebLogic RCE 익스플로잇  
	- EDR 및 모니터링 도구, AliBaba의 Aliyun 및 Tencent의 qcloud 제거  
	- SSH 사용자, 키, 호스트 및 포트를 열거하는 SSH Lateral Movement에 대한 개선 된 기능 사용  
	- 드롭 위치가 다른 여러 셸 스크립트 및 Python 스크립트를 사용하고 하드 코딩 된 IP 주소 및 도메인을 사용하여 바이너리 호스팅 웹 서버에 연결  
	- 대량 스캔을 사용하여 SSH 및 Redis 서비스를 스캔하고 Redis-cli 및 SSH 무차별 대입 도구를 사용하여 서버를 감염시키는 데 사용되지 않는 코드를 포함   
    
	
---
  
  
### 3. Docker Hub 컨테이너 이미지의 절반 이상의 심각한 취약성 
  
  
https://www.zdnet.com/article/microsoft-removes-18-malicious-edge-extensions-for-injecting-ads-into-web-pages/   
  
  
공개적으로 사용 가능한 Docker Hub 컨테이너 이미지의 절반 이상에 심각한 취약성이 포함  
    
전체적으로 스캔 된 이미지의 51 %에 하나 이상의 심각한 취약점이 포함되어 있음  
이 중 가장 많은 수 44 %는 코인 채굴 자였으며 악성 npm 패키지 23 %, 해킹 도구 20 % 및 Windows 악성 코드 6 %가 뒤를 이음  
  
  
---
  
  
### 4. 5 년 동안 APT 공격에 사용 된 'Crutch'러시아 악성 코드 발견
  
  
https://thehackernews.com/2020/12/experts-uncover-crutch-russian-malware.html
   
    
ESET 연구자들이 코드 명 " Crutch "로 명명 한이 악성 코드는 러시아에 기반을 둔 고급 해커 그룹 인 Turla (일명 Venomous Bear 또는 Snake)가 정부, 대사관, 군사 기관에 대한 다양한 공격과 창을 통해 광범위한 공격을 수행 한 것으로 알려져 있음
  
민감한 문서 및 기타 파일을 Turla 운영자가 관리하는 Dropbox 계정으로 유출하도록 설계되었음