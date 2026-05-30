# Model & Eval Signals (2026-05-31)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 소프트웨어 엔지니어링 및 코딩 역량 중심의 벤치마크 업데이트가 주요 흐름을 형성하고 있습니다.

### 오늘의 핵심 포인트
- LiquidAI, NemoStation, ByteDance 등 다양한 규모와 목적(text, video-text, any-to-any)을 가진 신규 모델들이 Hugging Face에서 주목받고 있습니다.
- SWE-bench를 중심으로 단순 작업 수행을 넘어 목표 지향적 개발 역량을 평가하는 CodeClash 및 에이전트 학습 도구(SWE-smith) 등 고도화된 평가 체계가 등장했습니다.
- LiveCodeBench를 통해 O4-Mini 및 Gemini 시리즈 등 최신 모델들의 코딩 성능(pass@1) 경쟁이 지속되고 있습니다.

**오늘의 태그**: LLM_Trending, Software_Engineering_Agents, Coding_Benchmarks, Multimodal_Models

## 1. [LiquidAI/LFM2.5-8B-A1B](https://huggingface.co/LiquidAI/LFM2.5-8B-A1B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
LiquidAI에서 공개한 LFM2.5-8B-A1B 모델이 Hugging Face에서 주목받고 있습니다. 약 8.5B 파라미터를 가진 이 모델은 text-generation 태그로 분류되어 있습니다.

### 핵심 포인트
- LiquidAI에서 출시한 LFM2.5-8B-A1B 모델
- 약 8.47B 규모의 파라미터를 보유한 text-generation 모델
- 17,000회 이상의 다운로드와 257개의 likes를 기록하며 트렌딩 중

**태그**: LiquidAI, LFM2.5-8B-A1B, text-generation

**Metrics**: {"likes": 257, "downloads": 17084, "num_parameters": 8467856832, "pipeline_tag": "text-generation"}

### 원문 설명
likes=257, downloads=17084, pipeline_tag=text-generation

---

## 2. [NemoStation/Marlin-2B](https://huggingface.co/NemoStation/Marlin-2B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
NemoStation에서 공개한 Marlin-2B 모델이 최근 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 video-text-to-text 파이프라인을 지원하는 2.2B 규모의 모델입니다.

### 핵심 포인트
- NemoStation의 Marlin-2B 모델이 높은 관심도를 보임
- 약 15,780회의 다운로드와 454개의 likes를 기록
- video-text-to-text 작업을 위한 2.2B 파라미터 규모의 모델

**태그**: NemoStation, Marlin-2B, video-text-to-text

**Metrics**: {"likes": 454, "downloads": 15780, "num_parameters": 2213241664, "pipeline_tag": "video-text-to-text"}

### 원문 설명
likes=454, downloads=15780, pipeline_tag=video-text-to-text

---

## 3. [bytedance-research/Lance](https://huggingface.co/bytedance-research/Lance)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ByteDance Research에서 공개한 any-to-any 모델인 Lance가 Hugging Face에서 주목받고 있습니다. 높은 다운로드 수와 좋아요를 기록하며 새로운 멀티모달 작업 가능성을 보여주고 있습니다.

### 핵심 포인트
- ByteDance Research에서 개발한 Lance 모델 공개
- any-to-any 파이프라인 태그를 가진 모델
- likes 980회, downloads 2,856회를 기록하며 트렌딩 중

**태그**: ByteDance, Lance, any-to-any

**Metrics**: {"likes": 980, "downloads": 2856, "num_parameters": 0, "pipeline_tag": "any-to-any"}

### 원문 설명
likes=980, downloads=2856, pipeline_tag=any-to-any

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

