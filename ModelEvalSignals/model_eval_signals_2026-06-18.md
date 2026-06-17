# Model & Eval Signals (2026-06-18)

## 오늘의 요약
Hugging Face의 대규모 및 경량 모델 트렌드와 함께, 소프트웨어 엔지니어링 에이전트 역량 평가를 위한 새로운 벤치마크(CodeClash, SWE-smith) 및 코딩 성능 측정(LiveCodeBench) 중심의 기술 동향이 나타났습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 753B 규모의 GLM-5.2부터 3B 규모의 VibeThinker까지 다양한 파라미터 규모의 모델 트렌드 확인
- 단순 태스크 수행을 넘어 목표 지향적 개발 역량을 측정하는 CodeClash 및 에이전트 학습 환경인 SWE-smith 등 소프트웨어 엔지니어링 특화 평가 도구 등장
- LiveCodeBench를 통한 Gemini 및 O4-Mini 등 주요 모델의 코딩 성능(pass@1) 경쟁 및 벤치마크 스냅샷 업데이트

**오늘의 태그**: LLM, Software Engineering Agents, Benchmark, Coding Evaluation, Hugging Face

## 1. [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
zai-org에서 공개한 GLM-5.2 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 text-generation 태스크를 위한 모델로, 약 753B 규모의 파라미터를 보유하고 있습니다.

### 핵심 포인트
- zai-org에서 공개한 GLM-5.2 모델의 트렌딩
- 약 753B 규모의 대규모 파라미터 수치 확인
- text-generation 태스크를 위한 모델

**태그**: GLM-5.2, text-generation, Large Language Model

**Metrics**: {"likes": 954, "downloads": 666, "num_parameters": 753329940480, "pipeline_tag": "text-generation"}

### 원문 설명
likes=954, downloads=666, pipeline_tag=text-generation

---

## 2. [WeiboAI/VibeThinker-3B](https://huggingface.co/WeiboAI/VibeThinker-3B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
WeiboAI에서 공개한 VibeThinker-3B 모델이 Hugging Face에서 주목받고 있습니다. 약 3B 파라미터 규모의 text-generation 모델로, 최근 다운로드 수가 증가하며 트렌드에 진입했습니다.

### 핵심 포인트
- WeiboAI가 공개한 3B 규모의 text-generation 모델
- downloads 1,950회 및 likes 296회를 기록하며 트렌딩 중
- 약 3.09B의 num_parameters를 보유한 모델

**태그**: WeiboAI, VibeThinker-3B, text-generation

**Metrics**: {"likes": 296, "downloads": 1950, "num_parameters": 3085938688, "pipeline_tag": "text-generation"}

### 원문 설명
likes=296, downloads=1950, pipeline_tag=text-generation

---

## 3. [yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 높은 다운로드 수를 기록 중인 yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF 모델에 대한 동향입니다. 해당 모델은 12B 규모의 파라미터를 가진 text-generation 태그의 GGUF 포맷 모델입니다.

### 핵심 포인트
- 모델명: yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF
- 14만 건 이상의 높은 downloads와 1,427개의 likes를 기록하며 주목받고 있음
- 약 11.9B 규모의 파라미터를 가진 text-generation용 GGUF 모델

**태그**: Gemma-4, GGUF, Text-Generation

**Metrics**: {"likes": 1427, "downloads": 146784, "num_parameters": 11907350576, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1427, downloads=146784, pipeline_tag=text-generation

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

