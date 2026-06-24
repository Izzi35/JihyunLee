# Jihyun Lee, Ph.D. — Personal Academic Homepage

Jihyun Lee의 academic personal homepage.
Built with plain HTML, CSS, and a small amount of JavaScript — ready to host on **GitHub Pages**.

## 현재 완성된 기능 (Completed Features)

실제 CV(Curriculum Vitae_202606) 내용을 모두 반영했습니다.

- **상단 고정 네비게이션** (About / Research / Experience / Publications / Funding / Service / Cello / Contact) — 모바일 햄버거 메뉴 지원
- **프로필 헤더** — 사진, 이름, 직함, 소속(Hallym Univ. / D.I.D.I.M.), 이메일, 전화, ORCID
- **About + Education & Training** — 학력/연수 타임라인, 본문 하이퍼링크
- **Research** — 연구 주제 카드(음악·감정, 시청각 통합, 청각·인지) + 키워드 + Technical Skills
- **Research Experience** — 직책별 소속·지도교수·프로젝트 목록 (5개)
- **Publications** — Peer-reviewed 19편, Manuscripts in Progress 3편, Patent 1건
- **Funding** — NRF 연구비 2건 (PI)
- **Honors & Awards** — 수상 3건
- **Selected Presentations** — Invited talks + 주요 학회 발표
- **Professional Service** — Editorial / Peer Review / Mentoring
- **Cello (Beyond Research)** — 첼로 소개 + DoDo Cello Orchestra 공연 포스터 + 사진 갤러리(메이슨리 + 라이트박스) + Apple Music 음원("With" 앨범, 9번 Slavonic Dance 세컨드 참여)
- **OSF / ORCID 링크** — 프로필·Publications·Contact에 연결
- **Contact** — 이메일·전화·ORCID
- **반응형 디자인** (데스크톱/태블릿/모바일)

## 기능별 경로 (Functional Entry URIs)

| 경로 | 설명 |
|------|------|
| `index.html` | 메인 페이지 (전체 콘텐츠) |
| `index.html#about` | About + Education |
| `index.html#research` | Research + Skills |
| `index.html#experience` | Research Experience |
| `index.html#publications` | Publications / Patent |
| `index.html#funding` | Funding |
| `index.html#awards` | Honors & Awards |
| `index.html#presentations` | Presentations |
| `index.html#service` | Editorial / Review / Mentoring |
| `index.html#cello` | Cello / Hobby |
| `index.html#contact` | Contact |

## 파일 구조

```
index.html          메인 페이지
css/style.css       스타일시트
js/main.js          모바일 메뉴 + 연도 표시
images/profile.jpg  ← 여기에 본인 사진을 넣으세요 (없으면 자리표시자 표시)
files/CV.pdf        ← (선택) 이력서 PDF
.nojekyll           GitHub Pages 빌드 설정
```

## ✏️ 내용 수정하는 법 (직접 채워야 할 부분)

`index.html` 에서 대괄호 `[ ... ]` 와 `href="#"`, `your.email@example.com` 으로 표시된 곳을 본인 정보로 바꾸세요.

1. **사진**: `images/` 폴더에 `profile.jpg` 추가 (권장 460×580px 세로형)
2. **소속/기관**: `[Your Department]`, `[Your University / Institute]`
3. **이메일**: `your.email@example.com` 을 실제 이메일로
4. **학술 링크**: Google Scholar / ORCID / ResearchGate / GitHub / LinkedIn 의 `href="#"` 를 실제 주소로
5. **Research**: 연구 주제 제목/설명/키워드 교체
6. **Publications**: 논문 제목, 저자, 저널, 연도, PDF/DOI 링크 교체
7. **CV**: `files/CV.pdf` 추가 후 About 섹션 링크 활성화

> 💡 본문 단어에 링크를 추가하려면 `<a href="주소" target="_blank" rel="noopener">단어</a>` 형식으로 감싸면 됩니다. (NEURECA 페이지처럼)

## 🚀 GitHub Pages 로 배포하는 법

1. GitHub에서 새 저장소(repository)를 만듭니다.
   - 본인 메인 사이트로 쓰려면 저장소 이름을 `사용자이름.github.io` 로 하면 `https://사용자이름.github.io` 주소로 열립니다.
   - 일반 저장소로 만들면 `https://사용자이름.github.io/저장소이름/` 주소가 됩니다.
2. 이 프로젝트의 모든 파일(`index.html`, `css/`, `js/`, `images/`, `.nojekyll`)을 저장소에 업로드(또는 push)합니다.
3. 저장소 **Settings → Pages** 로 이동합니다.
4. **Source** 를 `Deploy from a branch` 로 두고, Branch 를 `main` / 폴더 `/(root)` 로 선택 후 **Save**.
5. 1~2분 후 표시되는 URL로 사이트가 공개됩니다. 🎉

> 이 작업환경의 **Publish 탭**에서도 한 번에 게시할 수 있습니다.

## 아직 구현되지 않은 것 (Not Yet Implemented)

- 실제 개인 정보/사진/논문 데이터 (사용자가 직접 입력)
- 별도의 News/Blog 페이지
- 다국어(한/영) 전환

## 추천 다음 단계 (Next Steps)

1. 대괄호 자리표시자를 실제 정보로 교체
2. 프로필 사진 및 CV PDF 추가
3. GitHub 저장소 생성 후 Pages 배포
4. (선택) News 또는 Blog 섹션 추가

## 사용 기술

- HTML5 / CSS3 (custom design, 외부 빌드 불필요)
- Vanilla JavaScript
- Google Fonts (Lora, Inter), Font Awesome (CDN)
