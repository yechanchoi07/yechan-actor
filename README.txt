배우 최예찬 GitHub Pages 사이트

[최종 구조]
일반 방문자: GitHub 로그인 없이 공개 사이트 접속
관리자: /admin.html 에서 Supabase 이메일/비밀번호로 로그인
호스팅: GitHub Pages
데이터/사진/영상/프로필 파일: Supabase

[GitHub 저장소에 올릴 파일]
index.html
admin.html
.nojekyll

중요: 파일을 저장소의 최상위(root)에 올립니다. index.html이 바로 보이는 위치여야 합니다.

[GitHub Pages 설정]
1. GitHub에서 yechanchoi07/yechan-actor 저장소를 엽니다.
2. Settings → Pages 로 들어갑니다.
3. Build and deployment → Source를 "Deploy from a branch"로 설정합니다.
4. Branch는 "main", 폴더는 "/ (root)"로 선택합니다.
5. Save를 누릅니다.
6. 1~5분 정도 기다린 뒤 페이지 상단의 Visit site를 누릅니다.

공개 주소 예시:
https://yechanchoi07.github.io/yechan-actor/

[관리자 주소]
공개 주소 뒤에 admin.html을 붙입니다.
예: https://yechanchoi07.github.io/yechan-actor/admin.html

[사진 슬라이드]
- 사진이 2장 이상이면 좌우 버튼으로 이동합니다.
- 휴대폰에서는 사진 위를 좌우로 밀어도 이동합니다.
- 아래 점(dot)을 눌러 원하는 사진으로 바로 이동할 수 있습니다.
- 좌우 버튼은 사진이 1장이어도 표시되지 않습니다.

[QR 코드]
Chrome에서 최종 공개 주소를 연 뒤 주소창의 QR 코드 기능으로 생성합니다.
관리자 주소(/admin.html)가 아니라 공개 홈 주소를 사용해야 합니다.

[주의]
- Vercel 로그인은 필요 없습니다.
- Higgsfield 로그인은 필요 없습니다.
- 일반 방문자가 GitHub에 로그인할 필요도 없습니다.
- Supabase publishable key는 프론트 코드에 들어가도 되지만 secret/service_role key는 절대 넣지 않습니다.
