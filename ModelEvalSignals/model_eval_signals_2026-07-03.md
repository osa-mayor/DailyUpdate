# Model & Eval Signals (2026-07-03)

## 오늘의 요약
Hugging Face의 대규모 및 특화 모델(OCR, GGUF) 트렌드와 함께, 소프트웨어 엔지니어링 에이전트 역량 평가를 위한 새로운 벤치마크(CodeClash, SWE-smith) 및 코딩 성능 중심의 벤치마크(LiveCodeBench) 업데이트가 주요 흐름을 형성하고 있습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 대규모 파라미터 모델(GLM-5.2) 및 특정 작업 특화 모델(OCR, GGUF)의 높은 관심
- 단순 작업 수행을 넘어 목표 지향적 개발 역량을 측정하는 새로운 에이전트 평가 체계(CodeClash, SWE-smith) 등장
- LiveCodeBench를 통한 최신 모델(Gemini 시리즈, O4-Mini)의 코딩 성능 실시간 모니터링

**오늘의 태그**: LLM_Trending, Software_Engineering_Agents, Benchmark_Update, Coding_Evaluation

## 1. [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있는 zai-org/GLM-5.2 모델입니다. 텍스트 생성(text-generation) 작업을 위한 모델로, 약 753B 규모의 파라미터를 보유하고 있습니다.

### 핵심 포인트
- zai-org/GLM-5.2 모델의 높은 관심도(likes 3,242, downloads 176,154) 확인
- 약 753B 규모의 대규모 파라미터를 가진 text-generation 모델
- Hugging Face 내 모델 트렌딩 지표 반영

**태그**: GLM-5.2, text-generation, Large Language Model

**Metrics**: {"likes": 3242, "downloads": 176154, "num_parameters": 753329940480, "pipeline_tag": "text-generation"}

### 원문 설명
likes=3242, downloads=176154, pipeline_tag=text-generation

---

## 2. [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
empero-ai에서 공개한 Qwythos-9B-Claude-Mythos-5-1M-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 9B 규모의 모델입니다.

### 핵심 포인트
- empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF 모델의 높은 인기도(downloads 1,250,562회)
- image-text-to-text 파이프라인을 지원하는 멀티모달 성격의 모델
- 약 8.95B 파라미터를 보유한 GGUF 포맷 모델

**태그**: Qwythos-9B, GGUF, image-text-to-text

**Metrics**: {"likes": 1231, "downloads": 1250562, "num_parameters": 8953803264, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1231, downloads=1250562, pipeline_tag=image-text-to-text

---

## 3. [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Baidu에서 공개한 Unlimited-OCR 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 OCR 특화 모델입니다.

### 핵심 포인트
- Baidu에서 공개한 Unlimited-OCR 모델의 높은 관심도
- 75만 회 이상의 다운로드와 1,643개의 likes 기록
- image-text-to-text 파이프라인을 활용한 OCR 작업 수행

**태그**: Baidu, Unlimited-OCR, OCR

**Metrics**: {"likes": 1643, "downloads": 758489, "num_parameters": 3336106240, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1643, downloads=758489, pipeline_tag=image-text-to-text

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

