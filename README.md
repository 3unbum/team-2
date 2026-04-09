# 🚀 2조 팀 자기소개

코드잇 풀스택 13기 **2조** 팀원들의 자기소개 정적 웹 페이지입니다.

## 🔗 배포 / 저장소

- **배포 주소**: [https://team-2-project.netlify.app](https://team-2-project.netlify.app)
- **GitHub**: [https://github.com/3unbum/team-2](https://github.com/3unbum/team-2)

## 👥 팀원

| 이름 | 페이지 |
|------|--------|
| 이은범 | `sub-eunbum.html` |
| 류재은 | `sub-jj.html` |
| 한효주 | `sub-hyoju.html` |
| 최병관 | `sub-byungkwan.html` |
| 이승재 | `sub-seungjae.html` |
| 김서윤 | `sub-seoyoon.html` |

## 📁 프로젝트 구조

```
team_project/
├── index.html          # 메인 페이지 (팀원 카드 목록)
├── sub-eunbum.html
├── sub-jj.html
├── sub-hyoju.html
├── sub-byungkwan.html
├── sub-seungjae.html
├── sub-seoyoon.html
└── src/
    ├── style/
    │   ├── reset.css       # CSS 리셋
    │   ├── style.css       # 메인 페이지 스타일
    │   └── sub-page.css    # 서브 페이지 공통 스타일
    └── images/             # 프로필 및 팀 이미지
```

## 🛠 기술 스택

- HTML5
- CSS3

## 🚀 로컬 실행 방법

별도 빌드 없이 정적 서버로 실행합니다.  
이미지 경로가 루트 절대경로(`/src/images/...`)로 설정되어 있어 **정적 서버 실행이 필요**합니다.

```bash
# VS Code Live Server 확장 사용 (권장)
# 또는 npx serve 사용
npx serve .
```

이후 브라우저에서 `http://localhost:3000`으로 접속합니다.

## 🌿 브랜치 전략

| 브랜치 | 역할 |
|--------|------|
| `main` | 최종 배포 브랜치 |
| `dev`  | 개발 통합 브랜치 |
