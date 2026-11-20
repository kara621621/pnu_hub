# pnu_hub

대학원생이 논문 작업에 AI 기능을 활용하는 방법을 익히는 한글·영문 실습사이트입니다.

## 실습 내용

- 검색어 확장과 실제 문헌 탐색
- 논문에 질문하고 같은 기준으로 정보 추출
- 메모 구성과 수정 범위 지정
- 번역 비교와 용어 일관성 관리
- 표 정리와 시각화 및 수치 확인
- 초안 검토와 인용 및 피드백 관리

6개 주제에서 18개 기능을 선택할 수 있습니다. 요청문의 주제, 추가 조건, 결과 형태를 바꾸고 복사하여 ChatGPT 등 외부 도구에서 직접 실행합니다. 결과 형태는 표, 목록, CSV, 짧은 문단, 여러 문단의 글·설명문, 일반 텍스트를 지원합니다.

Google Scholar, Elicit, ResearchRabbit, Gemini Notebook / NotebookLM, Academic Phrasebank, DeepL, Zotero, 국가물류통합정보센터와 연결하는 안내를 제공합니다.

## 사용 방법

이 저장소를 내려받아 `index.html`을 브라우저로 엽니다. 별도 설치나 빌드 없이 실행하는 HTML·CSS·JavaScript 사이트입니다. 외부 도구 링크를 사용하려면 인터넷 연결이 필요합니다.

현재 운영 사이트: https://research-ai-practice-lab-ryun.kara6021.chatgpt.site/

운영 사이트의 접속 권한은 GitHub 저장소 공개 설정과 별개입니다.

## 강사 가이드

[차시별 강사 가이드 Word 문서](instructor-guide.docx)

1차시부터 6차시까지 진행 멘트, 핵심 실습, 확인 사항과 함께 쓰는 사이트 사용법을 담았습니다.

## 파일 구성

- `index.html`: 시작 화면과 공통 구조
- `style.css`, `design.css`, `efficiency.css`: 화면 디자인
- `capabilities.js`: 6개 주제와 18개 기능
- `ui.js`: 한글·영문 안내와 결과 형태
- `efficiency.js`: 화면 이동과 요청문 생성 및 복사
- `tool-guides.js`: 함께 쓰는 사이트 안내
- `samples.js`, `feature-samples.js`: 연습용 자료
- `icons.js`: 화면 아이콘
- `instructor-guide.docx`: 차시별 강사 수업 문서

입력 자료는 외부 AI에 자동 전송하지 않습니다. 요청문을 복사한 후 선택한 도구에 자료를 직접 제공해야 합니다. 논문 PDF 원본은 포함하지 않으며 실습사이트에서 원문 링크로 연결합니다.
