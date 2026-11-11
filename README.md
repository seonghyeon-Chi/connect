# 계정 연결 중계 페이지 (connect)

SmartThings(삼성) 로그인은 https 주소로만 돌아올 수 있어서, 이 페이지가 로그인 결과(code)를 받아
연결을 시작한 사내 화면으로 그대로 넘깁니다.

- 비밀 정보 없음 — code 는 서버의 비밀 키 없이는 쓸 수 없고, 이 페이지는 아무것도 저장하거나 외부로 보내지 않습니다.
- 사내망 주소(사설 IP · localhost · .local)로만 돌려보냅니다.
- 주소: https://seonghyeon-chi.github.io/connect/ (SmartThings 앱의 Redirect URI 에 등록)
