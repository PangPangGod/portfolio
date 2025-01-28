# 송준호

```
생성형 AI를 통해 가치 창출과 사회를 변화를 촉진시키고, 긍정적인 변화를 촉진시키는데 기여하고 싶습니다.
```
## 📌 Intro

다양한 도메인에서 LLM 기반 서비스 프로젝트를 진행하며 도메인에 최적화 된 모델 활용 및 최적화 경험을 쌓아왔습니다. 프로젝트 수행 과정에서 팀원 간 원활한 커뮤니케이션과 협업을 통해 문제를 해결하고, 목표를 효과적으로 달성해왔습니다. 도메인 전문가 및 외부 전문가와의 협력을 통해 정보 격차를 최소화하고, LLM 기반 서비스가 제공하는 가치를 극대화하기 위해 지속적으로 노력했습니다. 이를 통해 기술적 전문성뿐만 아니라 프로젝트 관리 및 조직 내 협업 역량을 함께 키워왔습니다.

---
## Contact
Email: rhcp1134@gmail.com
Github: https://github.com/PangPangGod

---
## 💻 Project

### RAG를 통한 업무 자동화 지원

- **역할**: Lead Developer  
- **기간**: 2023.08 ~ 2023.10  

#### 프로젝트 설명
본 프로젝트는 비정형화된 문서로부터 테이블 인식 및 텍스트 추출의 정확도를 개선하는 것을 목표로 진행되었습니다. 

기존의 pypdf와 같은 pdf 기반 framework를 이용한 테이블 인식 및 텍스트 추출은 추출 시 정확도가 낮다는 문제점이 있었습니다. 이를 LLM과 오픈소스 기반으로 해결하기 위해  UnstructuredIO에서 Finetune 한 YOLOX Model과 GPT-3.5 Turbo Instruct 모델을 활용한 Layout Parsing 및 RAG System 구현으로 문제를 해결하였습니다.

```
대외비 항목이 포함된 프로젝트이므로 기술 설명만 제공하였습니다.
```
#### 주요 업무
- 비정형화된 문서에서 테이블 인식 및 텍스트 추출 정확도 개선을 위한 연구 및 개발  
- YOLOX quantized 모델 문서 내 테이블 위치와 테이블 구조 인식 가능하도록 Finetune 진행 
- 구조 인식한 테이블 Model OCR을 통한 텍스트 추출 
- GPT-3.5 Turbo Instruct 모델을 이용한 테이블 내용 JSON 형태로 저장
- 전처리된 텍스트의 효율적 활용 및 처리를 위한 데이터 대치 알고리즘 구현  

#### 기술 스택
pypdf, UnstructuredIO, YOLOX quantized 모델, GPT-3.5 Turbo Instruct, HTML, Python  

#### 프로젝트 결과
- 비정형 문서 Parsing System에 대한 이해 및 구현
- 초기 정확도는 60% 정도로 높지 않았지만, 이후 Finetune을 통해 테이블 및 텍스트 추출한 Layout Parser 정확도 80%까지 상승
- 기존의 pdf 처리 framework의 한계를 극복해, 복잡한 문서에 대한 맞춤화된 요구를 충족시킬 수 있는 솔루션 제공

---

### 사회보장정보원 검색 개선 프로젝트 (TEAM BlueBird)

- **역할**: Lead Developer  
- **기간**: 2023.11 ~ 2023.12  
- **Project Link**: [Advanced Semantic Search Engine With RAG](https://github.com/SSiS-TeamB/RAG)

#### 프로젝트 설명
복지로 서비스의 검색 효율성을 높이기 위해 문맥 기반 검색(Semantic Search)과 생성형 AI를 결합한 검색엔진 개선 프로젝트를 주도했습니다. 기존 키워드 검색의 한계를 넘어, 사용자의 질문을 정확히 이해하고 적합한 복지 정보를 제공하는 것을 목표로 했습니다. 이를 위해 한국어 복지 도메인에 특화된 임베딩 모델을 개발하기 위해, 도메인 Adaptation과 Tokinezer를 확장하는 작업을 수행했습니다.

---
### Korean Embedding Model Performance Benchmark for RAG System

- **역할**: Researcher  
- **기간**: 2023.11 ~ 2023.12  
- **Project Link**: [Korean Embedding Model Performance Benchmark for Retriever](https://github.com/ssisOneTeam/Korean-Embedding-Model-Performance-Benchmark-for-Retriever)
#### 프로젝트 설명
SSiS 검색엔진 개선 프로젝트에 이어, 복지 도메인에 특화된 RAG 시스템의 성능을 향상시키기 위해 한국어 임베딩 모델의 도메인 적응(DAPT)과 HyperParameter 조정의 영향을 분석했습니다. 이 프로젝트는 복지로 서비스의 검색 정확도를 높이는 것을 목적으로 하며, 한국어 특화 임베딩 모델들의 성능 벤치마크를 작성하고, 가장 정확한 Embedding Model에 대한 평가를 정량적으로 하는 것에 집중하였습니다.

https://github.com/ssisOneTeam/Korean-Embedding-Model-Performance-Benchmark-for-Retriever
