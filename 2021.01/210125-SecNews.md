## 보안동향 2021년 01월 25일  
   
    
### 1. 7 천 7 백만 Nitro PDF 사용자 레코드의 전체 데이터베이스 유출
       
  
https://www.bleepingcomputer.com/news/security/hacker-leaks-full-database-of-77-million-nitro-pdf-user-records/?&web_view=true  
    
- 7 천 7 백만 개 이상의 Nitro PDF 서비스 사용자 기록의 이메일 주소, 이름 및 비밀번호가 포함 된 도난당한 데이터베이스가 유출  
   

- 14GB 유출 된 데이터베이스에는 사용자의 이메일 주소, 전체 이름, bcrypt 해시 된 암호, 직함, 회사 이름, IP 주소 및 기타 시스템 관련 정보가 포함 된 77,159,696 개의 레코드가 포함되어 있음  
  

- Nitro는 PDF 및 디지털 문서를 만들고, 편집하고, 서명하는 데 도움이되는 응용 프로그램으로 Nitro Software에서 10,000 명 이상의 비즈니스 고객과 약 180 만 명의 라이선스 사용자가 있다고 주장하는 앱  
    - Nitro는 또한 고객이 문서 생성 프로세스와 관련된 동료 또는 기타 조직과 문서를 공유하는 데 사용할 수있는 클라우드 서비스를 제공  
  
      
---
  
  
### 2. NVIDIA 게이머는 쉴드 TV 버그로 인한 DoS, 데이터 손실
   
   
https://threatpost.com/nvidia-gamers-dos-data-loss-shield-tv-bugs/163200/?web_view=true  
    
    
- NVIDIA는 서비스 거부, 권한 상승 및 데이터 손실을 허용 할 수있는 NVIDIA Shield TV의 세 가지 보안 취약점을 새로 공개  
  
- Shield TV로 알려진 사물 인터넷 (IoT) 장치의 경우 하드웨어 기반 디코더 인 가젯의 NVDEC 구성 요소에 심각도가 높은 버그 (CVE‑2021‑1068)가 하나가 있음  
    

    - 이는 공격자가 버퍼의 의도 된 경계를 벗어난 메모리 위치에서 읽거나 쓸 수 있기 때문에 발생하며, 이로 인해 서비스 거부 또는 권한 상승이 발생   

   
    - 다른 두 가지 버그는 보통 심각도이며 CVE‑2021‑1069로 추적 된 결함은 NVHost 기능에 존재하며 널 포인터 참조로 인해 비정상적인 재부팅을  유발하여 데이터 손실을 유발할 수 있음  
  

    - 또 하나의 CVE‑2021‑1067은 RPMB 명령 상태 구현에 존재하며, 공격자가 쓰기 보호 구성 블록에 쓸 수 있으며, 이로 인해 서비스 거부 또는 권한 상승이 발생할 수 있음  
     

---
  
  
### 3. VLC Media Player 3.0.12는 여러 원격 코드 실행 결함을 수정  
           

https://www.bleepingcomputer.com/news/software/vlc-media-player-3012-fixes-multiple-remote-code-execution-flaws/?&web_view=true

   
   
- VideoLan은 지난주 Windows, Mac 및 Linux 용 VLC Media Player 3.0.12를 수많은 개선 사항, 기능 및 보안 수정 사항과 함께 출시  
  
    
- 버퍼 오버 플로우 또는 유효하지 않은 역 참조 취약점은 VLC 충돌 또는 대상 사용자의 권한으로 임의 코드 실행을 유발할 수 있음  
- VideoLan의 보안 게시판 에 따르면  원격 사용자는 특수 제작 된 미디어 파일을 만들고 사용자를 속여 VLC로 열도록이 취약점을 악용 할 수 있었음  
  
- VideoLan은이 취약점이 VLC Media Player를 중단시킬 가능성이 있다고 말하지만 공격자가이를 사용하여 정보를 유출하거나 장치에서 원격으로 명령을 실행할 수 있다고 경고  
- 성공하면 악의적 인 제 3자가 VLC 충돌 또는 대상 사용자의 권한으로 임의 코드 실행을 트리거 할 수 있음  
   

- VideoLan은 이러한 취약점을 악용하는 익스플로잇을 실제로 보지 못했다고 말함  
- 이 취약점의 심각성과 VLC 3.0.12의 개선 사항으로 인해 모든 사용자는 3.0.12 버전을 다운로드하여 설치 하는 것을 권장  
  

---
  
  
### 4. 해커 실수로 Google 검색을 통해 도난당한 비밀번호 노출
           

https://www.bleepingcomputer.com/news/security/hacker-blunder-leaves-stolen-passwords-exposed-via-google-search/  

   
- 대규모 피싱 캠페인으로 전 세계 수천 개의 조직을 공격 한 해커들은 자신의 전리품을 보호하는 것을 잊고 공개 검색을 위해 도난당한 비밀번호를 Google에 허용하는 것을 잊었었음  
  
   
- 피싱 캠페인은 반년 이상 실행되었으며 피싱 페이지를 호스팅하는 수십 개의 도메인을 사용함

     
- 이메일 보호 필터를 우회하는 데 성공했으며 회사 Office 365 계정에 대해 최소 1,000 개의 로그인 자격 증명을 수집  
  
- 오늘 발표 된 보고서에서 그들은 공격자가 작업을 위해 특별히 등록한 도메인으로 정보를 유출했다고 설명  
    - 구글 색인을 생성한 공개적으로 볼 수있는 파일에 데이터를 넣는 것이 문제   
   

- 결과적으로 Google은 아래 스크린 샷과 같이 훔친 이메일 주소 또는 비밀번호에 대한 검색 결과를 표시 할 수 있음  