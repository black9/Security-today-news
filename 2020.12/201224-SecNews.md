## 보안동향 2020년 12월 22일  

  
### 1. Cellebrite는 Signal의 매우 안전한 메시징 앱에서 메시지를 해독 할 수 있다고 주장  
    

https://securityaffairs.co/wordpress/112571/hacking/cellebrites-claims-signal-decrypt.html  
  
  
 이스라엘 보안 회사인 Cellebrite는 Signal의 매우 안전한 메시징 앱에서 메시지를 해독 할 수 있다고 주장
- Signal은 SqlScipher를 사용하여 데이터베이스를 암호화 한 상태로 유지하므로 이를 읽으려면 키가 필요
- 키를 얻으려면 공유 환경 설정 파일에서 값을 읽고 '키 스토어'라는 Android 기능에 의해 저장되는 'AndroidSecretKey'라는 키를 사용하여 암호를 해독해야 함
- 이를 위해 Signal의 오픈 소스 코드를 사용하고 데이터베이스에 대한 호출을 찾음
- 이를 찾은 후 우리는 해독 된 키와 페이지 크기 및 kdf 반복에 대해 값 4096 및 1을 사용하여 데이터베이스에서 SqlCipher를 실행

  
---


### 2. Firefox 85는 추적 방지 보호 기능으로 네트워크 파티션 기능 시작  
  
  
https://www.zdnet.com/article/firefox-to-ship-network-partitioning-as-a-new-anti-tracking-defense/  
  
  
이 기능은 현재 World Wide Web Consortium의 Privacy Community Group에서 개발중인 새로운 표준인 " Client-Side Storage Partitioning "을 기반  
  
네트워크 파티셔닝은 매우 기술적이지만 다소 단순화하기 위해 브라우저에는 쿠키뿐만 아니라 웹 사이트의 데이터를 저장할 수있는 여러 가지 방법이 있음  
  
  
---
  
  
### 3. 랜섬웨어 공격은 더욱 위험하고 파괴적일 수 있음
   
  
https://www.zdnet.com/article/ransomware-why-these-attacks-could-get-even-more-dangerous-and-disruptive/?&web_view=true 
   
    
2020 년 내내 금전 요구가 증가했으며, 랜섬웨어 조직은 이제 정기적으로 피해자에게 수백만 달러의 비트 코인을 요구


Andrew Rose는 "다음으로 보게 될 타겟은 아마도 클라우드에 더 중점을 둘 것이라고 함
  모든 사람이 클라우드로 이동하고 있기 때문에 COVID-19는 많은 조직의 클라우드 배포를 가속화했기 때문에 대부분의 조직은 클라우드에 데이터를 저장했습니다."라고 말했기 때문
  
  
