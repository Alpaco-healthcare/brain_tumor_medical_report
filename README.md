# brain tumor medical report

🧠 주제

뇌종양 분석과 RAG를 활용한 자동 의학 소견 생성 시스템 구축

목표:

MRI 사진에서 3D segmentation 모델로 뇌종양 발견

전문서적 전체 PDF에서 관련 지식 정보 추출

이를 통합하여 자동으로 Medical Letter 생성

---

📂 Dataset

BRATS 데이터셋: 뇌종양 MRI 이미지 데이터

PubMed Conversation 데이터셋: 의학 논문 및 연구 대화 데이터

Brain Section 데이터셋: 뇌 MRI의 세부 절단면 이미지 데이터

---

🧑‍💻 Model

UNet: 뇌 MRI에서 종양 영역을 정확하게 분리

SwinUnetR: 스윈트랜스포머 기반의 고도화된 U-Net 모델

Gemma2-2B: 의료 관련 정보 추출을 위한 GPT 모델

Llama3: 대규모 언어 모델로 의학적 질문에 대한 답변 생성

---

⚙️ Tech Stack

Programming Language: Python

Deep Learning Framework: PyTorch

Web Framework: FastAPI

Database:

MySQL
SQLite
PostgreSQL

Medical Imaging Tools: AAL, 3D Slicer

RAG (Retrieval-Augmented Generation): 텍스트 생성과 외부 정보 검색을 결합한 모델

---
