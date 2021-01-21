## 보안동향 2021년 01월 21일  
   
    
### 1. 해커, 포럼에 무료로 190 만 Pixlr 사용자 기록 게시
       
  
https://www.bleepingcomputer.com/news/security/hacker-posts-19-million-pixlr-user-records-for-free-on-forum/  
    
- 한 해커가 표적 피싱 및 크리 덴셜 스터핑 공격을 수행하는 데 사용될 수있는 정보가 포함 된 190 만 Pixlr 사용자 기록을 유출함  
  

- Pixlr는 Photoshop과 같은 전문 데스크톱 사진 편집기에서 볼 수있는 것과 동일한 기능을 많이 갖춘 매우 인기있는 무료 온라인 사진 편집 응용 프로그램임  
  

- Pixlr는 기본 편집 도구를 무료로 제공하지만 사이트는 고급 도구, 스톡 사진 및 기타 기능이 포함 된 프리미엄 멤버십도 제공  
  

- ShinyHunters는 웹 사이트를 해킹하고 훔친 사용자 데이터베이스를 비공개 판매 또는 데이터 유출 브로커를 통해 판매하는 것으로 잘 알려진 위협 행위자  

  
      
---
  
  
### 2. Signal, Facebook, Google 채팅 앱의 버그로 인해 공격자가 사용자를 감시 할 수 있음 
   
   
https://www.bleepingcomputer.com/news/security/bugs-in-signal-facebook-google-chat-apps-let-attackers-spy-on-users/?&web_view=true    
    
    
- 여러 화상 회의 모바일 애플리케이션에서 발견 된 취약점으로 인해 공격자는 상대방이 전화를 받기 전에 허가없이 사용자 주변의 소리를 들을 수 있었음  
  

- 로직 버그는 Google Project Zero 보안 연구원 Natalie Silvanovich가 Signal, Google Duo, Facebook Messenger, JioChat 및 Mocha 메시징 앱에서 발견했으며 모두 수정됨
  

- 그러나 패치를 적용하기 전에 코드를 실행할 필요없이 대상 장치가 공격자의 장치로 오디오를 전송하도록 강제 할 수있었음  
  

- Silvanovich가 공개 한 것처럼  2019 년 9 월에 패치 된 Signal 버그 로 인해 사용자 상호 작용없이 발신자 장치에서 수신자에게 연결 메시지를 전송하여 음성 통화를 연결할 수 있었음  
    
   
   
---
  
  
### 3. PrusaSlicer 취약점
       

https://blog.talosintelligence.com/2021/01/vulnerability-spotlight-out-of-bounds.html?&web_view=true  
   
   
- Cisco Talos는 최근 Prusa Research의 PrusaSlicer에서 경계를 벗어난 쓰기 취약점 2 개를 발견  
  

- Prusa Slicer는 Slic3r에서 분리 된 오픈 소스 3D 프린터 슬라이싱 프로그램으로 다양한 3D 모델 파일 형식을 변환 할 수 있으며 해당 3D 프린터 판독 가능 Gcode를 출력 할 수 있음  
    

- 소프트웨어의 두 가지 기능은 특수 제작 된 OBJ 및 AMF 파일과 함께 악용되어 범위를 벗어난 쓰기 조건 또는 버퍼 오버플로를 유발 한 다음 피해자 컴퓨터에서 코드를 실행할 수 있음  
    
  
## 취약성 세부 정보  

- Prusa Research PrusaSlicer Obj.cpp load_obj () 범위를 벗어난 쓰기 취약성 (TALOS-2020-1219 / CVE-2020-28595)  
    

- Prusa Research PrusaSlicer 2.2.0 및 Master (커밋 4b040b856)의 Obj.cpp load_obj () 기능에 범위를 벗어난 쓰기 취약점이 존재  
- 특별히 제작 된 obj 파일은 코드 실행으로 이어질 수 있음  
  

- Prusa Research PrusaSlicer Objparser :: objparse () 스택 기반 버퍼 오버플로 취약성  (TALOS-2020-1220 / CVE-2020-28598)  
- Prusa Research PrusaSlicer 2.2.0 및 Master (커밋 4b040b856)의 Objparser :: objparse () 기능에 스택 기반 버퍼 오버플로 취약점이 존재  
- 특별히 제작 된 obj 파일은 코드 실행으로 이어질 수 있음  