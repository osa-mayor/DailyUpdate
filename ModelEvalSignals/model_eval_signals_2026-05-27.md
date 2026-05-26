# Model & Eval Signals (2026-05-27)

## 오늘의 요약
Hugging Face의 신규 멀티모달 및 경량 모델 출시와 더불어, 소프트웨어 엔지니어링 에이전트 역량 및 코딩 능력을 측정하는 새로운 벤치마크/평가 지표들이 주목받고 있습니다.

### 오늘의 핵심 포인트
- ByteDance의 any-to-any 모델 Lance 및 OpenBMB의 경량 모델 MiniCPM5-1B 등 새로운 모델 트렌드 확인
- 목표 지향적 개발 역량 평가를 위한 CodeClash 및 에이전트 학습 환경 SWE-smith 등 소프트웨어 엔지니어링 특화 벤치마크 등장
- LiveCodeBench를 통한 주요 모델(Gemini 시리즈 등)의 코딩 성능 스냅샷 업데이트

**오늘의 태그**: Multimodal, LLM-Agents, Software-Engineering-Benchmark, Coding-Evaluation

## 1. [bytedance-research/Lance](https://huggingface.co/bytedance-research/Lance)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ByteDance Research에서 공개한 any-to-any 모델인 Lance가 Hugging Face에서 주목받고 있습니다. 높은 다운로드 수와 좋아요를 기록하며 새로운 멀티모달 작업 가능성을 보여주고 있습니다.

### 핵심 포인트
- ByteDance Research에서 개발한 Lance 모델이 Hugging Face 트렌딩에 진입했습니다.
- any-to-any 파이프라인 태그를 가진 모델로 다양한 모달리티 간 작업이 가능함을 시사합니다.
- 현재 1,908회의 다운로드와 853개의 좋아요를 기록하며 사용자 관심을 끌고 있습니다.

**태그**: ByteDance, Lance, any-to-any

**Metrics**: {"likes": 853, "downloads": 1908, "num_parameters": 0, "pipeline_tag": "any-to-any"}

### 원문 설명
likes=853, downloads=1908, pipeline_tag=any-to-any

---

## 2. [openbmb/MiniCPM5-1B](https://huggingface.co/openbmb/MiniCPM5-1B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenBMB에서 공개한 1B 규모의 text-generation 모델인 MiniCPM5-1B가 Hugging Face에서 주목받고 있습니다. 약 10.8억 개의 파라미터를 가진 경량 모델로, 최근 다운로드 수가 증가하며 트렌딩 모델로 진입했습니다.

### 핵심 포인트
- OpenBMB의 1B 규모 경량 text-generation 모델
- 약 1.08B(1,080,632,832) 파라미터 규모
- 최근 2,400회 이상의 다운로드와 294개의 likes를 기록하며 트렌딩 중

**태그**: MiniCPM5-1B, OpenBMB, text-generation

**Metrics**: {"likes": 294, "downloads": 2409, "num_parameters": 1080632832, "pipeline_tag": "text-generation"}

### 원문 설명
likes=294, downloads=2409, pipeline_tag=text-generation

---

## 3. [meituan-longcat/LongCat-Video-Avatar-1.5](https://huggingface.co/meituan-longcat/LongCat-Video-Avatar-1.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
meituan-longcat에서 공개한 LongCat-Video-Avatar-1.5 모델이 Hugging Face에서 주목받고 있습니다. 현재 289개의 likes를 기록하며 사용자들의 관심을 끌고 있습니다.

### 핵심 포인트
- meituan-longcat에서 출시한 LongCat-Video-Avatar-1.5 모델
- Hugging Face 내 289개의 likes를 기록하며 트렌딩 중
- 현재 다운로드 수 및 파라미터 정보는 제공되지 않음

**태그**: LongCat-Video-Avatar-1.5, meituan-longcat, Model Trending

**Metrics**: {"likes": 289, "downloads": 0, "num_parameters": 0, "pipeline_tag": ""}

### 원문 설명
likes=289, downloads=0, pipeline_tag=

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

