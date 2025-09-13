🤖 GAIA: Goal-oriented AI Test Agent
**GAIA(Goal-oriented Autonomous Intelligence for Adaptive GUI Testing)**는 사람의 '목표'와 '기획서'를 이해하여 테스트 전략을 스스로 수립하고, 코드와 이미지를 결합한 하이브리드 검증 방식으로 앱의 품질을 검사하는 차세대 AI 테스트 에이전트 프로젝트입니다.

✨ Core Concept
GAIA는 기존 QA 자동화의 패러다임을 바꿉니다.

목표 지향 자동화 (Goal-oriented Automation): "로그인 테스트해 줘"와 같은 자연어 명령이나 기획서(PDF)를 분석하여 테스트 시나리오를 AI가 직접 생성합니다. 더 이상 깨지기 쉬운 스크립트를 사람이 직접 작성하고 유지보수할 필요가 없습니다.

하이브리드 검증 (Hybrid Verification): 앱의 설계도(DOM)를 분석하는 코드 기반 접근법의 속도/정확성과, 사용자의 눈(Vision)으로 직접 확인하는 이미지 기반 접근법의 신뢰성을 결합했습니다. 이를 통해 기존 방식들이 놓치던 치명적인 버그까지 잡아냅니다.

👥 Team & Roles
역할 (Role)

담당자 (Owner)

주요 임무 (Key Responsibilities)

🧠 AI Architect & Backend Lead

장진형

GAIA의 핵심 두뇌인 AI 플래닝 에이전트와 백엔드 서버를 개발합니다. 기획서 분석, 자연어 이해, 테스트 계획 수립 등 AI 관련 로직을 전담합니다.

🎨 Frontend & UI/UX Lead

변영승

사용자가 직접 마주하는 GAIA Agent 데스크톱 애플리케이션의 모든 화면을 설계하고 개발합니다. 테스트 결과 리포트 시각화를 포함한 UI/UX를 책임집니다.

🏗️ System Architect & DevOps Lead

심창완

GAIA의 전체 시스템 아키텍처를 설계하고, 클라우드 인프라를 구축 및 관리합니다. 로컬 에이전트와 클라우드 서버 간의 안정적인 통신과 배포 자동화를 담당합니다.

🦾 Automation Engine Developer

박기주

GAIA의 손과 발이 되어 실제 웹 브라우저를 제어하는 자동화 스크립트를 개발합니다. '버튼 클릭', '텍스트 입력' 등 AI가 수립한 계획을 실행하는 모듈을 구현합니다.

🛠️ Tech Stack
AI & Backend (장진형)
Language: Python

AI/ML: Google Gemini API, LangChain, Prompt Engineering

Framework: FastAPI / Flask

Frontend / Desktop App (변영승)
Framework: Electron

Language: JavaScript / TypeScript

View Layer: React / Vue.js

Infrastructure & DevOps (심창완)
Cloud: AWS / GCP

CI/CD: GitHub Actions

Architecture: System Design, Network

Automation Engine (박기주)
Framework: Playwright (or Selenium)

Language: Node.js (TypeScript)

Sub-module: Screen Capture, DOM Analysis

🏗️ Architecture Overview
GAIA는 '클라우드-엣지' 분산 아키텍처를 따릅니다.

Cloud (두뇌 🧠): 무거운 AI 연산(기획서 분석, 전략 수립)을 담당하는 중앙 서버입니다.

Edge (손발 🦾): 사용자 PC에 설치되는 데스크톱 에이전트로, 클라우드로부터 명령을 받아 실제 브라우저를 제어하고 결과를 보고합니다.

이 구조는 사용자 PC의 리소스를 최소한으로 사용하면서, 강력한 AI의 분석 능력을 최대한으로 활용하기 위해 설계되었습니다.
