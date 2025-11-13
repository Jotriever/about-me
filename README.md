### I'm Hyunsu Cho — a Software Engineering Student passionate about Cloud & Security.
---
### 👤 About Me & Contact
⭐ **Hyunsu Cho(2001)**<br>
🎓 **단국대학교 소프트웨어학과 (2021 ~)** <br>

✏️ **Summary**<br>

&nbsp;&nbsp;&nbsp;&nbsp;**클라우드 환경**과 **보안**을 열심히 탐구하고 공부하는 소프트웨어학과 학생입니다.
- 클라우드 환경 기반 SaaS 서비스 개발을 위해서, MSA 아키텍쳐의 구조를 설계하고, 개발 방법론 기반 스크럼 회의를 주도하였습니다.
- 암호학을 중심으로 보안을 학습하여 CTF에 꾸준하게 참여하고 있으며, critical 수준의 CVE(Log4j)에 대한 세미나를 진행한 경험이 있습니다.
- 클라우드 통신에서 발생할 수 있는 취약점을 학습하기 위해 네트워크, 시스템 보안과 같은 관련 분야를 지속적으로 학습하고 있습니다.

[![Gmail](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white)](mailto:hscho.cyber@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Jotriever/Jotriever)
[![Velog](https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=Velog&logoColor=white)](https://velog.io/@jotreiver/)

---
### 💻 Tech Stack
  #### 💬 Languages
  <img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/> <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white"/> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/> <img src="https://img.shields.io/badge/Dart-00599C?style=flat-square&logo=dart&logoColor=white"/> 

  #### ⚙️ Tools & Frameworks
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white"/> <img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=white"/> <img src="https://img.shields.io/badge/Flutter-181717?style=flat-square&logo=flutter&logoColor=white"/>
  
---
### 🚀 Key Projects
| 프로젝트명 | 기간 | 주요 내용 | 역할 |
|-------------|------|------------|------|
| **랜섬웨어 분석 및 대응 시스템 (Blue)** | 2025.10 ~ 현재 | 악성 행위 탐지 및 로그 기록 시스템 구현 | 공격 테스터 제작 |
| **전세사기 예방 플랫폼 (K-PaaS 공모전)** | 2025.07 ~ 2025.10 | 청년층 대상 전세사기 예방 플랫폼 개발 | 기획 및 프론트엔드 개발 |
| **CTF 보안 대회 참여** | 2025.07 ~ 현재 | 암호학 분야 문제 풀이 및 팀 협업 | 암호학 담당 |

### 🛡️ [랜섬웨어 분석 및 대응 시스템 (Blue) (2025.10 ~ 현재)](https://github.com/system-security-0x/ransonware-battle)

- **프로젝트 개요**: Linux의 FUSE(Filesystem in Userspace)를 활용하여 파일 시스템 레벨에서 랜섬웨어의 악성 행위를 탐지하고 로깅하는 방어 시스템을 개발했습니다.
- **담당 역할**: 공격 테스터 및 탐지 로직 개발
- **사용 기술**: Linux, FUSE, Loggedfs, OpenSSL, Python
- **수행한 활동**:
    - FUSE 기반 행위 탐지: FUSE의 Loggedfs를 활용해 특정 프로세스(pid)의 파일 시스템 접근(write, read)을 후킹하여 모니터링하고, 과도한 I/O 발생 시 악성 행위로 탐지하는 로직을 구현했습니다.
    - 엔트로피 기반 암호화 탐지: 파일 암호화 시 엔트로피가 급격히 증가하는 특징에 착안, 파일의 엔트로피를 실시간으로 계산하고 임계치 이상 변화 시 탐지하는 로직을 개발했습니다.
    - 공격/테스트 자동화: Python의 os 라이브러리를 활용해 다양한 형식(.pdf, .gz)의 더미 파일을 대량 생성하고, 엔트로피 변화를 csv로 자동 추출하여 탐지 로직을 검증하는 '공격 시뮬레이터'를 제작했습니다.
- **핵심 성과**:
    - 파일 I/O 횟수 및 엔트로피 변화라는 두 가지 핵심 지표를 기반으로 랜섬웨어의 주요 행위를 탐지/로깅하는 시스템의 PoC(Proof of Concept)를 완성했습니다.
    - 공격 시뮬레이터 제작을 통해 방어 시스템의 탐지 로직을 반복적으로 검증하고 예외 케이스를 보완할 수 있는 테스트 환경을 구축했습니다.

### 🏆 [전세사기 예방 플랫폼 (K-PaaS 공모전) (2025.07 ~ 2025.10)](https://github.com/Jeonggeonyong/voyage)

- **프로젝트 개요**: K-PaaS 클라우드 환경 위에서 청년층 대상 전세사기 예방 SaaS 플랫폼을 기획부터 배포까지 진행한 공모전 프로젝트입니다.
- **담당 역할**: Product Manager (애자일) 및 클라이언트 개발 총괄
- **사용 기술**: K8s, Docker, Flutter, Dart, Jenkins, Gitlab
- **수행한 활동**:
    - PM (Agile Master): 팀원 대상 클라우드 개론 및 MSA 교육을 직접 진행했습니다. 데일리 스크럼 및 번다운 차트를 활용하여 3개월간의 프로젝트 일정을 성공적으로 관리했습니다.
    - 클라우드 아키텍처 설계: 오토 스케일링, 이중화, 이벤트 버스를 고려한 MSA 기반 아키텍처 다이어그램을 작성했습니다. Jenkins, Gitlab, Docker 기반의 CI/CD 자동 배포 파이프라인을 설계했습니다.
    - 클라이언트 개발: Flutter 기반 클라이언트 앱의 전체 로직을 설계했습니다. Google OAuth2 기술을 도입하여 복잡했던 로그인 및 회원가입 로직 구현 문제를 성공적으로 해결했습니다.
- **핵심 성과**:
  - 5인 팀의 PM 역할을 수행하며 3개월의 짧은 기간 내 성공적인 프로토타입 배포를 완료했습니다.
  - 클라우드 네이티브 개발 프로세스 전체(기획-MSA설계-CI/CD설계-개발)를 주도했습니다.

### 🚩 [CTF 보안 대회 참여 (Crypto) (2025.07 ~ 현재)](https://velog.io/@jotreiver/)

- **활동 개요**: 다양한 국내외 CTF(Capture The Flag) 보안 대회에 팀원으로 참여, 특히 암호학(Cryptography) 분야를 전담하여 문제 해결 및 이론 학습을 병행하고 있습니다.
- **담당 역할**: 암호학(Cryptography) 문제 해결 담당
- **사용 도구**: Python, Ghidra, Burp Suite, WireShark
- **수행한 활동**:
    - 현대 암호학 문제 해결: RSA, ECC 등 현대 공개키 암호화 로직의 수학적 취약점(e.g., Small Exponent, Common Modulus)을 분석하고, 선형대수 및 행렬 연산 기반의 암호 문제를 해결했습니다.
    - 자동화 도구 개발: 단일 치환, 카이사르 암호, 다중 Base64 인코딩 등 반복적인 고전 암호 및 인코딩 문제를 신속하게 풀기 위한 Python 기반 자동 복호화 스크립트를 제작하여 활용했습니다.
    - 취약점 분석: Ghidra(리버싱), Burp Suite(웹) 등을 활용하여 프로그램이나 웹 서비스에 하드코딩된 암호화 로직을 분석하고 취약점을 탐색하는 경험을 쌓았습니다.
- **핵심 성과**:
    - 암호학 분야 문제 해결 능력을 체계적으로 향상시켰으며, 팀의 암호학 분야 점수 확보에 핵심적으로 기여했습니다.
    - 2025년 CTF 상위권 수상이라는 단기 목표 달성을 위한 실전 감각과 문제 해결 능력을 꾸준히 축적하고 있습니다.
          
### 📈 Other Activities & Experience
| 활동 내용 | 기간 | 주요 내용 | 역할 |
|-------------|------|------------|------|
| **보안 학습 동아리 참여** | 2025.07 ~ 현재 | 취약점 분석 및 워게임 문제 풀이 | 암호학 담당 |
| **토익 스터디 운영** | 2025.07 ~ 2025.09 | 토익 LC, RC에 대한 기초 학습 진행 | 운영 & 수업 |
| **OS 시뮬레이터 구현** | 2025.03 ~ 2025.06 | proc schduler, fine-grained lock, FS policy | 시뮬레이터 구현 |
| **Shake! 경인지역 알고리즘 대회** | 2025.01 ~ 2025.01 | 교내 대표로 본선 진출 | 문제 해결 |
| **Unity 게임 개발** | 2023.01 ~ 2023.07 | RPG, shooting game | Demo ver 구현|

  #### 🔹Algorithm
[![Solved.ac](http://mazassumnida.wtf/api/v2/generate_badge?boj=bird4002)](https://solved.ac/bird4002/)

---
### 📈 Goals
- ✅ **Short-term (2025):** CTF 상위권 수상, 지속적인 대외활동 진행
- 🚀 **Mid-term:** 클라우드 보안 분야 진출, 테크 블로그 운영
- 🎯 **Long-term:** 클라우드 전문 보안 컨설턴트, 멘토링 활동 지속
