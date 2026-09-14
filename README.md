# GitHub Pages 홈페이지

## 파일 구성
- `index.html` : 홈페이지 내용
- `style.css` : 디자인
- `script.js` : 간단한 동작
- `README.md` : 사용 안내

## 가장 먼저 바꿀 부분
`index.html`을 메모장 또는 VS Code로 열고 다음 항목을 수정하세요.

1. `<title>홈페이지 제목</title>`
2. 상단의 `홈페이지 제목`
3. 메인 제목과 소개 문구
4. 각 카드의 제목/설명
5. `href="https://example.com"`을 실제 링크로 변경
6. 이메일 주소 변경

## GitHub에 올리기

터미널 또는 Git Bash에서 이 폴더로 이동한 뒤:

```bash
git init
git add .
git commit -m "첫 홈페이지 업로드"
git branch -M main
git remote add origin https://github.com/깃허브아이디/저장소이름.git
git push -u origin main
```

그 다음 GitHub 저장소에서:

Settings → Pages → Build and deployment → Deploy from a branch

Branch는 `main`, 폴더는 `/(root)`를 선택하고 저장하세요.

몇 분 뒤 아래 형태의 주소로 접속할 수 있습니다.

`https://깃허브아이디.github.io/저장소이름/`

저장소 이름 자체가 `깃허브아이디.github.io`이면:

`https://깃허브아이디.github.io/`
