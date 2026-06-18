# Model & Eval Signals (2026-06-19)

## 오늘의 요약
Hugging Face 내 특정 모델들의 높은 관심과 더불어, 소프트웨어 엔지니어링 에이전트의 역량을 측정하고 학습시키기 위한 새로운 벤치마크 및 도구들이 등장하며 개발 중심의 LLM 평가 트렌드가 강화되고 있습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 Gemma-4 기반 모델 및 GLM-5.2 등 텍스트 생성 모델들이 높은 다운로드와 좋아요를 기록하며 트렌드 형성
- SWE-bench 팀의 CodeClash 공개 및 SWE-smith 출시를 통해 목표 지향적 개발 에이전트 평가와 학습 환경 구축이 가속화됨
- LiveCodeBench 스냅샷 결과, Gemini-2.5 시리즈 등 특정 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁 지속

**오늘의 태그**: LLM_Trending, Software_Engineering_Agents, Benchmark_Update, Coding_LLM

## 1. [yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF 모델이 Hugging Face에서 높은 관심을 받고 있습니다. 약 21만 회 이상의 다운로드와 1,600개 이상의 좋아요를 기록하며 텍스트 생성 분야에서 주목받는 중입니다.

### 핵심 포인트
- yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF 모델의 높은 다운로드 수(211,424회) 기록
- 1,675개의 likes를 확보하며 사용자들의 높은 관심을 반영
- text-generation 파이프라인을 지원하는 12B 규모의 모델

**태그**: Gemma-4, GGUF, text-generation

**Metrics**: {"likes": 1675, "downloads": 211424, "num_parameters": 11907350576, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1675, downloads=211424, pipeline_tag=text-generation

---

## 2. [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 zai-org/GLM-5.2 모델이 텍스트 생성(text-generation) 태스크를 위해 주목받고 있습니다. 높은 다운로드 수와 좋아요 수를 기록하며 모델 트렌드에 진입했습니다.

### 핵심 포인트
- zai-org/GLM-5.2 모델의 Hugging Face 트렌딩 진입
- 4,307회의 다운로드와 1,296개의 likes를 기록하며 높은 관심을 받음
- 약 753B 파라미터를 보유한 대규모 text-generation 모델

**태그**: GLM-5.2, text-generation, HuggingFace

**Metrics**: {"likes": 1296, "downloads": 4307, "num_parameters": 753329940480, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1296, downloads=4307, pipeline_tag=text-generation

---

## 3. [WeiboAI/VibeThinker-3B](https://huggingface.co/WeiboAI/VibeThinker-3B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
WeiboAI에서 공개한 VibeThinker-3B 모델이 Hugging Face에서 주목받고 있습니다. 약 3B 파라미터 규모의 text-generation 모델로, 최근 다운로드 수가 증가하며 트렌드에 진입했습니다.

### 핵심 포인트
- WeiboAI가 공개한 3B 규모의 text-generation 모델입니다.
- 6,589회의 다운로드와 396개의 likes를 기록하며 모델 트렌드에 진입했습니다.
- 모델 파라미터 수는 약 3.08B입니다.

**태그**: WeiboAI, VibeThinker-3B, text-generation

**Metrics**: {"likes": 396, "downloads": 6589, "num_parameters": 3085938688, "pipeline_tag": "text-generation"}

### 원문 설명
likes=396, downloads=6589, pipeline_tag=text-generation

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

