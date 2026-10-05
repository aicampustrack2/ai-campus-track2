# ai-campus-track2

**메가존클라우드 AI 캠퍼스 TRACK 02 · 하이브리드 클라우드 기반 AI 아키텍트 엔지니어 양성과정**
수업 자료(교안·실습 코드·문서) 공유 저장소입니다.

> 리눅스부터 Kubernetes·AWS·IaC까지, AI 서비스를 떠받치는 인프라 전문가로 성장하는 과정

`Linux` `Kubernetes` `AWS` `Terraform` `GPU·CUDA` `MLOps`

---

## 과정 소개

리눅스 기초부터 생성형 AI 서비스 운영까지 아우르는 AI 인프라 전문가 양성 과정입니다.
GPU 컨테이너 환경, 벡터 DB·AWS 아키텍처 설계, 인프라 자동화(IaC)까지 실무 MLOps 핵심 역량을 익힙니다.

| 항목 | 내용 |
| --- | --- |
| 교육 기간 | 984시간 · 약 6개월 (평일 09:00~18:00) |
| 교육 장소 | 과천 캠퍼스 — 과천 메가존클라우드 2층 교육장 |
| 과정 안내 | https://training.megazone.com/ai-campus/architect.html |

※ 수업 일정과 진도는 과정 운영 사정에 따라 바뀔 수 있습니다. 자료에 적힌 일정은 기준안으로 보시고, 실제 일정은 수업 중 공지를 따라 주세요.

---

## 커리큘럼

### 정규 교과 — 기본기부터 전공 심화까지

| 단계 | 교과 | 주요 내용 |
| --- | --- | --- |
| 1 | 생성형 AI & 프롬프트 기초 | LLM 핵심 원리, Gemini API 활용, Zero-shot · CoT · 메타 프롬프팅 |
| 2 | AI 바이브 코딩 | Cursor 기반 AI-Native 개발 환경, 자연어 기반 코드 생성·디버깅 |
| 3 | Vibe Coding MVP 프로젝트 | 아이디어를 실행 가능한 프로토타입으로 구현·발표 |
| 4 | AI-Ready 네트워크 인프라 | TCP/IP, LAN · Trunk · L3 라우팅 · NAT, ACL 접근 제어 |
| 5 | AI-Ready 리눅스 인프라 | 파일 시스템·권한 관리, 셸 스크립트 자동화, NVIDIA 드라이버·CUDA |
| 6 | Python 기반 LLM 서비스 | Conda 가상환경, Hugging Face · Ollama, 모델 양자화, FastAPI |
| 7 | Docker & Kubernetes | 이미지 최적화, 클러스터 구축·관리, Pod · Deployment · Service |
| 8 | AI 데이터 아키텍처 & RAG | MySQL 데이터 모델링, Vector DB · pgvector, RAG 파이프라인 |
| 9 | AWS Cloud Architecture | VPC 보안 설계, EC2 · S3 · RDS, 고가용성·로드밸런싱 |
| 10 | AWS AI Cloud Operations | GPU 인스턴스 모델 운영, SageMaker Studio, EFS 모델 스토리지 |
| 11 | Terraform & CI/CD 자동화 | Terraform HCL, GitLab CI/CD 파이프라인, 이미지 빌드·자동 배포 |

### 프로젝트 & 특강 — 실전 프로젝트와 취업 준비

| 단계 | 교과 | 주요 내용 |
| --- | --- | --- |
| 12 | AI Cloud 실전 프로젝트 | 폐쇄형 AI 검색, 대규모 트래픽 AI 추천, 에지 컴퓨팅, AI 문서 요약·번역 |
| 13 | 취업 역량 & 포트폴리오 | 포트폴리오 완성, 기술 면접 대비, 프로젝트 성과 발표 |

---

## 자료 받기

처음 한 번만 내려받습니다.

```bash
git clone https://github.com/aicampustrack2/ai-campus-track2.git
cd ai-campus-track2
```

새 자료가 올라오면 아래 명령으로 최신 상태를 가져옵니다.

```bash
git pull
```

> 저장소 안의 파일을 직접 고치면 `git pull` 때 충돌이 날 수 있습니다.
> 실습은 저장소 밖으로 복사한 폴더에서 진행하는 것을 권장합니다.

---

## 주의 사항

- AWS 액세스 키, `.pem` 키 파일, `.env`, `terraform.tfstate`, kubeconfig 같은 **인증 정보는 절대 올리지 않습니다.**
  공개 저장소에 올라간 키는 몇 분 안에 자동 수집되어 악용될 수 있습니다. 이 파일들은 `.gitignore`로 막아 두었습니다.
- 모델 가중치(`.gguf`, `.safetensors` 등) 같은 대용량 파일은 올리지 않고, 내려받는 방법만 안내합니다.

---

## 이용 안내

이 저장소의 자료는 **본 부트캠프 훈련생의 학습을 위해 공유**합니다.
자세한 이용 조건은 [LICENSE](./LICENSE)를 확인해 주세요.
