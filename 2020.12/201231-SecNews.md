## 보안동향 2020년 12월 31일  

  
### 1. Windows, Linux 서버를 Monero 코인 마이너로 바꾸는 새로운 웜
    

https://www.bleepingcomputer.com/news/security/new-worm-turns-windows-linux-servers-into-monero-miners/    
  
  
새로 확산되는 Golang 기반 악성 코드는 12 월 초부터 Windows 및 Linux 서버에서 XMRig 암호 화폐 채굴기를 제거 하고 있음  
  
- 취약한 암호 로 공개 서비스  
    - ex) MySQL, Tomcat, Jenkins 및 WebLogic)를 무차별 대입하여 다른 시스템으로 확산 할 수있는 웜 기능도 있음  
  
C2 서버는 bash 또는 PowerShell dropper 스크립트 (대상 플랫폼에 따라 다름), Golang 기반 바이너리 웜 및 감염된 장치에서 추적 할 수없는 Monero 암호 화폐를 은밀하게 채굴하기 위해 배포 된 XMRig 마이너를 호스팅하는 데 사용됨  
  
  
이 웜은 암호 스프레이 및 하드 코딩 된 자격 증명 목록을 사용하여 MySql, Tomcat 및 Jenkins 서비스를 검색하고 무차별 대입하여 다른 컴퓨터로 확산됨

이전 버전의 웜도 **CVE-2020-14882** Oracle WebLogic 원격 코드 실행 취약점을 악용하려는 것으로 나타남
  
  
---


### 2. Wasabi 클라우드 스토리지 서비스가 악성 코드 호스팅으로 인해 오프라인 상태가 됨
   
  
https://www.bleepingcomputer.com/news/security/wasabi-cloud-storage-service-knocked-offline-for-hosting-malware/ 
  
  
클라우드 스토리지 제공 업체 Wasabi는 스토리지 엔드 포인트에 사용 된 도메인이 악성 코드 호스팅으로 인해 일시 중단됨

Wasabi는 Amazon S3와 같은 솔루션과 경쟁하는 클라우드 스토리지 제공 업체로, 송신 또는 API 수수료를 부과하지 않고 훨씬 저렴한 서비스를 제공하고 있음

Wasabi는 DNS 확인으로 인해 "성능 저하"가 발생한다는 중단 보고서의 문제를 인정함

- 상태 보고서에 따르면 도메인 등록 기관은 wasabisys.com 도메인에 호스팅 된 악성 콘텐츠에 대해 Wasabi에 연락을 시도함  
- 악용 보고서를 보낼 때 등록 기관은 이를 잘못된 이메일로 전달했으며 Wasabi는 알림을 받지 못했음  
    
이 사고로 인해 등록 기관은 도메인을 일시 중단하여 거의 모든 스토리지 버킷이 wasabisys.com 도메인을 사용하므로 스토리지 서비스를 오프라인으로 둠  

- 악용 보고서를 알게 된 후 Wasabi는 악성 콘텐츠를 호스팅하는 클라이언트를 중단하고 등록 기관에 도메인을 다시 활성화하도록 요청함  
    - 도메인 복원을 완료하는데 13 시간 걸림  

---
  
  
### 3. Microsoft는 6 개월 전에 제로 데이에 대한 수정을 발표했지만 작동하지 않음
   
  
https://hotforsecurity.bitdefender.com/blog/microsoft-issued-a-fix-for-zero-day-six-months-ago-but-it-didnt-work-24990.html?web_view=true  
   
    
마이크로 소프트는 2020 년 6 월 제로 데이 취약점을 수정했지만 작동하지 않음   
구글 프로젝트 제로 (Project Zero)의 보안 연구원들은 패치에도 불구하고 공격자들이 여전히 제로 데이를 사용할 수 있음을 보여줌   
Windows 8.1 및 10 용 2020 년 6 월 패치는 제로 데이 **CVE-2020-0986**   
  
- Windows 커널이 메모리의 개체를 제대로 처리하지 못하는 경우 권한 상승 취약점이 존재    
    - 이 취약점 악용에 성공한 공격자는 커널 모드에서 임의의 코드를 실행할 수 있음    
    - 그런 다음 공격자는 프로그램을 설치할 수 있으며 데이터 보기, 변경 또는 삭제 또는 전체 사용자 권한으로 새 계정을 만들수도 있음   
  
- 결과적으로 이러한 중요한 문제에 대한 빠른 수정이 가능한 최선의 결과이지만 보안 연구원은 수정이 작동하지 않는다는 것을 발견   
  

- 새로운 패치 수정 사항은 1 월 패치에서 사용할 수 있음  
  
  
---


### 4. 컴퓨터 프로그램의 취약점을 수정하는 데 걸리는 평균 시간을 조사함
   
   
https://www.hackers-review.tech/2020/12/experts-have-named-average-time-for.html?&web_view=true 
  
  
44% 정도의 개발자는 느린 소프트웨어 업데이트로 인해 3 개월 만에 정보 보안의 관점에서 발견된 제품의 취약점을 수정하는 것을 발견  
  
어떤 경우에는 6 개월 후에도 오류가 제거되지 않음   
- 전문가들에 따르면 이에 대한 주된 이유 중 하나는 코로나 전염병으로 인해 원격으로 작업해야하는 현지 IT 전문가의 업무량이 증가 때문이라고 반박  
  
- 19 %는 메시지를 받은 후 7일 이내에 수정 
- 10.1 %는 8-30 일 이내에 수정
- 27.4 % 31~90 일 이내에 수정
- 29.2 %를 수정하는 데는 91 ~ 180 일이 걸림
- 180 일 후에도 14.3 %의 오류가 수정되지 않음

이 연구는 지난 1 년 동안 일반적으로 알려진 취약점 데이터베이스 인 CVE (Common Vulnerabilities and Exposures)에 나타난 168 가지 유형의 취약점을 고려함  
  
  
전문가에 따르면 취약점을 수정하는 데 걸리는 시간에 대한 조건부 표준이 없다고 알림  
  