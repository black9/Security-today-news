## 보안동향 2020년 12월 22일  

  
### 1. Sunburst 악성 코드 DGA 크래킹 후 SolarWinds 피해자 공개
  
https://securityaffairs.co/wordpress/112494/malware/clop-ransomware-symrise.html  

 
SolarWinds 공급망 공격을 지속적으로 조사한 후 위협 행위자가 Sunburst / Solarigate 맬웨어를 배포 한 조직 목록을 공유  
  

SolarWinds Orion IT 관리 플랫폼의 손상된 업데이트 메커니즘을 통해 Sunburst 백도어에 감염된 피해자 목록을 작성하기 위해 연구원은 손상된 장치 각각에 대해 동적으로 생성 된 C2 하위 도메인의 일부를 디코딩함 

  
---


### 2. Dell Wyse ThinOS 결함으로 해커가 악용 할 수 있음
  
  
https://securityaffairs.co/wordpress/112520/hacking/dell-wyse-thinos-flaws.html  
  
  
CVE-2020-29492 및 CVE-2020-29491 로 추적되는 심각한 취약성  은 원격 공격자가 악의적 인 코드를 실행하고 임의 파일에 대한 액세스 권한을 얻을 수있는 여러 Dell Wyse 씬 클라이언트 모델에 영향을 줌  
  
- 컴퓨터 네트워킹에서 씬 클라이언트 는 서버 기반 컴퓨팅 환경과의 원격 연결을 설정하도록 최적화 된 단순한 저성능 컴퓨터  
- 서버는 소프트웨어 프로그램 시작, 계산 수행, 데이터 저장 등 대부분의 작업을 수행함  
  
  
---
  
  
### 3. VBA 제거 공격을 사용하는 해커 
   
  
https://www.securityweek.com/threat-actors-increasingly-using-vba-purging-attacks    
   
    
2020 년 2 월에 자세히 설명 된 VBA 제거 는 일반적으로 컴파일 된 코드 대신 Office 문서 내에서만 VBA 소스 코드를 사용하며 탐지 및 회피 보장  
   
악성 Office 문서에는 CFBF (Compound File Binary Format) 파일의 스트림 내에 VBA 코드가 저장되어 있으며, VBA 매크로 (MS-OVBA)에 대한 Microsoft의 사양은 VBA 데이터를 다양한 유형의 스트림을 포함하는 계층 구조에 저장  
  
VBA 제거를 사용하면 PerformanceCache 데이터가 대신 제거되고 MODULEOFFSET 값이 0으로 전환되고 SRP 스트림이 제거되어 응용 프로그램이 모듈 스트림에서 컴파일 된 코드를 찾지 못할 때 런타임 오류가 발생하지 않도록 해야함  
  
  
