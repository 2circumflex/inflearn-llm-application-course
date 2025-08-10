# inflearn-llm-application-course

RAG를 활용한 LLM Application 개발 (feat. LangChain) 강의 실습

## 섹션 1. 1. 강의의 목적과 대상

- 1.1 우리가 만들어낼 결과물로 보는 강의의 목적
- 1.2 강의자료 소스코드 (GitHub Repository, Google Colab, GitBook)

## 섹션 2. 2. 본격적인 개발 전 필요한 배경지식

- 2.1 Retrieval Augmented Generation(RAG)란?
- 2.2 Vector Database와 Embedding Model 성능 비교

## 섹션 3. 3. LangChain을 활용한 Retrieval Augmented Generation(RAG) 구성

- 3.1 환경 설정과 LangChain의 ChatOpenAI를 활용한 검증
- 3.1.1 OpenAI API quota를 늘리는 방법
- 3.1.2 수강하면서 OpenAI API를 결제하기 싫은경우 (feat. ChatUpstage)
- 3.1.3 보안문제로 인해 외부 API를 연동할 수 없는 경우 (feat. Ollama)
- 3.2 LangChain과 Chroma를 활용한 RAG 구성
- 3.2.1 OpenAIEmbeddings 대신 UpstageEmbeddings를 활용하는 방법
- 3.3 LangChain 없이 구성하는 RAG의 불편함
- 3.4 LangChain을 활용한 Vector Database 변경 (Chroma ➡️ Pinecone)
- 3.4.1 Pinecone에 UpstageEmbedding을 활용한 데이터 적재
- 3.5 Retrieval 효율 개선을 위한 데이터 전처리
- 3.6 Retrieval 효율 개선을 위한 키워드 사전 활용

## 섹션 4. 4. Streamlit을 활용한 ChatBot 구현

- 4.1 Streamlit 설치와 user message 작성
- 4.2 LangChain으로 작성한 코드를 활용한 LLM 답변 생성
- 4.3 Chat History추가와 streaming 구현
- 4.4 Few Shot을 활용한 답변 정확도 향상과 포맷 수정
- 4.5 Streamlit Cloud를 활용한 서비스 배포

## 섹션 5. 5. 부록

- 5.1 LangSmith를 활용한 LLM Evaluation
- 5.2 이제는 AI Agent의 시대
- 5.3 [업데이트] HuggingFace의 오픈소스 언어모델 활용방법
- 5.4 [업데이트] HuggingFace 오픈소스를 활용한 RAG Pipeline 구성
- 5.5 [업데이트] PromptTemplate을 활용하는 방법
