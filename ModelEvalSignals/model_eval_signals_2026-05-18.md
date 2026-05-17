# Model & Eval Signals (2026-05-18)

## 오늘의 요약
Hugging Face를 통한 고성능 멀티모달 모델(Qwen, Sulphur)의 인기와 함께, 소프트웨어 엔지니어링 에이전트 역량 평가를 위한 새로운 벤치마크(CodeClash, SWE-smith) 및 모델 평가 리포트(METR)가 주요 흐름을 형성하고 있습니다.

### 오늘의 핵심 포인트
- Qwen 및 Sulphur 시리즈 등 멀티모달(Text-to-Video, Image-to-Text) 기능을 갖춘 모델들이 높은 관심을 받으며 배포됨
- 단순 작업 수행을 넘어 목표 지향적 개발 역량을 측정하는 CodeClash 및 에이전트 학습 환경인 SWE-smith 등 소프트웨어 엔지니어링 특화 벤치마크 등장
- METR를 통한 GPT-5, DeepSeek, Qwen 등 주요 모델에 대한 심층 평가 리포트 지속 발표

**오늘의 태그**: LLM_Trending, Software_Engineering_Agents, Benchmark_Update, Multimodal_Models

## 1. [SulphurAI/Sulphur-2-base](https://huggingface.co/SulphurAI/Sulphur-2-base)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
SulphurAI에서 공개한 Sulphur-2-base 모델이 Hugging Face에서 높은 관심을 받고 있습니다. 이 모델은 text-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Sulphur-2-base 모델의 Hugging Face 다운로드 수가 약 97만 건을 기록하며 높은 인기를 보임
- text-to-video 파이프라인 태그를 가진 모델임
- 모델 파라미터 규모는 약 8.95B임

**태그**: Sulphur-2-base, text-to-video, Hugging Face

**Metrics**: {"likes": 1067, "downloads": 970124, "num_parameters": 8953803264, "pipeline_tag": "text-to-video"}

### 원문 설명
likes=1067, downloads=970124, pipeline_tag=text-to-video

---

## 2. [unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 Qwen3.6-27B-MTP-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 27B 규모의 모델입니다.

### 핵심 포인트
- unsloth/Qwen3.6-27B-MTP-GGUF 모델의 높은 관심도 반영
- 185,303회의 다운로드와 224개의 likes 기록
- image-text-to-text 기능을 지원하는 27B 파라미터 규모의 모델

**태그**: unsloth, Qwen3.6, GGUF

**Metrics**: {"likes": 224, "downloads": 185303, "num_parameters": 27320697856, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=224, downloads=185303, pipeline_tag=image-text-to-text

---

## 3. [unsloth/Qwen3.6-35B-A3B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-35B-A3B-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 Qwen3.6-35B-A3B-MTP-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 35B 규모의 모델입니다.

### 핵심 포인트
- unsloth에서 배포한 Qwen3.6-35B-A3B-MTP-GGUF 모델
- 181,425회의 높은 downloads 기록
- image-text-to-text 파이프라인 지원

**태그**: unsloth, Qwen3.6, GGUF

**Metrics**: {"likes": 206, "downloads": 181425, "num_parameters": 35505251456, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=206, downloads=181425, pipeline_tag=image-text-to-text

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

## 5. [GPT-5.1-Codex-Max](https://metr.org/evaluations/gpt-5-1-codex-max-report/)
**Source**: METR | **Signal Type**: evaluation_report | **Category**: Evaluation Report

### 요약
2025년 11월 19일에 발표된 GPT-5.1-Codex-Max에 대한 Evaluation Report입니다. 해당 리포트는 파트너십을 통해 제공되었습니다.

### 핵심 포인트
- GPT-5.1-Codex-Max 모델에 대한 평가 보고서
- 2025년 11월 19일 기준 정보
- 파트너십을 통한 리포트 발행

**태그**: GPT-5.1-Codex-Max, Evaluation Report, METR

### 원문 설명
GPT-5.1-Codex-Max 19 November 2025 • Partnership

---

## 6. [GPT-5](https://metr.org/evaluations/gpt-5-report/)
**Source**: METR | **Signal Type**: evaluation_report | **Category**: Evaluation Report

### 요약
METR에서 발표한 GPT-5 관련 Evaluation Report입니다. 2025년 8월 7일 파트너십을 통해 공개된 정보입니다.

### 핵심 포인트
- METR의 GPT-5 관련 Evaluation Report 발표
- 2025년 8월 7일 기준 정보
- 파트너십을 통한 모델 관련 업데이트

**태그**: GPT-5, METR, Evaluation Report

### 원문 설명
GPT-5 7 August 2025 • Partnership

---

## 7. [mini-SWE-agent scores 65% on SWE-bench Verified in 100 lines of python code. [ Link ]](https://github.com/SWE-agent/mini-swe-agent)
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

## 8. [DeepSeek and Qwen](https://metr.org/evaluations/deepseek-qwen-report/)
**Source**: METR | **Signal Type**: evaluation_report | **Category**: Evaluation Report

### 요약
METR에서 발표한 DeepSeek와 Qwen 모델에 대한 Evaluation Report입니다. 해당 보고서는 특정 기업의 개입 없이 작성되었습니다.

### 핵심 포인트
- DeepSeek 및 Qwen 모델에 대한 평가 보고서
- 2025년 6월 27일 발행
- 기업의 개입이 없는 독립적인 평가 결과

**태그**: DeepSeek, Qwen, METR

### 원문 설명
DeepSeek and Qwen 27 June 2025 • No company involvement

---

## 9. [SWE-smith is out! Train your own models for software engineering agents. [ Link ]](https://swesmith.com)
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

## 10. [LiveCodeBench top model: O4-Mini (High)](https://livecodebench.github.io/leaderboard.html)
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

## 11. [LiveCodeBench top model: Gemini-2.5-Pro-06-05](https://livecodebench.github.io/leaderboard.html)
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

## 12. [LiveCodeBench top model: Gemini-2.5-Flash-04-17](https://livecodebench.github.io/leaderboard.html)
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

