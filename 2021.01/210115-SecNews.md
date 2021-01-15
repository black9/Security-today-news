## 보안동향 2021년 01월 15일  
   
    
### 1.악성 Android RAT가 다크 웹에서 발견  
       
  
https://securityaffairs.co/wordpress/113369/malware/rogue-android-rat-darkweb.html  
    
  
전문가들은 감염된 기기를 장악하고 사용자 데이터를 훔칠 수있는 Rogue 라고하는 Android 원격 액세스 트로이 목마를 발견  
  
  
Rogue 는 Triangulum 및 HeXaGoN Dev로 알려진 다크 넷 위협 행위자의 활동을 조사하는 동안 Check Point의 연구원이 발견 한 새로운 모바일 RAT  
  
  
"Rogue는 MRAT 제품군 (Mobile Remote Access Trojan)의 일부   
- 맬웨어는 호스트 장치를 제어하고 사진, 위치, 연락처 및 메시지와 같은 모든 종류의 데이터를 유출하여 장치의 파일을 수정하고 추가 악성 페이로드를 다운로드 할 수 있음  
     
   
---
  
  
### 2. SAP, 심각한 코드 삽입으로 인한 DoS 취약점 패치  
    
   
https://www.securityweek.com/sap-patches-serious-code-injection-dos-vulnerabilities?&web_view=true   
    
    

독일의 소프트웨어 제조업체 인 SAP는 다양한 심각한 보안 취약성에 대한 결함과 수정 사항을 문서화하기 위해 10 개의 권고를 발표  
    
     
SAP는 또한 이번 달 패치 데이에 이전에 발표 된 보안 노트에 대해 총 17 개의 다른 업데이트를 게시 했습니다. 이들 중 5 개는 Hot News의 가장 높은 심각도 등급을 가짐  

- CVE-2021-21465
- CVE-2021-21466

  
   
---
  
  
### 3. 특정 파일의 아이콘을 볼 때 Windows 10 버그로 인해 하드 드라이브 손상  
     
  
https://www.bleepingcomputer.com/news/security/windows-10-bug-corrupts-your-hard-drive-on-seeing-this-files-icon/?&web_view=true    
  

Microsoft Windows 10의 패치되지 않은 제로 데이는 공격자가 한 줄 명령으로 NTFS로 포맷 된 하드 드라이브를 손상시킬 수 있음  

한 줄짜리 파일은 Windows 바로 가기 파일, ZIP 아카이브, 배치 파일 또는 다양한 기타 벡터 안에 숨겨져 파일 시스템 색인을 즉시 손상시키는 하드 드라이브 오류를 트리거 할 수 있음  

결함은 Windows 10 빌드 1803, Windows 10 2018 년 4 월 업데이트부터 악용 될 수있게되었으며 최신 버전에서도 계속 작동  

 Windows 10 시스템에서 표준 및 권한이 낮은 사용자 계정에 의해 취약점이 트리거 될 수 있다는 것   

드라이브를 손상시키는 예제 명령어
```
cd c:/:$i30:bitmap
```
  
