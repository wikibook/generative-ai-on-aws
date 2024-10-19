# 2장 프롬프트 엔지니어링과 콘텍스트 내 학습
[![](../img/gaia_book_cover_sm.png)](https://www.amazon.com/Generative-AI-AWS-Multimodal-Applications/dp/1098159225/)

# 질문&답변

_Q: 생성형 AI에서 프롬프트와 컴플리션은 어떻게 작동하나요?_

A: 생성형 AI의 프롬프트는 작업에 필요한 인스트럭션, 콘텍스트, 제약 조건을 포함하는 텍스트 기반 입력입니다. AI 모델은 학습한 내용을 바탕으로 텍스트, 이미지, 비디오, 오디오 등 '컴플리션'으로 응답합니다.

_Q: 프롬프트 엔지니어링에서 토큰은 어떤 역할을 하나요?_

A: 프롬프트 엔지니어링에서 토큰은 매우 중요합니다. 생성 모델은 텍스트 기반 프롬프트와 컴플리션을 토큰이나 단어 조각 순서로 변환합니다. 토큰은 단어를 나타내며, 모델이 언어 기반 응답을 처리하고 생성하게 합니다.

_Q: 프롬프트 구조의 개념을 설명해 주시겠습니까?_

A: 프롬프트 구조는 일반적으로 인스트럭션, 콘텍스트, 입력 데이터, 출력 표시자를 포함합니다. 효과적인 프롬프트 엔지니어링은 명확하고 구체적인 프롬프트 구조로 모델이 원하는 출력을 생성하도록 유도합니다.

_Q: 생성형 AI에서 콘텍스트 내 학습이란 무엇인가요?_

A: 생성형 AI의 콘텍스트 내 학습은 프롬프트 입력과 함께 여러 프롬프트-컴플리션 쌍을 전달하는 것을 포함합니다. 이 기법은 요청에 대해 모델의 작동을 일시적으로 변경해, 문맥에 제공된 예시와 유사한 방식으로 응답하도록 유도합니다.

_Q: 퓨샷 추론은 제로샷 및 원샷 추론과 어떻게 다른가요?_

A: 퓨샷 추론은 모델이 학습할 수 있도록 프롬프트 콘텍스트 내에 여러 예시를 제공하는 것입니다. 반면 원샷 추론은 단일 예시를 사용하고, 제로샷 추론은 예시를 사용하지 않고 모델의 기존 지식과 일반화 능력에 의존합니다.

_Q: 콘텍스트 내 학습의 모범 사례는 무엇인가요?_

A: 효과적인 콘텍스트 내 학습을 위해서는 제로샷 추론으로 시작하고 필요에 따라 원샷 또는 퓨샷 추론으로 진행하세요. 예시의 조합이 작업에 일관되고 적절한지 확인하세요. 콘텍스트가 모델의 입력 크기나 콘텍스트 윈도를 초과하지 않도록 해야 합니다.

_Q: 효과적인 프롬프트 엔지니어링 기법에는 어떤 것들이 있나요?_

A: 효과적인 프롬프트 엔지니어링 기법에는 명확하고 간결하게 작성하기, 창의력 발휘하기, 긴 텍스트일 경우 인스트럭션을 프롬프트 끝으로 이동하기, 주제를 명확하게 전달하기, 명시적 지시문 사용하기, 부정적 표현 피하기, 콘텍스트와 퓨샷 예시 포함하기, 응답 크기 지정하기, 구체적인 응답 형식 제공하기 등이 있습니다.

_Q: 프롬프트 엔지니어링에서 중요한 추론 구성 매개변수는 무엇인가요?_

A: 프롬프트 엔지니어링에서 중요한 추론 구성 매개변수에는 콘텐츠 생성 시 모델의 창의성을 제어하는 temperature와 top-k가 포함됩니다.

_Q: 프롬프트 구조는 생성형 AI 모델의 성능에 어떤 영향을 미치나요?_

A: 프롬프트 구조는 생성형 AI 모델이 원하는 출력을 생성하도록 유도해 모델의 성능에 영향을 미칩니다.

# 목차
* [1장](/01_intro) - 생성형 AI 활용 사례, 기본 사항 및 프로젝트 생명 주기
* [2장](/02_prompt) - 프롬프트 엔지니어링과 콘텍스트 내 학습
* [3장](/03_foundation) - 대형 언어 파운데이션 모델
* [4장](/04_optimize) - 메모리와 연산 최적화
* [5장](/05_finetune) - 미세 조정 및 평가
* [6장](/06_peft) - 효율적인 매개변수 미세 조정(PEFT)
* [7장](/07_rlhf) - 인간 피드백을 통한 강화 학습으로 미세 조정(RLHF)
* [8장](/08_deploy) - 모델 배포 최적화
* [9장](/09_rag) - RAG와 에이전트를 활용한 맥락 인식 추론 애플리케이션
* [10장](/10_multimodal) - 멀티모달 파운데이션 모델
* [11장](/11_diffusers) - 스테이블 디퓨전을 통한 생성 제어와 미세 조정
* [12장](/12_bedrock) - 아마존 베드록: 생성형 AI 관리형 서비스

# 관련 자료
* 유튜브 채널: https://youtube.generativeaionaws.com
* AWS에서의 생성형 AI 밋업 (글로벌, 온라인): https://meetup.generativeaionaws.com
* AWS에서의 생성형 AI - O'Reilly 서적: https://www.amazon.com/Generative-AI-AWS-Multimodal-Applications/dp/1098159225/
* AWS에서의 데이터 과학 - O'Reilly 서적: https://www.amazon.com/Data-Science-AWS-End-End/dp/1492079391/