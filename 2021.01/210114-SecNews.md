## 보안동향 2021년 01월 14일  
   
    
### 1. Microsoft 이메일 공급망 공격에서 해킹 된 Mimecast 인증서
       
  
https://threatpost.com/mimecast-certificate-microsoft-supply-chain-attack/162965/?web_view=true  
    
  
마이크로 소프트 365 익스체인지 웹 서비스에 대해 회사의 일부 제품을 인증하는 데 사용되는 Mimecast에서 발급 한 인증서가 "정교한 위협 행위자에 의해 손상"되었다고 회사는 발표  
  

Mimecast는 고객이 Mimecast 서버에 연결을 설정하여 Microsoft 365 계정에 적용 할 수있는 이메일 보안 서비스를 제공
    - 문제의 인증서는 Mimecast의 동기화 및 복구 (사서함 폴더 구조, 일정 콘텐츠 및 Exchange On-Premises 또는 Microsoft 365 사서함의 연락처 백업), 연속성 모니터 (이메일 트래픽의 중단을 찾음)에 대한 연결을 확인하고 인증하는 데 사용
    - 내부 이메일 보호 (IEP) (내부적으로 생성 된 이메일에서 악성 링크, 첨부 파일 또는 민감한 콘텐츠 검사)
     
   
---
  
  
### 2. Microsoft, Defender Zero-Day 용 패치 및 기타 Windows 결함 82 개 발표  
   
   
https://thehackernews.com/2021/01/microsoft-issues-patches-for-defender.html?&web_view=true  
    
    
2021 년 화요일의 첫 번째 패치에서 Microsoft 는 적극적으로 악용 된 제로 데이 취약점을 포함하여 11 개 제품 및 서비스에 걸쳐 총 83 개의 결함을 해결하는 보안 업데이트 발표  
   
   
최신 보안 패치는 Microsoft Windows, Edge 브라우저, ChakraCore, Office 및 Microsoft Office Services, Web Apps, Visual Studio, Microsoft 맬웨어 방지 엔진, .NET Core, ASP .NET 및 Azure를 포함   
- 이 83 개의 버그 중 10 개는 Critical, 73 개는 심각도에서 Important로 표시 
  
   
---
  
  
### 3. 전 세계적으로 공격을 벌이는 Egregor 랜섬웨어
    

https://cyware.com/news/egregor-on-an-attacking-spree-around-the-world-4e99932e  
  
   
gregor 랜섬웨어는 2020 년 9 월 처음 등장한 이후 현재 150 명 이상의 피해자를 위협함  
  

Egregor 랜섬웨어는 여러 메커니즘을 사용하여 비즈니스 네트워크 및 비즈니스 네트워크 또는 장치와 액세스를 공유하는 직원의 개인 계정 손상과 같은 비즈니스 네트워크를 대상  
    
  
이 랜섬웨어가 가장 많이 공격하는 분야는 기업, 제조, 교육, 운송 및 소매이며 영향을받는 지역은 남미 및 북미 및 서유럽   
  
  
---
  
  
### 4. 구글, 윈도우, 안드로이드 사용자를 대상으로 한 해킹 캠페인 공개  
    

https://www.bleepingcomputer.com/news/security/google-discloses-hacking-campaign-targeting-windows-android-users/  
  

Google의 제로데이 버그 사냥 팀인 Project Zero는 "매우 정교한 행위자"가 조직하고 제로 데이 및 n-day 익스플로잇으로 Windows 및 Android 사용자를 대상으로하는 해킹 캠페인을 공개  
   

Project Zero 팀은 Google 위협 분석 그룹 (TAG)과 협력하여 2020 년 초에 두 개의 익스플로잇 서버를 사용한 워터 링 홀 공격 을 발견    
  - 별도의 익스플로잇 체인을 사용하여 잠재적인 표적을 손상 시킴  
  

Project Zero 연구원은 다음과 같은 두 개의 익스플로잇 서버에서 정보를 수집 할 수 있었음  
   
    
- Renderer는 Chrome의 4 가지 버그를 악용
    - 두 개의 샌드 박스 이스케이프 익스플로잇이 Windows의 세 가지 제로데이 취약점을 악용