# Model & Eval Signals (2026-06-08)

## 오늘의 요약
Hugging Face의 신규 모델 공개와 함께 소프트웨어 엔지니어링 및 코딩 역량 평가를 위한 새로운 벤치마크와 에이전트 학습 도구들이 주목받고 있습니다.

### 오늘의 핵심 포인트
- LiquidAI, unsloth, ideogram-ai 등 다양한 도메인(텍스트 생성, 멀티모달, 이미지 생성)의 신규 모델이 Hugging Face에서 높은 관심을 받음
- SWE-bench 팀의 CodeClash 공개 및 mini-SWE-agent의 성과 등 목표 지향적 개발 역량 평가와 에이전트 학습 환경이 강화됨
- LiveCodeBench를 통해 O4-Mini 및 Gemini 시리즈 등 최신 모델들의 코딩 성능 스냅샷이 업데이트됨

**오늘의 태그**: LLM, Benchmark, AI Agents, Software Engineering, Coding

## 1. [LiquidAI/LFM2.5-8B-A1B](https://huggingface.co/LiquidAI/LFM2.5-8B-A1B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
LiquidAI에서 공개한 LFM2.5-8B-A1B 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 8.5B 파라미터를 가진 이 모델은 text-generation 태스크를 위한 모델입니다.

### 핵심 포인트
- LiquidAI의 LFM2.5-8B-A1B 모델이 높은 관심을 받고 있음
- 약 8.47B 규모의 파라미터를 보유한 text-generation 모델
- 11만 건 이상의 높은 다운로드 수를 기록 중

**태그**: LiquidAI, LFM2.5-8B-A1B, text-generation

**Metrics**: {"likes": 539, "downloads": 118326, "num_parameters": 8467856832, "pipeline_tag": "text-generation"}

### 원문 설명
likes=539, downloads=118326, pipeline_tag=text-generation

---

## 2. [unsloth/gemma-4-12b-it-GGUF](https://huggingface.co/unsloth/gemma-4-12b-it-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 gemma-4-12b-it-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 12B 규모의 모델입니다.

### 핵심 포인트
- unsloth/gemma-4-12b-it-GGUF 모델의 높은 다운로드 수(568,158회) 기록
- image-text-to-text 기능을 지원하는 멀티모달 성격의 모델
- 약 11.9B 파라미터를 보유한 GGUF 포맷 모델

**태그**: unsloth, gemma-4-12b-it-GGUF, image-text-to-text

**Metrics**: {"likes": 442, "downloads": 568158, "num_parameters": 11907350576, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=442, downloads=568158, pipeline_tag=image-text-to-text

---

## 3. [ideogram-ai/ideogram-4-nf4](https://huggingface.co/ideogram-ai/ideogram-4-nf4)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ideogram-ai에서 공개한 text-to-image 모델인 ideogram-4-nf4가 Hugging Face에서 주목받고 있습니다. 해당 모델은 텍스트를 이미지로 생성하는 파이프라인을 지원합니다.

### 핵심 포인트
- ideogram-ai/ideogram-4-nf4 모델의 Hugging Face 트렌딩 발생
- 3,844회의 downloads와 229개의 likes를 기록하며 높은 관심을 받음
- text-to-image 태스크를 위한 모델임

**태그**: ideogram-4-nf4, text-to-image, HuggingFace

**Metrics**: {"likes": 229, "downloads": 3844, "num_parameters": 0, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=229, downloads=3844, pipeline_tag=text-to-image

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

