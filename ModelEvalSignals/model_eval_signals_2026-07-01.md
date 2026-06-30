# Model & Eval Signals (2026-07-01)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 소프트웨어 엔지니어링 및 코딩 역량 평가를 위한 새로운 벤치마크/모델 성과가 주요 흐름을 형성하고 있습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 empero-ai의 Qwythos-9B 시리즈와 Baidu의 Unlimited-OCR 모델이 높은 관심을 받으며 다운로드 수 기록 중
- SWE-bench 팀에서 목표 지향적 개발 역량 측정을 위한 CodeClash 공개 및 에이전트 학습 환경인 SWE-smith 출시
- LiveCodeBench를 통해 Gemini 및 O4-Mini 등 주요 모델들의 코딩 성능 스냅샷 업데이트

**오늘의 태그**: LLM_Trending, Software_Engineering_Agents, Coding_Benchmark

## 1. [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 높은 다운로드 수를 기록 중인 empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF 모델에 대한 동향입니다. 이 모델은 약 9B 파라미터 규모의 image-text-to-text 파이프라인을 지원하는 GGUF 포맷 모델입니다.

### 핵심 포인트
- 모델명: empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF
- 약 97만 회 이상의 높은 다운로드 수를 기록하며 주목받고 있음
- image-text-to-text 파이프라인을 지원하는 9B 규모의 모델

**태그**: empero-ai, Qwythos-9B, GGUF

**Metrics**: {"likes": 1036, "downloads": 970663, "num_parameters": 8953803264, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1036, downloads=970663, pipeline_tag=image-text-to-text

---

## 2. [empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 높은 다운로드 수를 기록 중인 empero-ai/Qwythos-9B-Claude-Mythos-5-1M 모델에 대한 동향입니다. 약 9.4B 파라미터를 가진 text-generation 태그의 모델로, 최근 사용자들의 높은 관심을 받고 있습니다.

### 핵심 포인트
- empero-ai/Qwythos-9B-Claude-Mythos-5-1M 모델의 높은 다운로드 수(99,359회) 기록
- 약 9.4B 규모의 파라미터를 보유한 text-generation 모델
- 586개의 likes를 기록하며 모델 트렌드 형성

**태그**: empero-ai, Qwythos-9B-Claude-Mythos-5-1M, text-generation

**Metrics**: {"likes": 586, "downloads": 99359, "num_parameters": 9409813744, "pipeline_tag": "text-generation"}

### 원문 설명
likes=586, downloads=99359, pipeline_tag=text-generation

---

## 3. [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Baidu에서 공개한 Unlimited-OCR 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 OCR 특화 모델입니다.

### 핵심 포인트
- Baidu에서 공개한 Unlimited-OCR 모델의 트렌딩
- 429,056회의 높은 다운로드 수 기록
- image-text-to-text 파이프라인을 활용한 OCR 작업 수행

**태그**: Baidu, Unlimited-OCR, OCR

**Metrics**: {"likes": 1473, "downloads": 429056, "num_parameters": 3336106240, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1473, downloads=429056, pipeline_tag=image-text-to-text

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

