# 미션 4: 실전 RAG

## 📌 미션 정보

- **날짜**: 2025.10.08 (수)
- **학습 범위**: Part8 - 실전 RAG
- **제출 기한**: 2025.10.08 23:59

---

## 🎯 학습 목표

이 미션에서는 실전 환경에서 활용 가능한 고급 RAG 시스템을 구현합니다.

### 주요 학습 내용
- 고급 RAG 기법 (Re-ranking, Hybrid Search 등)
- 문서 chunk 최적화
- RAG 성능 개선 기법
- 실제 서비스에 적용 가능한 RAG 파이프라인

---

## 📝 실습 내용

### 구현 기능
- [ ] 고급 문서 처리 (다양한 포맷 지원)
- [ ] 효율적인 chunking 전략 구현
- [ ] Hybrid Search (키워드 + 벡터 검색)
- [ ] Re-ranking을 통한 검색 품질 향상
- [ ] 답변 생성 품질 개선
- [ ] RAG 평가 지표 측정

### 사용 기술
- Python
- LangChain
- Advanced Vector Database
- Re-ranking Models
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

<img width="560" height="339" alt="image" src="https://github.com/user-attachments/assets/c2542c89-da46-4516-a4ec-4a51da672322" />

---

## 🤔 학습 내용 정리

### 배운 점
- llm을 제외하고 RAG성능 평가
    - 정답 idx가 있는 경우 -> accuracy
    - 정답 idx가 없는 경우
        - RAGAS - context recall
            - similarity(model.answer, ground_truth)
- The Needle in a Haystack 
    - 입력을 주고 입력 내에서 특정 텍스트를 찾는 테스트
    - LLM의 Input Context 길이가 1M이상으로 늘지만 너무 긴 Input을 잘 기억하지 못하는 경우도 있음


### 어려웠던 점
- bug

### 개선하고 싶은 점
- 다른 데이터로 해보고픔

---

## 📚 참고 자료

- [온라인 강의 링크]()
- [Advanced RAG Techniques](https://www.pinecone.io/learn/series/rag/)

---

**작성자**: [장준규]  
**작성일**: 2025.10.08

