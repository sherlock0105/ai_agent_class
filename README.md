# AI Agent · Python 학습 노트

Python으로 AI 대화 호출과 대화 기록 관리를 연습하는 학습 저장소입니다.

## 구성

| 파일 | 내용 |
| --- | --- |
| `main.ipynb` | 대화 입력, 모델 호출, 메시지 기록 실습 |
| `main.py` | 기초 실행 파일 |
| `pyproject.toml` | Python 및 패키지 요구사항 |
| `uv.lock` | 의존성 잠금 파일 |
| `src/example_agent/` | 패키지 기본 구조 |

## 학습 환경

- Python 3.13 이상
- `pyproject.toml`에 정의된 `openai` 및 개발 의존성 `ipykernel`
- Jupyter 노트북을 실행할 수 있는 편집기
- 모델 호출에 사용할 `OPENAI_API_KEY` 환경 변수

노트북을 위에서부터 실행하며 입력과 응답이 `messages`에 쌓이는 흐름을 확인합니다. 저장된 출력에는 이전 실행의 오류 기록이 남아 있으므로 현재 셀을 다시 실행한 결과와 구분해서 읽으세요.

## 관련 개인 학습

[AI 일정 도우미 웹앱 실습](https://github.com/sherlock0105/ai_agent)
