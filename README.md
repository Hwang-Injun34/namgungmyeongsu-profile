## 남궁명수 (Namgung Myeongsu)

**Junior Backend Developer**  
- Go와 Linux를 기반으로 서버 및 시스템 소프트웨어를 공부하고 있습니다.
- OS, Network, Database의 동작 원리를 이해하고 이를 실제 개발에 적용하는 것을 중요하게 생각합니다.
---

## Contact & Channels

- **Email:** myeongsu.namgung@gmail.com
- **Phone:** 010-9405-7554

---

## Projects

### 👥 Team Projects
> 협업 기반으로 진행한 주요 프로젝트

#### 📁 Public Insight
> 지식 그래프 기반 정책 데이터 탐색 및 추천 플랫폼<br>
> 정책 간 관계를 연결하여 직관적인 탐색 및 개인화 추천 제공
- **Role:**
  - FastAPI 기반 백엔드 아키텍처 설계 및 구현
  - JWT 인증 및 미들웨어 설계
  - 정책 데이터 크롤링 및 ETL 파이프라인 구현
- **Tech Stack:** FastAPI, MySQL, Docker, Nginx, Elasticsearch
- **Repository:** [GitHub](https://github.com/Hwang-Injun34/public_insight_notes)

---

### 👤 Mini Projects (Personal)
> 개인 학습 및 실습 중심 프로젝트

#### 📁 trash-overflow-detector
> 엣지 디바이스 기반 쓰레기통 Overflow 감지 시스템 <br>
> YOLOV5 기반 영상 분석을 통해 실시간 상태를 판단하고 알림 자동 전송
- **Tech Stack:** Python, YOLOv5, Raspberry Pi
- **Key Points:**
  - Edge AI 기반 독립 실행 구조 설계
  - 영상 기반 상태 판단 로직 구현(bin/garbage/overflow)
  - 이벤트 기반 이메일 알림 시스템 구축
- **Repository:** [GitHub](https://github.com/Hwang-Injun34/trash-overflow-detector)

#### 📁 Politi-Search
> 국회 회의록을 발언 단위로 구조화하고 의미 기반 검색을 제공하는 시스템 <br> 
> 키워드 검색의 한계를 개선하고 문맥 기반 탐색 가능
- **Tech Stack:** FastAPI, Elasticsearch, MySQL
- **Key Points:**
  - 발언 단위 데이터 구조 설계 및 인덱싱
  - Elasticsearch 기반 검색 엔진 구현
  - 키워드 + 시멘틱 검색 구조 실험 및 비교 
- **Repository:** [GitHub](https://github.com/Hwang-Injun34/elasticsearch_notes)

#### 📁 mini-edr
> Linux Audit 이벤트를 수집하고 규칙에 따라 의심스러운 행위를 탐지하는 Go기반 경량 EDR 에이전트<br>
> 이벤트의 수집부터 변환, 탐지, 경고까지 이어지는 파이프라인을 직접 설계하고 구현
- **Tech Stack:** Go, Linux, Auditd
- **Key Points:**
    - 동일한 Audit Event ID의 레코드를 조립하고 공통 SystemEvent 모델로 변환
    - Collector → Dispatcher → Rule Engine → Alert 구조의 동시성 파이프라인 설계
    - JSON 기반 탐지 규칙 엔진 및 프로세스·파일·네트워크·권한 상승·영속성 탐지 규칙 구현
- **Repository:** [GitHub](https://github.com/Hwang-Injun34/mini_edr)

#### 📁 Pac-man
> x86-64 Assembly 기반 Terminal 게임 구현 프로젝트<br>
> syscall, 메모리, 레지스터 수준에서 프로그램 동작을 직접 제어
- **Tech Stack:** NASM, Linux syscall
- **Key Points:**
   - syscall 기반 입출력 및 실행 흐름 직접 구현
   - 레지스터 및 메모리 기반 게임 상태 관리
   - Raw Mode 터미널 입력 처리 및 화면 제어 구현 
- **Repository:** [GitHub](https://github.com/Hwang-Injun34/pacman-assembly)

---

### 📚 Study (Learning & Practice)

> 운영체제와 Linux를 중심으로 학습한 이론과 실습 내용을 문서화하고 있습니다.

- **Operating System:** 가상화, 병행성, I/O, 파일 시스템
- **Linux:** 기본 개념 및 시스템 프로그래밍 실습
- **Programming:** C, Go 동시성, x86-64 Assembly
- **Mathematics:** 선형대수학

- **Repository:** [Computer Science Notes](https://github.com/Hwang-Injun34/computer-science-notes)
  
