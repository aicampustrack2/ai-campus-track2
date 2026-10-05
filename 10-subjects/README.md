# 과목별 부가 자료

수업 슬라이드는 **https://ai-campus.pages.dev** 에서 보고, 이 폴더에는 수업에 쓰는 **실습 코드·예제 파일·참고 링크**를 과목별로 올립니다.

## 과목 폴더 구조

과목 폴더는 날짜(일차)가 아니라 **자료의 종류와 주제**로 나뉩니다.

```
10-subjects/06-network/
├─ README.md          ← 진도 표: 순서 · 주제 · 사이트 Day · 상태 · 자료 링크
├─ labs/              ← 실습 (주제 이름 폴더, 앞 번호는 배우는 순서)
│   ├─ 01-vpc-basic/
│   ├─ 02-subnet-routing/
│   └─ 03-nat-gateway/
├─ files/             ← 예제 데이터·설정 파일·내려받을 자료
└─ references.md      ← 참고 링크·명령어 모음
```

- 실습 폴더는 **해당 실습을 시작할 때** 하나씩 추가됩니다.
- 실습 폴더 이름은 날짜가 아니라 **주제**라서, 복습할 때도 내용으로 바로 찾을 수 있습니다.

## ⏱ 일정과 자료를 분리했습니다

```
 진도 표 (일정 — 바뀔 수 있음)                  폴더 (자료 — 바뀌지 않음)

 순서 | 주제        | 사이트 Day | 상태
 ─────┼─────────────┼──────────┼──────────
  1   | VPC 기초     | Day 22    | 완료      ─▶ labs/01-vpc-basic/
  2   | 서브넷·라우팅 | Day 23    | 진행 중   ─▶ labs/02-subnet-routing/
  3   | NAT 게이트웨이 | Day 25    | 예정      ─▶ labs/03-nat-gateway/
                     ▲
          진도에 따라 이 칸만 바뀜
```
(위 표는 읽는 법을 보여 주는 예시입니다.)

- 순서와 자료 위치는 고정이고, **며칠에 배우는지는 진도에 따라 달라질 수 있습니다.**
- 한 주제가 이틀에 걸치거나 두 주제를 하루에 진행할 수도 있습니다.
- **사이트 Day**는 수업 사이트의 Day 번호입니다. 같은 내용의 슬라이드를 찾을 때 쓰고, 진도가 바뀌면 함께 고쳐집니다.
- 지금 어디를 하는지는 **진도 표의 「진행 중」** 과 저장소 첫 화면의 「현재 진도」로 확인해 주세요.
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
