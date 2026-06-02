# Model & Eval Signals (2026-06-03)

## 오늘의 요약
Hugging Face의 신규 멀티모달 모델 트렌드와 소프트웨어 엔지니어링 에이전트 역량 평가를 위한 새로운 벤치마크 및 모델 성과가 주요 흐름을 형성하고 있습니다.

### 오늘의 핵심 포인트
- NVIDIA 및 Stepfun-ai 등에서 이미지/텍스트 처리가 가능한 멀티모달 모델이 Hugging Face에서 주목받음
- SWE-bench 팀의 CodeClash 출시 및 mini-SWE-agent의 성과 등 소프트웨어 엔지니어링 에이전트 평가/학습 도구의 진화
- LiveCodeBench를 통한 Gemini 및 O4-Mini 등 최신 모델들의 코딩 성능 스냅샷 업데이트

**오늘의 태그**: Multimodal, AI Agents, Software Engineering Benchmark, Coding LLM

## 1. [nvidia/PiD](https://huggingface.co/nvidia/PiD)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
NVIDIA에서 공개한 image-to-image 태스크를 위한 nvidia/PiD 모델이 Hugging Face에서 주목받고 있습니다. 현재 253개의 likes와 646회의 downloads를 기록하며 트렌딩 중입니다.

### 핵심 포인트
- NVIDIA에서 배포한 image-to-image 파이프라인 모델임
- Hugging Face 내에서 likes 253개, downloads 646개를 기록 중
- 이미지 변환 작업을 위한 모델로 분류됨

**태그**: NVIDIA, image-to-image, Hugging Face

**Metrics**: {"likes": 253, "downloads": 646, "num_parameters": 0, "pipeline_tag": "image-to-image"}

### 원문 설명
likes=253, downloads=646, pipeline_tag=image-to-image

---

## 2. [stepfun-ai/Step-3.7-Flash](https://huggingface.co/stepfun-ai/Step-3.7-Flash)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Stepfun-ai에서 공개한 Step-3.7-Flash 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 제공합니다.

### 핵심 포인트
- Step-3.7-Flash 모델의 Hugging Face 트렌딩 기록
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델
- 약 201B 규모의 파라미터를 보유한 모델

**태그**: Step-3.7-Flash, image-text-to-text, multimodal

**Metrics**: {"likes": 211, "downloads": 12932, "num_parameters": 201365316160, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=211, downloads=12932, pipeline_tag=image-text-to-text

---

## 3. [meituan-longcat/LongCat-Video-Avatar-1.5](https://huggingface.co/meituan-longcat/LongCat-Video-Avatar-1.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 주목받고 있는 meituan-longcat/LongCat-Video-Avatar-1.5 모델에 대한 동향입니다. 해당 모델은 최근 481개의 likes를 기록하며 사용자들의 관심을 받고 있습니다.

### 핵심 포인트
- meituan-longcat/LongCat-Video-Avatar-1.5 모델의 Hugging Face 트렌딩 정보
- 481개의 likes와 174개의 downloads를 기록 중
- 비디오 아바타 관련 모델로 추정됨

**태그**: meituan-longcat, LongCat-Video-Avatar-1.5, Model Trending

**Metrics**: {"likes": 481, "downloads": 174, "num_parameters": 0, "pipeline_tag": ""}

### 원문 설명
likes=481, downloads=174, pipeline_tag=

---

## 4. [Introducing CodeClash, our new eval of LMs as goal (not task) oriented developers! [ Link ]](https://codeclash.ai)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
SWE-bench 팀에서 단순 작업 수행이 아닌 목표 지향적 개발자 역량을 평가하기 위한 새로운 벤치마크인 CodeClash를 공개했습니다. 이 평가는 언어 모델이 복잡한 개발 목표를 이해하고 해결할 수 있는지 측정하는 데 중점을 둡니다.

### 핵심 포인트
- 새로운 평가 프레임워크인 CodeClash 도입
- 단순 task 수행이 아닌 goal-oriented 개발자로서의 역량 평가
- LLM의 복잡한 소프트웨어 개발 문제 해결 능력 측정

**태그**: SWE-bench, CodeClash, LLM Evaluation

### 원문 설명
Introducing CodeClash, our new eval of LMs as goal (not task) oriented developers! [ Link ]

---

## 5. [mini-SWE-agent scores 65% on SWE-bench Verified in 100 lines of python code. [ Link ]](https://github.com/SWE-agent/mini-swe-agent)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
mini-SWE-agent가 SWE-bench Verified 벤치마크에서 65%의 점수를 기록했습니다. 이 모델은 단 100라인의 Python 코드로 구현되었습니다.

### 핵심 포인트
- mini-SWE-agent의 SWE-bench Verified 점수 65% 달성
- 단 100라인의 Python 코드로 구현된 효율성
- SWE-bench Verified 벤치마크 결과 보고

**태그**: mini-SWE-agent, SWE-bench, Python

### 원문 설명
mini-SWE-agent scores 65% on SWE-bench Verified in 100 lines of python code. [ Link ]

---

## 6. [SWE-smith is out! Train your own models for software engineering agents. [ Link ]](https://swesmith.com)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
소프트웨어 엔지니어링 에이전트 학습을 위한 SWE-smith가 출시되었습니다. 사용자가 직접 에이전트용 모델을 학습시킬 수 있는 환경을 제공합니다.

### 핵심 포인트
- SWE-smith 프로젝트 출시
- 소프트웨어 엔지니어링 에이전트 전용 모델 학습 지원
- 사용자 맞춤형 모델 학습 가능

**태그**: SWE-smith, Software Engineering, AI Agents

### 원문 설명
SWE-smith is out! Train your own models for software engineering agents. [ Link ]

---

## 7. [LiveCodeBench top model: O4-Mini (High)](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench에서 O4-Mini (High) 모델이 상위 성적을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 테스트를 진행했습니다.

### 핵심 포인트
- LiveCodeBench에서 O4-Mini (High) 모델이 우수한 성능을 보임
- 테스트에 사용된 문제 수는 총 4개임
- avg_pass@1 지표는 25.0을 기록함

**태그**: LiveCodeBench, O4-Mini (High), avg_pass@1

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "O4-Mini (High)"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

## 8. [LiveCodeBench top model: Gemini-2.5-Pro-06-05](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench 벤치마크에서 Gemini-2.5-Pro-06-05 모델이 상위 성적을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 avg_pass@1 25.0%의 성능을 보여주었습니다.

### 핵심 포인트
- Gemini-2.5-Pro-06-05 모델이 LiveCodeBench에서 top model로 기록됨
- 테스트에 사용된 문제 수는 총 4개임
- avg_pass@1 지표 기준 25.0%의 성능을 달성함

**태그**: LiveCodeBench, Gemini-2.5-Pro-06-05, avg_pass@1

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "Gemini-2.5-Pro-06-05"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

## 9. [LiveCodeBench top model: Gemini-2.5-Flash-04-17](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench의 최신 스냅샷 결과, Gemini-2.5-Flash-04-17 모델이 상위 성능을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 테스트를 진행했습니다.

### 핵심 포인트
- Gemini-2.5-Flash-04-17 모델이 LiveCodeBench에서 상위권을 기록함
- 테스트 결과 avg_pass@1 지표는 25.0을 달성함
- 총 4개의 문제를 대상으로 벤치마크가 수행됨

**태그**: LiveCodeBench, Gemini-2.5-Flash-04-17, benchmark_snapshot

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "Gemini-2.5-Flash-04-17"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

