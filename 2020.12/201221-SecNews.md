## 보안동향 2020년 12월 21일  

  
### 1. Gitpaste-12 웜 봇넷이 30 개 이상의 취약점 악용
  
  
https://www.bleepingcomputer.com/news/security/gitpaste-12-worm-botnet-returns-with-30-plus-vulnerability-exploits/  
  
   
GitHub를 통해 확산되고 있으며 Pastebin에서 악성 페이로드를 호스팅하는 Gitpaste-12 웜이 더 많은 익스플로잇으로 돌아옴   
  
Gitpaste-12  
- 리버스 쉘 및 암호화 채굴 기능과 함께 제공되었으며 12 개 이상의 알려진 취약점을 악용  
- 고급 웜과 봇넷이 30개가 넘는 취약점 악용  
  
  
---


### 2. jSQL Injection Lightweight Application 원격 서버에서 데이터베이스 정보를 찾는데 사용 
   
  
https://securityaffairs.co/wordpress/112376/apt/solarwinds-backdoor-kill-switch.html  
  
  
jSQL Injection은 서버에서 데이터베이스 정보를 찾는데 사용되는 경량 애플리케이션     
    
  
jSQL Injection은 공식 침투 테스트 배포판 인 Kali Linux의 일부이며 Pentest Box , Parrot Security OS , ArchStrike 및 BlackArch Linux 와 같은 다양한 배포판에 포함되어 있음    

- 34 가지 데이터베이스 Injection 공격
    - Access, Altibase, C-treeACE, CockroachDB, CUBRID, DB2, Derby, Exasol, Firebird, FrontBase, H2, Hana, HSQLDB, Informix, Ingres, InterSystems-IRIS, MaxDB, Mckoi, MemSQL, MimerSQL, MonetDB, MySQL, Neo4j, Netezza, NuoDB, Oracle, PostgreSQL, Presto, SQLite, SQL Server, Sybase, Teradata 및 Vertica    
- Multiple injection strategies: Normal, Error, Stacked, Blind and Time  
- Various injection processes: Default, Zip, Dios  
- Sandbox for SQL and tampering scripting  
- List to inject multiple targets  
- Read and write file using injection  
- Create and display Web shell and SQL shell  
- Bruteforce password hash  
- Search for admin pages  
- Hash, encode and decode text  
- Authenticate using Basic, Digest, NTLM and Kerberos  
- Proxy connection on HTTP, SOCKS4 and SOCKS5  
  
  
---
  
  
### 3. 모바일 장치 에뮬레이터를 사용하여 온라인 은행 계좌에서 수백만 달러를 훔쳐 달아남  

  
https://cyware.com/news/the-bronze-bit-attack-can-bypass-kerberos-protocol-7853a276      
    
  
공격자들은 모바일 멀웨어 봇넷을 사용하거나 피싱 로그를 스크랩하여 온라인 은행 계좌에 대한 로그인 자격 증명을 얻은 다음 이를 사용하여 대규모 사기 거래를 성사 시킴
   
사기꾼은 에뮬레이터를 사용하여 사기 거래를 감지하기 위해 은행에서 구현한 보안 조치를 우회하였음 

사기꾼은 계정에 액세스하고, 거래를 시작하고, SMS를 통해 전송 된 OTP 코드를 캡처하고, 불법 거래를 완료하는 프로세스를 자동화 함
   
   
---
