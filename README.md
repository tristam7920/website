# HAI Micro Lab (GitHub Pages Blog)

개인 블로그를 "AI 연구소" 컨셉으로 확장한 GitHub Pages 사이트입니다.

## 배포 (GitHub Pages)

1. 이 폴더를 GitHub 저장소로 올립니다.
2. GitHub 저장소에서 `Settings` → `Pages`로 이동합니다.
3. `Build and deployment`:
   - Source: `Deploy from a branch`
   - Branch: `main` / `root`
4. 저장하면 GitHub가 Jekyll로 자동 빌드 후 배포합니다.

## 로컬 실행 (선택)

Ruby가 설치되어 있다면:

```powershell
bundle install
bundle exec jekyll serve
```

브라우저에서 `http://127.0.0.1:4000` 접속.

