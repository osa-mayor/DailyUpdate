# Model & Eval Signals (2026-10-24)

## 오늘의 요약
Hugging Face의 신규 모델 공개로 인한 텍스트 생성 및 이미지 모델의 활발한 트렌드 형성 및 LiveCodeBench를 통한 코딩 성능 벤치마크 결과 확인.

### 오늘의 핵심 포인트
- Comfy-Org의 MOSS-Image 및 RecursiveSI의 flint 등 신규 모델들이 높은 다운로드와 관심을 받으며 트렌드 진입
- 4B에서 40B 규모에 이르는 다양한 파라미터 크기의 텍스트 생성 모델들이 주목받음
- LiveCodeBench 벤치마크에서 O4-Mini, Gemini 시리즈 등 상위 모델들의 코딩 성능 지표 확인

**오늘의 태그**: HuggingFace, ModelTrending, LiveCodeBench

## 1. [Comfy-Org/MOSS-Image](https://huggingface.co/Comfy-Org/MOSS-Image)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Comfy-Org에서 공개한 MOSS-Image 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 해당 모델은 약 160만 회 이상의 다운로드를 달성하며 활발한 사용성을 보여주고 있습니다.

### 핵심 포인트
- Comfy-Org에서 배포한 MOSS-Image 모델의 트렌드 확인
- 1,606,363회의 높은 downloads 기록
- 392개의 likes를 확보하며 사용자 관심을 받음

**태그**: MOSS-Image, Comfy-Org, Model Trending

**Metrics**: {"likes": 392, "downloads": 1606363, "num_parameters": 0, "pipeline_tag": ""}

### 원문 설명
likes=392, downloads=1606363, pipeline_tag=

---

## 2. [RecursiveSI/flint](https://huggingface.co/RecursiveSI/flint)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
RecursiveSI에서 공개한 flint 모델이 Hugging Face에서 주목받고 있습니다. 약 40B 파라미터 규모의 text-generation 모델로, 최근 다운로드와 좋아요 수가 증가하며 트렌드에 진입했습니다.

### 핵심 포인트
- RecursiveSI에서 공개한 40B 규모의 text-generation 모델입니다.
- likes 673회, downloads 1,904회를 기록하며 모델 트렌드에 진입했습니다.
- 약 39.8B 파라미터를 보유한 대규모 언어 모델입니다.

**태그**: RecursiveSI, flint, text-generation

**Metrics**: {"likes": 673, "downloads": 1904, "num_parameters": 39785287456, "pipeline_tag": "text-generation"}

### 원문 설명
likes=673, downloads=1904, pipeline_tag=text-generation

---

## 3. [XHToken/Spark-X2.6-4B](https://huggingface.co/XHToken/Spark-X2.6-4B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
XHToken에서 공개한 Spark-X2.6-4B 모델이 Hugging Face에서 주목받고 있습니다. 약 4.1B 파라미터를 가진 이 모델은 text-generation 태스크를 위한 모델입니다.

### 핵심 포인트
- XHToken의 Spark-X2.6-4B 모델이 Hugging Face에서 트렌딩 중입니다.
- 모델의 파라미터 규모는 약 4.1B입니다.
- 주요 활용 분야는 text-generation입니다.

**태그**: XHToken, Spark-X2.6-4B, text-generation

**Metrics**: {"likes": 408, "downloads": 1060, "num_parameters": 4112079360, "pipeline_tag": "text-generation"}

### 원문 설명
likes=408, downloads=1060, pipeline_tag=text-generation

---

## 4. [LiveCodeBench top model: O4-Mini (High)](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench 벤치마크에서 O4-Mini (High) 모델이 상위 성적을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 테스트를 진행했습니다.

### 핵심 포인트
- LiveCodeBench 벤치마크 결과 O4-Mini (High) 모델이 상위권을 기록함
- 테스트에 사용된 문제 수는 총 4개임
- avg_pass@1 지표는 25.0을 기록함

**태그**: LiveCodeBench, O4-Mini (High), benchmark_snapshot

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "O4-Mini (High)"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

## 5. [LiveCodeBench top model: Gemini-2.5-Pro-06-05](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench 벤치마크에서 Gemini-2.5-Pro-06-05 모델이 상위 성적을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 테스트를 진행했습니다.

### 핵심 포인트
- Gemini-2.5-Pro-06-05 모델이 LiveCodeBench에서 top model로 기록됨
- 테스트 결과 avg_pass@1 지표에서 25.0을 달성함
- 총 4개의 문제를 대상으로 벤치마크가 수행됨

**태그**: LiveCodeBench, Gemini-2.5-Pro-06-05, benchmark_snapshot

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "Gemini-2.5-Pro-06-05"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

## 6. [LiveCodeBench top model: Gemini-2.5-Flash-04-17](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench 벤치마크에서 Gemini-2.5-Flash-04-17 모델이 상위 성적을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 avg_pass@1 25.0%를 달성했습니다.

### 핵심 포인트
- LiveCodeBench 벤치마크 결과 Gemini-2.5-Flash-04-17 모델이 상위권을 기록함
- 4개의 문제를 대상으로 테스트가 진행됨
- avg_pass@1 지표에서 25.0%의 성능을 보임

**태그**: LiveCodeBench, Gemini-2.5-Flash-04-17, benchmark_snapshot

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "Gemini-2.5-Flash-04-17"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

