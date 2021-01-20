## 보안동향 2021년 01월 20일  
   
    
### 1. Indelible, 크기가 빠르게 증가하는 새로운 악성 푸시 알림 발견
       
  
https://in.news.yahoo.com/indelible-discovers-malfeasant-push-notification-120000781.html?&web_view=true  
  
    
- PushBug는 많은 보안 제어를 우회하고 일반적인 탐지 및 예방 조치에서 누락됨  
  

- 보안 회사 인 Indelible LLC는 회사 에서 운영되는 불법적 인 푸시 알림 캠페인에 대한 중요한 정보를 수집했다고 발표  
    - 100 개 이상의 도메인. "PushBug"캠페인은 복원력이 뛰어난 운영으로 수많은 도메인에 분산되어 있으며 탐지하기 어려운 브라우저 기반 활동을 설치  
   
  
- "무료"영화 웹 사이트를 포함하여 특정 웹 사이트를 검색하는 사용자는 웹 사이트에서 콘텐츠를 볼 수 있도록 "허용"알림 메시지가 표시되지만, 이는 시스템에서 일어나는 일이 아님  
  

- 사용자가 "허용"을 클릭하면 웹 사이트는 사용자의 브라우저에 서비스 워커를 설치하여 사용자 활동 추적과 관련된 악의적 도메인과 상호 작용하기 시작하고 악의적 인 운영자에게 원하는대로 사회 공학 팝업 알림 공격을 생성 할 수있는 기능을 제공  
  

  
      
---
  
  
### 2. AnyVan은 디지털 침입을 확인하고 노출 된 고객 이름, 이메일 및 해시 된 암호 유출  
   
   
https://www.theregister.com/2021/01/19/anyvan_confirms_digital_breakin_says/?&web_view=true  
    
    
- 사용자가 공급자 네트워크에서 배송, 운송 또는 제거 서비스를 구매할 수있는 유럽 온라인 마켓 플레이스 인 Anyvan은 고객의 개인 데이터 도난  
  

- The Register에서 확인한 이메일에 따르면이 회사는 지난 주 중순 고객에게 "보안 위반으로 인해 사용자 데이터베이스의 데이터에 무단 액세스하게 된"사실을 고객에게 알림  
   
  
- Anyvan은 "고객의 이름, 이메일 및 비밀번호의 암호화 해시에 액세스하여 '잠재적으로 조회'했지만 다른 개인 데이터는 무의식적으로 공유되지 않았음   
  
   
---
  
  
### 3. 새로운 FreakOut 봇넷은 패치되지 않은 소프트웨어를 실행하는 Linux 시스템을 대상
     

https://www.zdnet.com/article/new-freakout-botnet-targets-linux-systems-running-unpatched-software/?&web_view=true  
  
   
- 새로 확인 된 봇넷은 Linux 시스템에서 실행되는 패치되지 않은 애플리케이션을 목표로하고 있다고 Check Point 보안 연구원은 오늘 보고서에서 밝힘  
  
- 2020 년 11 월에 처음 발견 된  **FreakOut**  봇넷은 이번 달 새로운 일련의 공격에서 다시 나타남  

- 현재 목표에는 TerraMaster 데이터 저장 장치, Zend PHP 프레임 워크를 기반으로 구축 된 웹 애플리케이션, Liferay Portal 콘텐츠 관리 시스템을 실행하는 웹 사이트가 포함됨  
  

- Check Point는 FreakOut 운영자가 인터넷에서 이러한 애플리케이션을 대량 스캔 한 다음 기본 Linux 시스템을 제어하기 위해 세 가지 취약점을 악용하고 있다고 말함  
    

- 많은 시스템이 패치에서 여전히 뒤처 질 수 있기 때문에 FreakOut 악용 시도가 성공할 가능성이 높음  
  
- [CVE-2020-28188-TerraMaster](https://nvd.nist.gov/vuln/detail/CVE-2020-28188)  

    관리 패널의 RCE   

- [CVE-2021-3007](https://nvd.nist.gov/vuln/detail/CVE-2021-3007)  
  
    Zend 프레임 워크의 역 직렬화 버그   

- [CVE-2020-7961](https://nvd.nist.gov/vuln/detail/CVE-2020-7961)  
  
    Liferay 포털의 역 직렬화 버그  


  
---
