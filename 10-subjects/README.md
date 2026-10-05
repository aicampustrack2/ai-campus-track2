# 과목별 부가 자료

수업 슬라이드는 **https://ai-campus.pages.dev** 에서 보고, 이 폴더에는 수업에 쓰는 **실습 코드·예제 파일·참고 링크**를 과목별로 올립니다.

## 폴더 구조

```
10-subjects/
└─ 02-ai-foundation/        ← 과목 (과정 순서대로 번호)
   ├─ README.md             ← 이 과목의 진도 표 (예정·진행 중·완료)
   ├─ day1/                 ← 진도 순서 1번째 분량의 자료
   └─ day2/                 ← 진도 순서 2번째 분량의 자료
```

- 일차 폴더(`day1`, `day2` …)는 **해당 수업이 시작될 때** 만들어 자료를 올립니다.

## ⏱ dayN은 날짜가 아니라 진도 순서입니다

```
 진도 순서   day1 ──▶ day2 ──▶ day3 ──▶ day4
             (고정)   (고정)   (고정)   (고정)

 실제 날짜   ┌ 계획대로 진행:      1일 → 1일 → 1일 → 1일
             ├ 한 분량이 길어질 때:  1일 → 2일 → 1일 → …
             └ 두 분량을 묶을 때:    1일 → (day2+day3 하루) → …
```

- 자료의 **순서는 바뀌지 않지만, 며칠에 배우는지는 진도에 따라 달라질 수 있습니다.**
- 지금 어디를 하는지는 **각 과목 README의 진도 표**와 저장소 첫 화면의 「현재 진도」를 기준으로 확인해 주세요.
- 일정이 크게 바뀌면 [공지](../00-notice/)로 알려 드립니다.

## 과목 목록

| 번호 | 과목 |
| --- | --- |
| [01](./01-orientation/) | 오리엔테이션 |
| [02](./02-ai-foundation/) | AI Foundation |
| [03](./03-prompt/) | 프롬프트 엔지니어링 |
| [04](./04-vibe-coding/) | 바이브 코딩 |
| [05](./05-mini-project/) | 미니 프로젝트 (MVP) |
| [06](./06-network/) | AI-Ready 네트워크 인프라 |
| [07](./07-linux/) | AI-Ready 리눅스 인프라 |
| [08](./08-llm-serving/) | Python 기반 LLM 서비스 |
| [09](./09-k8s/) | Docker & Kubernetes |
| [10](./10-data-foundation/) | AI 데이터 아키텍처 (RDBMS·Vector DB) |
| [11](./11-backend-rag/) | Backend & Service (FastAPI·RAG) |
| [12](./12-aws-infra/) | AWS Cloud Architecture |
| [13](./13-aws-ai-ops/) | AWS AI Cloud Operations |
| [14](./14-terraform/) | Terraform & CI/CD 자동화 |
| [15](./15-career/) | 취업 역량 |
| [16](./16-ai-cloud-project/) | AI Cloud 실전 프로젝트 |
| [17](./17-showcase/) | 프로젝트 발표회 |

※ 과목 순서와 시기는 과정 운영 사정에 따라 조정될 수 있습니다.
