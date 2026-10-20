# 바이브코딩 교원 연수

중학교 선생님을 위한 셀프 바이브코딩 연수 자료입니다. 모든 페이지는 HTML 파일 하나로 되어 있어 별도 설치나 빌드 없이 열립니다.

> 이 연수의 관점: AI를 쓰기 위한 수업이 아니라, 수업에 AI가 필요할 때 꺼내 쓸 수 있는 선생님이 되는 것을 목표로 합니다.

## 구성

`index.html`은 전체 목차(첫 화면)입니다.

### 이론

| 파일 | 내용 |
|---|---|
| `1-ai-basics.html` | AI 기본 이론 · AI가 답을 만드는 원리, 토큰, 환각, API, 모델·생각 깊이, 프롬프트, 안전 수칙, 자료를 고르는 기준 |
| `ai-rankings.html` | 부문별 AI 순위 · 생각하기·코딩·그림·영상·목소리·음악마다 다른 1위, 순위 읽는 법과 고르는 법 (2026.10.20 기준) |
| `special-agent-ai.html` | 에이전트 AI · 일을 끝까지 맡기는 에이전트 사용법과 안전 수칙 |
| `special-token-saving.html` | 토큰 절약 · 어떤 AI에서든 한도를 아끼는 대화 습관 여섯 가지 |
| `refactoring.html` | 리팩토링 (심화) · 꼬인 코드를 기능 그대로 정리하는 시기, 다섯 단계, 부분 정리, 새 기능과 나누기 |
| `special-prompt-sites.html` | 프롬프트 도우미 사이트 · 디자인·색·글꼴을 대신 말해 주는 사이트 모음과 쓰는 법 |

### 실습

| 파일 | 내용 |
|---|---|
| `2-pptx-slides.html` | 수업 PPT 만들기 · 지침서·글꼴·에셋을 담은 작업 폴더로 매번 같은 품질의 PPTX |
| `worksheet.html` | 학습지 만들기 · 설계표, 한글(HWPX)·Word(DOCX)·HTML→PDF 세 가지 완성법, 수준별 버전과 정답지, 인쇄 전 점검 |
| `3-student-webapp.html` | 학생 참여형 웹앱 · 바이브코딩으로 만들고 GitHub·Netlify로 배포, 가지로 새 버전 |
| `4-image-generation.html` | 이미지 생성해 보기 · 그림 설계표, 한 가지씩 고치기, 같은 캐릭터 유지, 글자·도식 따로, 점검표와 AI 표시 |
| `5-video-generation.html` | 영상 생성해 보기 · 카메라 움직임과 장면 설계, 그림에서 영상으로, 스토리보드·편집, 딥페이크 안전 수칙 |
| `6-assessment-design.html` | 평가 구상·설계 · 성취기준에서 채점 기준·문항·피드백·웹 형성평가 설계서까지 |
| `7-data-collection.html` | 결과 수집·데이터화 · 구글 시트 저장소, 학생 정보 보호, 정답률·오답 분석 |
| `special-html-slides.html` | HTML 슬라이드 · PPT의 대항마, 활동이 슬라이드 안에 들어 있는 수업 자료 |

## GitHub Pages로 게시하기

1. GitHub에서 새 저장소를 만듭니다. 예) `ai-teacher-training` (Public)
2. 저장소 화면의 **Add file → Upload files**로 이 폴더 안의 파일을 모두 끌어다 놓고 **Commit changes**를 누릅니다.
   - `.nojekyll`처럼 점(.)으로 시작하는 파일이 보이지 않으면 빼도 괜찮습니다.
3. 저장소의 **Settings → Pages**에서 **Source**를 **Deploy from a branch**로, **Branch**를 `main` / `(root)`로 고르고 **Save**를 누릅니다.
4. 1~2분 뒤 `https://내아이디.github.io/ai-teacher-training/` 주소에서 열립니다.

## Netlify로 게시하기

「학생 참여형 웹앱」 4장과 같은 방법입니다. 위 1~2번으로 저장소를 만든 뒤, Netlify에서 **Add new project → Import an existing project → GitHub**로 저장소를 고르고, 빌드 명령은 비워 둔 채 배포합니다.

## 고칠 때

- 각 HTML 파일을 GitHub 화면에서 연필 버튼으로 직접 고치거나, 고친 파일을 다시 올리면 됩니다.
- 큰 변경은 「학생 참여형 웹앱」 4-4처럼 가지(branch)를 만들어 미리 확인한 뒤 합치세요.
- 페이지끼리의 링크는 같은 폴더 안의 파일 이름으로 연결되어 있습니다. 파일 이름을 바꾸면 링크도 함께 바꿔야 합니다.

## 참고

- 글꼴은 Google Fonts, QR코드 기능(「학생 참여형 웹앱」)은 cdnjs의 qrcodejs를 인터넷으로 불러옵니다.
- 실습 체크 표시와 입력 내용은 각자의 브라우저(localStorage)에만 저장되며 서버로 보내지지 않습니다.
- 각 서비스의 메뉴 이름은 업데이트로 바뀔 수 있습니다.
