# galmanhae-docs

갈만해? 미니앱의 약관·정책 정적 페이지. GitHub Pages로 호스팅됩니다.

## 파일

- `index.html` — 문서 색인 (랜딩)
- `terms.html` — 서비스 이용약관
- `privacy.html` — 개인정보 처리방침

## GitHub Pages 활성화

1. GitHub에서 repo 생성 후 push (아래 명령 참고)
2. Settings → Pages → Source: **`main` branch / root** 선택 → Save
3. 1~2분 후 발급되는 URL:
   - `https://<github-username>.github.io/galmanhae-docs/index.html`
   - `https://<github-username>.github.io/galmanhae-docs/terms.html`
   - `https://<github-username>.github.io/galmanhae-docs/privacy.html`

## 토스 콘솔 등록

| 약관 제목 | 약관 URL | 약관 유형 | 조건 |
|---|---|---|---|
| 서비스 이용약관 | `.../terms.html` | 서비스 이용약관 | 필수 동의 |
| 개인정보 처리방침 | `.../privacy.html` | 개인정보 처리방침 | 필수 동의 |

## 갱신

내용 수정 후:
```bash
git add -A && git commit -m "update terms/privacy" && git push
```
→ 1~2분 후 GitHub Pages 자동 반영.
