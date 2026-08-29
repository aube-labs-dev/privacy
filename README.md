# aube-labs Privacy Policies

aube-labs 앱들의 개인정보 처리방침을 호스팅하는 공용 저장소입니다.
Hosted privacy policies for aube-labs applications.

🔗 **Live:** https://aube-labs-dev.github.io/privacy/

## 구조 / Structure

```
/                  → 앱 목록 랜딩 페이지
/hifive/           → HiFive 개인정보 처리방침 (KR/EN)
```

## 새 앱 추가 방법 / Adding a new app

1. `<app-name>/index.html` 로 처리방침 HTML 추가
2. 루트 `index.html`의 앱 목록에 링크 추가
3. commit & push → GitHub Pages 자동 배포

App Store Connect의 Privacy Policy URL에는
`https://aube-labs-dev.github.io/privacy/<app-name>/` 를 등록합니다.
