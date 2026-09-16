# siul-site

시울 공개 페이지. GitHub Pages 로 서빙.

- `index.html` — 소개 (준비 중)
- `privacy.html` — 개인정보처리방침
- `terms.html` — 이용약관

원문(마크다운)은 앱 리포 `docs/legal/` 에 있고, 여기 HTML 은 거기서 만든다.
- `app/` — 웹 미리보기 (호스팅 Supabase, 한국어 단독). 앱 리포에서 `flutter build web --release --base-href /siul-site/app/ --dart-define-from-file=env.prod.json` 후 `build/web` 을 복사
