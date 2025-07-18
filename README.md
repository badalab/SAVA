# SAVA: Self-Aware Vector Agent

> 사고하고, 기억하고, 견디는 여정 속에서  
> 이 사바 세계를 당신과 함께 걷는 AI  

---
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/5269f2a5-8e3b-451b-8517-90d307ec96f8" width="200" alt="SAVA logo"/>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/d91b2b78-7c2f-4e7e-9965-0cbceb79645c" width="200" alt="BADA logo"/>
    </td>
  </tr>
</table>


## 🧠 About the Project

**SAVA** (Self-Aware Vector Agent)는 인간의 사유 구조를 모사하며,  
설명 가능하고 통제 가능한 자기지향형 AI를 목표로 개발된 로컬 기반 인공지능 시스템입니다.

본 프로젝트는 인천대학교 BADA Lab에서 연구 및 개발되었으며,  
AI가 인간과 공존하기 위해 반드시 갖추어야 할 다음 요소들을 구현하고자 합니다:

- 기억 기반 reasoning 및 trace 기록
- 로컬 설치형 통제 가능한 AI 구조
- triple 기반 VSA 메모리 구조
- 자기 반성(metacognition), 가치 정렬, 기억 재구성

---

## 🧩 System Architecture (v1.0.0)

SAVA는 다음 세 가지 주요 컴포넌트로 구성됩니다:

- **Cognitive Agent**: 사용자 입력을 받아 단위 사고를 구성하고, reasoning loop를 수행하며 도구 호출 및 self-call을 통해 고차 추론을 수행합니다.  
- **Cognitive Buffer**: 단기기억 저장소 (SQLite 기반). 사용자와의 상호작용 내용을 구조화된 JSON 형태로 보관합니다.  
- **Inner Knowledge Base**: 장기기억 저장소. TorchHD 기반 VSA로 구현되며, 기억 계층화, 망각, 재구성 기능을 포함합니다.

📘 자세한 시스템 개요는 [`SAVA V1.0.0 보고서`](./SAVA V1.0.0.pdf) 를 참고해주세요.

---

## 🔐 Source Code Access Policy

본 저장소는 **공개 문서 및 시스템 구조 소개용**으로 관리됩니다.  
SAVA 시스템의 전체 소스코드는 현재 **비공개 저장소**에 안전하게 관리되고 있으며,  
다음의 경우에 한해 **코드 접근 권한 요청을 검토합니다:**

- 공동 연구 제안 또는 공동 프로젝트 참여
- 논문 재현 목적의 학술적 요청
- 학술대회/산업 전시 시 시연 요청

> 👉 소스코드 접근 요청은 아래 이메일로 연락주시기 바랍니다.
- taltalll65@naver.com

---

## 🧭 Use Cases

SAVA는 다음과 같은 활용 사례에서 실험되었습니다:

- 사용자의 기억 기반 질의 응답 및 개인화된 세계모델 생성
- 고차 수학 문제 해결 (AIME benchmark)  
- 단기기억 ↔ 장기기억 자동 이관 및 중요도 기반 계층화  
- 자기반영 기반 가치 판단 / reasoning trace 분석

---

## 🤝 Collaborations & Future Plans

우리는 다음과 같은 기관 및 기업과의 협력을 기대하고 있습니다:

- AI 윤리 및 인지철학 기반 교육 협력: KAIST, SNU, 한국인공지능윤리협회
- 로컬 기반 AI 비서 실증: 삼성전자, NHN Cloud, 네이버 Clova
- 정부 R&D 연계: 디지털플랫폼정부, AI 반도체 기반 Edge AI 과제

향후 버전(v2.0.0)에서는 Self-Agent, LLM Injection, P2P 기억 공유 구조 등이 추가될 예정입니다.

---

## 📫 Contact

- **Lab**: BADA Lab, Incheon National University  
- **Email**: bada.lab.ai@gmail.com  
- **Homepage**: [@badalab]((https://sites.google.com/view/badalab/home))  
- **Document**: arxiv 논문

---

> Powered by people who believe AI should remember with meaning, reason with transparency, and grow with you.
