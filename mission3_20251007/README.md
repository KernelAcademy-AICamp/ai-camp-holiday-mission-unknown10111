# 미션 3: RAG 기초 이론 & 실습

## 📌 미션 정보

- **날짜**: 2025.10.07 (화)
- **학습 범위**: Part7 - RAG 기초 이론 & 실습
- **제출 기한**: 2025.10.07 23:59

---

## 🎯 학습 목표

이 미션에서는 RAG(Retrieval-Augmented Generation)의 기초 개념을 학습하고 간단한 RAG 시스템을 구현합니다.

### 주요 학습 내용
- RAG의 개념과 원리
- 문서 임베딩과 벡터 DB
- 검색 기반 답변 생성
- LangChain을 활용한 RAG 구현

---

## 📝 실습 내용

### 구현 기능
- [ ] 문서 데이터 로드 및 전처리
- [ ] 문서 임베딩 생성
- [ ] 벡터 DB 구축 (FAISS/ChromaDB 등)
- [ ] 질문에 대한 관련 문서 검색
- [ ] 검색 결과 기반 답변 생성

### 사용 기술
- Python
- LangChain
- OpenAI Embeddings
- Vector Database (FAISS/ChromaDB)
- Jupyter Notebook

---

## 💻 실행 방법

```bash
# 필요한 패키지 설치
pip install -r requirements.txt

# Jupyter Notebook 실행
jupyter notebook

# 또는 Python 파일 실행
python main.py
```

---

## 📊 실행 결과

<img width="774" height="495" alt="image" src="https://github.com/user-attachments/assets/37f2550b-a22a-4b44-9ee6-8d5e6b58b58a" />

```
예시:
질문: "RAG란 무엇인가요?"
검색된 문서: [관련 문서 chunk들]
생성된 답변: "RAG는 Retrieval-Augmented Generation의 약자로..."
```

---

## 🤔 학습 내용 정리

### 배운 점
- - 유사도 검색 대신 인덱스로도 검색가능


### 어려웠던 점
- [미해결] streamit 멈추고 kill -9 로 없앴는데 그 다음부터 아무 명령어도 먹질 않았음(python조차...)

### 개선하고 싶은 점
- rag를 streamit에 넣어보고싶음

---

## 📚 참고 자료

- [온라인 강의 링크]()
- [LangChain 공식 문서](https://python.langchain.com/)
- [RAG 논문](https://arxiv.org/abs/2005.11401)

---

**작성자**: [장준규]  
**작성일**: 2025.10.07

