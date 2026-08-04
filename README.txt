nnme_archive playlist maker

배포 방법

1. Cloudflare Pages (가장 간단)
- Cloudflare 대시보드에서 Workers & Pages > Create > Pages > Upload assets
- 이 폴더 안의 index.html을 업로드
- 생성된 pages.dev 링크를 친구에게 공유

2. Netlify Drop
- https://app.netlify.com/drop 접속
- 이 폴더를 통째로 드래그앤드롭
- 생성된 netlify.app 링크 공유

3. GitHub Pages
- 새 GitHub 저장소 생성
- index.html을 저장소 최상단에 업로드
- Settings > Pages > Deploy from a branch > main / root 선택

특징
- 서버와 데이터베이스 불필요
- 이미지와 입력값은 브라우저 내부에서만 처리
- ChatGPT API 키 불필요
- ChatGPT 추천 프롬프트 복사 후 결과 JSON을 붙여넣는 방식
