## 보안동향 2021년 01월 14일  
   
    
### 1. Microsoft, Windows Zerologon 결함 'Enforcement Mode'구현
       
  
https://threatpost.com/microsoft-implements-windows-zerologon-flaw-enforcement-mode/163104/?web_view=true  
    
  
- 2 월 9 일부터 Microsoft는 CVE-2020-1472를 해결하기 위해 기본적으로 도메인 컨트롤러 "Enforcement Mode"를 활성화  
  

- Microsoft는 중요한 Zerologon 결함을 해결하기 위해 아직 시스템을 업데이트하지 않은 회사에 대해 문제를 해결하고 있음  
    - 이 기술 대기업은 결함을 악용 할 수있는 장치에서 취약한 연결을 기본적으로 차단할 예정  
  

- Microsoft Active Directory 도메인 컨트롤러는 Zerologon 취약점의 핵심    
    - 도메인 컨트롤러는 인증 요청에 응답하고 컴퓨터 네트워크에서 사용자를 확인  
    - 결함 악용 하면 도메인 컨트롤러에 대한 네트워크 액세스 권한이있는 인증되지 않은 공격자가 모든 Active Directory ID 서비스를 완전히 손상시킬 수 있음  
      
      
---
  
  
### 2. TA551, 이제 스푸핑 된 이메일을 통해 IcedID Stealer 확산
   
   
https://cyware.com/news/ta551-now-spreading-icedid-stealer-via-spoofed-emails-c090b741  
    
    
TA551 (일명 Shathak)은 영어를 사용하는 피해자를 적극적으로 대상으로하는 이메일 기반 악성 코드 배포 캠페인  
- 2020 년 초부터 활성화 된 TA551은 Ursnif 및 Valak과 같은 여러 악성 코드 군을 배포하는 것으로 알려짐  
  
  
스푸핑 된 이메일을 미끼로 사용했으며 이러한 이메일은 이전에 감염된 호스트의 이메일 클라이언트에서 검색    
- 이메일 메시지에는 첨부 된 ZIP 아카이브와 첨부 파일을 여는 데 필요한 비밀번호를 사용자에게 경고하는 메시지가 포함되어 있으며 ZIP 아카이브에는 매크로가있는 Microsoft Word 문서가 포함되어 있음  
- 피해자가 노출 된 Windows 컴퓨터에서 매크로를 활성화하면 피해자의 호스트는 IcedID 악성 코드 용 설치 프로그램 DLL을 다운로드  
- 2020 년 10 월 27 일까지이 캠페인은 영어를 사용하는 피해자만을 대상  
    - 얼마 후, 캠페인은 일본어를 사용하는 피해자를 포함한 다른 대상을 표적으로하기 시작  
  
   
---
  
  
### 3. Linux Mint에서 화면 보호기 우회 발견   
     

https://securityaffairs.co/wordpress/113518/hacking/screensaver-bypass-linux-mint.html  
  
   
Linux Mint 배포판의 개발 팀은 사용자가 OS 화면 보호기를 우회 할 수 있는 보안 결함을 수정    
  
   
프로세스는 간단하며 화면 보호기를 충돌시켜 화면 보호기 잠금을 우회하고 가상 키보드를 통해 데스크톱을 잠금 해제 할 수 있음   
잠긴 시스템에서 바이 패스를 재현하려면 가상 키보드를 클릭 한 다음 가상 키보드에 동시에 입력하는 동안 실제 키보드에 가능한 한 많은 키를 입력   
  
   
Linux Mint의 수석 개발자 인 Clement Lefebvre는 버그 가 Linux Mint에서 사용 하는 Cinnamon 데스크톱 환경의 일부인 온 스크린 키보드 (OSK) 구성 요소 인 *libcaribou* 에 있음을 확인  
  

모든 버전의 Cinnamon에서 화면 키보드 (메뉴에서 실행 됨)는 Cinnamon 프로세스 내에서 실행되며 libcaribou를 사용합니다. ē를 누르면 계피가 충돌  
  

Cinnamon 4.2 이상 버전에서는 화면 보호기에 libcaribou OSK가 있습니다. 거기에서 ē를 누르면 화면 보호기가 충돌  


  
---
