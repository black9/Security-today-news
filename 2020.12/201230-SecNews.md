## 보안동향 2020년 12월 30일  

  
### 1. 해커는 Facebook 광고를 사용하여 615,000 개의 로그인 자격 증명을 피싱 
    

https://www.hackread.com/hackers-phish-login-credentials-with-facebook-ads/?web_view=true    
  
  
연구원들은 Facebook 광고를 사용하여 사용자를 실제 피싱 페이지가있는 Github로 리디렉션하는 피싱 캠페인을 발견  
  
대상 사용자는 이집트, 필리핀, 파키스탄, 네팔을 포함한 여러 국가의 대상이며 그중 615,000 명 이상이 영향을 받았음  
  
피싱 캠페인은 사용자의 의심을 피하기 위해 합법적 인 회사를 사칭하는 것을 목표로하는 페이지에서 게시 된 Facebook 광고에 의해 실행됨  
  
  
---


### 2. Google 문서 버그로 인해 해커가 개인 문서를 볼 수 있었음
   
  
https://thehackernews.com/2020/12/a-google-docs-bug-could-have-allowed.html?&web_view=true  
  
  
Google은 서비스 전반에 통합 된 피드백 도구에 버그를 패치했습니다.이 버그는 공격자가 악의적 인 웹 사이트에 단순히 삽입하여 민감한 Google 문서 문서의 스크린 샷을 훔칠 수 있음  
  
- Google 문서 창의 스크린 샷이 포함될 때마다 이미지를 렌더링하려면 모든 픽셀의 RGB 값을 상위 도메인 (www.google.com)으로 전송해야 함  
  
- 그러면 해당 RGB 값이 피드백 도메인으로 리디렉션됩니다. 궁극적으로 이미지를 구성하고 Base64 인코딩 형식으로 다시 보냄  
  
- Sreeram 은 이러한 메시지 가 "feedback.googleusercontent.com"으로 전달 되는 방식에서 버그를 식별 하여 공격자가 프레임을 임의의 외부 웹 사이트로 수정하고 Google 문서 스크린 샷을 훔치고 도용 할 수 있었음
  

---
  
  
### 3. 현재 시장의 인기 메시지 앱 및 보안
   
  
https://www.bleepingcomputer.com/news/security/multi-platform-card-skimmer-found-on-shopify-bigcommerce-stores/  
   
    
인터넷 쇼핑몰 플랫폼 대상으로 하는 이 새로운 유형의 웹 스키밍 멀웨어는 악성 체크 아웃 페이지를 삽입하여 여러 온라인 상점 관리 시스템을 사용하는 상점의 체크 아웃 프로세스를 장악 할 수 있음   
  
  
고객이 실제 결제 양식에 도착하기 전에 위조 결제 페이지를 표시하고 키로거를 사용하여 결제 및 개인 정보를 가로채는 방식  
  
  
---


### 4. Google에서 홍보하는 쇼핑 광고 10 개 중 1 개는 잠재적으로 피싱 사이트로 이어짐  
   
  
https://cyware.com/news/popular-messaging-apps-and-security-that-matters-bef7621b  
  
  
보안되지 않은 애플리케이션은 민감한 정보의 유출 및 악용과 같은 재앙적인 결과를 초래할 수 있음  
  
최근 CyberNews 연구원들은 13 개의 메시징 앱을 분석하여 보안 여부를 확인  
  
최근 연구에 따르면 앱의 86 % (13 개 중 11 개)가 기본적으로 안전한 것으로 밝혀짐  
  
그러나 응용 프로그램에서 몇 가지 다른 보안 문제가 확인됨  

- 보안 메시징 응용 프로그램 중 4 개 (Signal, Messenger, WhatsApp 및 Session)가 종단 간 암호화를 위해 업계에서 신뢰하는 신호 프로토콜을 사용하는 것으로 관찰됨   
- 
- 두 개의 애플리케이션 (Briar 및 Qtox)만이 전송 메커니즘에 P2P를 사용 
   
- Telegram 및 Facebook Messenger에는 기본적으로 '개인 콘텐츠'보안 기능이 활성화되어 있지 않음  
  
- iMessage는 GSM (2G / 3G에 사용)에서 보낸 메시지를 암호화하지 않음  
  
- 최대 수의 애플리케이션이 암호화 및 키 해시를위한 암호화 알고리즘으로 AES 및 RSA를 사용하는 것으로 확인
  
