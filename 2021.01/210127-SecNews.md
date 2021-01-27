## 보안동향 2021년 01월 27일  
   
    
### 1. 잘못 구성된 클라우드 서버에 66,000명 데이터 노출  
       
  
https://www.infosecurity-magazine.com/news/misconfigured-cloud-server-exposes/?&web_view=true  
      

- 인기있는 온라인 게임 사이트가  Elasticsearch 서버를 잘못 구성한 후 수만 명의 사용자가 개인 정보를 노출   
  

- 연구팀은 간단한 검색을 통해 암호화가없고 암호 보호가없는 개방형 서버를 발견   
   

- 2,300 만 개의 기록을 포함하여 30GB 이상의 데이터가 개인 정보 보호 문제로 유출   
  

    - 보고서에서 연구원들은 사용자 이름, 이메일, 장치 세부 정보, IP 주소, 해시 된 암호, Facebook, Twitter 및 Google ID, 게임 내 거래 세부 정보, 금지 된 플레이어에 대한 베팅 및 세부 정보를 포함하여 66,000 개의 사용자 프로필을 발견    
   
   
- 암호는 10 라운드를 사용하는 Bcrypt 알고리즘을 사용하여 해시되었으며, 시간이 많이 걸리지 만 결정된 공격자가 크래킹하는 것은 불가능하지 않다고 WizCase는 주장

---
  
  
### 2. Google은 심각한 Golang Windows RCE 취약성을 수정
   
   
https://www.bleepingcomputer.com/news/security/google-fixes-severe-golang-windows-rce-vulnerability/?&web_view=true   
    
    
- 이번 달 Google 엔지니어는 Go 언어 (Golang)의 심각한 원격 코드 실행 (RCE) 취약성을 수정  
 
- RCE 취약점 인 CVE-2021-3115 `go get` 는 Windows PATH 조회의 기본 동작으로 인해 주로 명령을 실행하는 Go의 Windows 사용자에게 영향을 줌    
  
  
- CVE-2021-3115로 추적되는 취약점은 사용자가 저장소를 가져 오기 위해 "go get"명령을 실행할 때 컴파일 프로세스가 작동하는 방식에서 고안됨   
  

- 일반적으로 Windows 시스템에서 사용자 또는 프로그램에 의해 실행되는 OS 셸 명령은 셸이 먼저 현재 디렉터리 내에서 해당 명령과 관련된 바이너리 / 실행 파일을 검색 한 다음 시스템 PATH 변수에 지정된 디렉터리 목록을 검색함 
   

- 예를 들어,  `netstat` Windows 명령 프롬프트에 입력하면 Windows는 우선 순위를 받고 실행될 현재 디렉터리 (아래 스크린 샷 참조) 에서 *netstat.exe, netstat.bat* 또는 다른 *netstat. ** 실행 파일 을 먼저 찾음  
- **PowerShell이 아닌 Windows 명령 프롬프트에 *netstat* 를 입력  하면 시스템 유틸리티가 아닌 로컬에있는 *netstat.bat* 가 실행됨** 
  
- 현재 폴더에 *netstat* 가 없는  경우에만 Windows 쉘  이 Windows *% PATH %* 변수 에있는 *netstat* 시스템 유틸리티를 찾음  
  

- 이 동작과 관련된 보안 위험으로 인해 Unix 셸과 Windows PowerShell은 이전에이 기본 동작을 삭제 하고 명령을 실행할 때 신뢰할 수없는 현재 디렉터리보다 *% PATH %* 변수 위치의 우선 순위를 지정하기 시작  
      
  

  
---
  
  
### 3. WhatsApp을 통해 확산되는 새로운 웜 가능한 Android 맬웨어     
            
  
https://www.bleepingcomputer.com/news/security/tiktok-fixes-flaws-allowing-theft-of-private-user-information/  
  
   
- TikTok의 기술 회사 인 ByteDance는 공격자가 사용자의 개인 정보를 훔칠 수있는 비디오 공유 소셜 네트워킹 서비스의 보안 취약점을 해결  
   

- TikTok은  iOS 및 Android 앱이 작동하는 국가에 서버 를 보유하고 있으며  3 ~ 60 초의 짧은 형식의 루핑 모바일 동영상을 공유하는 데 사용  
   
   
- 틱톡의 '친구 찾기'에서 체크 포인트 연구원이 발견 한 보안 취약점으로 인해 공격자는 플랫폼의 개인 정보 보호를 우회하여 전화 번호 및 사용자 ID를 포함하되 이에 국한되지 않는 사용자의 개인 개인 정보에 액세스  
  

- 취약점을 통해 접근 할 수 있었던 프로필 세부 정보에는 전화 번호, 닉네임, 프로필 및 아바타 사진, 고유 한 사용자 ID는 물론 사용자가 팔로워인지 또는 사용자 프로필이 숨겨져 있는지와 같은 특정 프로필 설정이 포함  
    
