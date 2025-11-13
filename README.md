# Context Engineering

## Context Engineeing 란?

[Context Engineering for AI Agents with LangChain and Manus](https://www.youtube.com/watch?v=6_BcCthVvb8)

- Context를 더 많이 사용한다고 항상 좋은 결과를 얻는것은 아닙니다.
- 간단하고 정확한 context가 대량의 context를 가지는 정보보다 좋은 결과를 얻습니다.
- Context engineering에서는 context를 추가하는것이 아니라 불필요한 정보를 제거함으로써 더 좋은 성능을 얻는것을 목표로 합니다.
- Context engineering을 통해 model이 해야할 일을 간단하게 합니다.

## Context를 줄이는 방법

- Offload
- Reduce
- Retrieve
- Isolate
- Cache

### RAPTOR

Long Context를 RAG를 이용해 처리한 RAPTOR를 기반으로 정리 예정입니다. 


![image](https://github.com/user-attachments/assets/8f193c82-ac96-42d2-b207-50ba366b1885)

Long Context RAG를 통해 긴 문서에 대해 더 나은 성능의 RAG를 제공할 수 있습니다.

[Building long context RAG with RAPTOR from scratch](https://www.youtube.com/watch?v=jbGchdTL7d0)

[Notebook - RAPTOR: Recursive Abstractive Processing for Tree-Organized Retrieval](https://github.com/langchain-ai/langchain/blob/master/cookbook/RAPTOR.ipynb)

[Paper - RAPTOR: Recursive Abstractive Processing for Tree-Organized Retrieval](https://arxiv.org/abs/2401.18059)

