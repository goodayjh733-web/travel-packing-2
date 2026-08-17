싱가포르·말레이시아 여행 준비물 PWA

파일 구성
- index.html : 앱 본체
- manifest.webmanifest : 앱 설치 정보
- sw.js : 오프라인 실행용 서비스 워커
- icon-192.png / icon-512.png : 앱 아이콘

중요
PWA의 '홈 화면 설치' 및 서비스 워커 기능은 일반적으로 HTTPS 웹주소에서 열어야 정상 작동합니다.
GitHub Pages, Netlify, Cloudflare Pages 같은 정적 웹 호스팅에 이 폴더의 파일을 그대로 올리면 됩니다.

휴대폰 설치
Android Chrome: 웹주소 접속 → 설치 배너 또는 메뉴 → '앱 설치/홈 화면에 추가'
iPhone Safari: 웹주소 접속 → 공유 버튼 → '홈 화면에 추가'
