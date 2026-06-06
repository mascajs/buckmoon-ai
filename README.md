# buckmoon-ai

> **Practical AI integration and automation tools designed to solve real-world problems.**
> 인공지능과 코드를 결합하여 복잡한 현실의 문제를 찾아 자동화하고싶은 마음이 담긴 프로젝트 저장소입니다.


## 📌 소개 (Introduction)
`buckmoon-ai`는 일상의 불편함을 찾아 해결하는 업무 흐름(Workflow)을 혁신하기 위한 **AI 활용 및 자동화 스크립트 모음**입니다. 
대형 언어 모델(LLM) API 연동부터 구글 앱스 스크립트(GAS)를 활용한 시스템 최적화까지, 실제로 작동하고 바로 적용 가능한 테크 예제와 결과물들을 관리합니다.

## 🛠 기술 스택 (Tech Stack)
이 저장소에서 주로 다루거나 실험하는 핵심 기술 스택입니다.
- **AI & Integrations:** Gemini API, OpenAI API, Anthropic API
- **Automation & Scripting:** Google Apps Script (GAS), Python
- **Environments:** Google Workspace, Node.js, Local Environment


## ✨ 주요 기능 (Key Features)
- **AI-Driven Automation:** LLM 파이프라인을 활용한 스마트 데이터 분석 및 맞춤형 콘텐츠 생성 자동화
- **Workspace Optimization:** 구글 스프레드시트, 지메일, 드라이브를 유기적으로 연결하는 시스템 도구 개발
- **Practical Tech Experiments:** 실무 및 현장의 생산성을 극대화하기 위한 다양한 오픈소스 AI 모델 활용 실험


## 🚀 사용 방법 (Getting Started & Vibe Coding)

이 저장소는 전통적인 로컬 실행 방식뿐만 아니라, AI 코딩 어시스턴트와 협업하는 **'바이브 코딩(Vibe Coding)'의 레퍼런스 라이브러리**로 최적화되어 있습니다.

### 🤖 1. Vibe Coding 가이드 (AI 어시스턴트 활용)
이 프로젝트의 스크립트들은 모듈화되어 있어, 새로운 자동화 도구를 기획할 때 AI의 컨텍스트(Context)로 주입하기 매우 용이합니다.

* **IDE 연동 (Cursor / Github Copilot):** 저장소를 클론한 후 에디터에서 엽니다. 채팅 인터페이스에서 `@Files` 또는 `@Folders` 기능을 사용하여 `snippets/` 또는 `gas-templates/` 디렉토리를 참조(Reference)하세요.
* **프롬프트 예시:**
    > "현재 작업 공간의 `gas-templates/gmail-to-sheet.gs` 코드를 참조해서, 새로운 메일이 오면 슬랙(Slack)으로 알림을 보내는 GAS 코드를 바이브 코딩해 줘. 기존 코드의 로깅(Logging) 구조를 그대로 유지해."
* **웹 기반 LLM 활용 (Gemini / Claude):**
    각 폴더 내의 `README_CONTEXT.md` 파일은 해당 폴더의 핵심 구조와 변수명을 요약해 둔 파일입니다. 이 텍스트를 복사하여 프롬프트의 배경 지식으로 제공하면 환각(Hallucination) 없는 정확한 코드를 얻을 수 있습니다.

### 💻 2. 직접 실행 가이드 (심사 및 테스트용)
코드를 직접 실행하거나 테스트하기 위한 기본 환경 설정입니다.

**Step 1: 환경 구성 (Python / Node.js 등)**
```bash
git clone [https://github.com/mascajs/buckmoon-ai.git](https://github.com/mascajs/buckmoon-ai.git)
cd buckmoon-ai

# Python 환경일 경우
pip install -r requirements.txt
