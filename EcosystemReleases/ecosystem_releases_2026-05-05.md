# Ecosystem Releases (2026-05-05)

## 오늘의 요약
오늘의 릴리즈는 llama.cpp, vLLM, TensorRT-LLM 등 주요 추론 엔진의 성능 최적화와 안정성 개선에 집중되었으며, 모델 평가 방식의 변화와 IBM Granite 모델의 설계 전략 등 AI 모델 신뢰성 확보를 위한 흐름이 관찰되었습니다.

### 오늘의 핵심 포인트
- 주요 추론 엔진(llama.cpp, vLLM, TensorRT-LLM, SGLang)의 버전 업데이트를 통한 메모리 최적화, 버그 수정 및 특정 모델(DeepSeek 등) 지원 강화
- 모델 성능 상향 평준화에 따라 단순 벤치마크를 넘어 신뢰성과 안전성을 검증하는 'AI evals'가 핵심 과제로 부상
- IBM Granite 4.1 등 고품질 데이터 관리와 학습 전략을 통한 신뢰할 수 있는 LLM 구축 방식 공유

**오늘의 태그**: LLM Inference, Model Optimization, AI Evaluation, Open Source AI

## 1. [b9030](https://github.com/ggml-org/llama.cpp/releases/tag/b9030)
**Source**: llama.cpp Releases | **Category**: GitHub Release | **Release Type**: github_release

### 요약
llama.cpp의 b9030 릴리즈에서는 cpp-httplib 라이브러리가 0.43.3 버전으로 업데이트되었습니다. 또한 macOS, Linux, Android, Windows, openEuler 등 다양한 플랫폼과 아키텍처를 지원하는 빌드 결과물이 포함되었습니다.

### 핵심 포인트
- vendor: cpp-httplib를 0.43.3 버전으로 업데이트
- macOS/iOS, Linux, Android, Windows, openEuler 등 광범위한 OS 및 아키텍처 지원
- CUDA, Vulkan, SYCL, ROCm, OpenVINO 등 다양한 가속 프레임워크를 포함한 빌드 제공

**태그**: llama.cpp, Update, Multi-platform

### 원문 설명
vendor : update cpp-httplib to 0.43.3 ( #22686 ) 
 
  macOS/iOS:  
 
  macOS Apple Silicon (arm64)  
  macOS Apple Silicon (arm64, KleidiAI enabled)  
  macOS Intel (x64)  
  iOS XCFramework  
 
  Linux:  
 
  Ubuntu x64 (CPU)  
  Ubuntu arm64 (CPU)  
  Ubuntu s390x (CPU)  
  Ubuntu x64 (Vulkan)  
  Ubuntu arm64 (Vulkan)  
  Ubuntu x64 (ROCm 7.2)  
  Ubuntu x64 (OpenVINO)  
  Ubuntu x64 (SYCL FP32)  
  Ubuntu x64 (SYCL FP16)  
 
  Android:  
 
  Android arm64 (CPU)  
 
  Windows:  
 
  Windows x64 (CPU)  
  Windows arm64 (CPU)  
  Windows x64 (CUDA 12)  -  CUDA 12.4 DLLs  
  Windows x64 (CUDA 13)  -  CUDA 13.1 DLLs  
  Windows x64 (Vulkan)  
  Windows x64 (SYCL)  
  Windows x64 (HIP)  
 
  openEuler:  
 
  openEuler x86 (310p)  
  openEuler x86 (910b, ACL Graph)  
  openEuler aarch64 (310p)  
  openEuler aarch64 (910b, ACL Graph)

---

## 2. [v0.5.11](https://github.com/sgl-project/sglang/releases/tag/v0.5.11)
**Source**: SGLang Releases | **Category**: GitHub Release | **Release Type**: github_release

### 요약
SGLang의 v0.5.11 릴리스입니다. 이번 버전은 시스템 안정성 및 성능 개선을 포함한 업데이트를 담고 있습니다.

### 핵심 포인트
- SGLang v0.5.11 버전 릴리스
- 시스템 안정성 및 버그 수정

**태그**: SGLang, GitHub Release, LLM Inference

### 원문 설명
Release v0.5.11

---

## 3. [b9028](https://github.com/ggml-org/llama.cpp/releases/tag/b9028)
**Source**: llama.cpp Releases | **Category**: GitHub Release | **Release Type**: github_release

### 요약
llama.cpp의 b9028 릴리즈에서는 디바이스 버퍼의 메모리 사용량을 절약할 수 있는 새로운 옵션이 추가되었습니다. 또한 테스트 케이스 확장 및 다양한 OS와 하드웨어 가속 환경을 지원하는 빌드가 제공됩니다.

### 핵심 포인트
- llama: 디바이스 버퍼 메모리 절약을 위한 옵션 추가
- tests: llama-save-load-state 테스트 범위 확장
- macOS, Linux, Android, Windows, openEuler 등 다양한 플랫폼 및 가속 라이브러리(CUDA, Vulkan, ROCm, OpenVINO 등) 지원

**태그**: llama.cpp, Memory Optimization, Inference

### 원문 설명
llama : add option to save memory in device buffers ( #22679 ) 
 
 
 llama : add option to save memory in device buffers 
 
 
 tests : extend llama-save-load-state 
 
 
 
  macOS/iOS:  
 
  macOS Apple Silicon (arm64)  
  macOS Apple Silicon (arm64, KleidiAI enabled)  
  macOS Intel (x64)  
  iOS XCFramework  
 
  Linux:  
 
  Ubuntu x64 (CPU)  
  Ubuntu arm64 (CPU)  
  Ubuntu s390x (CPU)  
  Ubuntu x64 (Vulkan)  
  Ubuntu arm64 (Vulkan)  
  Ubuntu x64 (ROCm 7.2)  
  Ubuntu x64 (OpenVINO)  
  Ubuntu x64 (SYCL FP32)  
  Ubuntu x64 (SYCL FP16)  
 
  Android:  
 
  Android arm64 (CPU)  
 
  Windows:  
 
  Windows x64 (CPU)  
  Windows arm64 (CPU)  
  Windows x64 (CUDA 12)  -  CUDA 12.4 DLLs  
  Windows x64 (CUDA 13)  -  CUDA 13.1 DLLs  
  Windows x64 (Vulkan)  
  Windows x64 (SYCL)  
  Windows x64 (HIP)  
 
  openEuler:  
 
  openEuler x86 (310p)  
  openEuler x86 (910b, ACL Graph)  
  openEuler aarch64 (310p)  
  openEuler aarch64 (910b, ACL Graph)

---

## 4. [v0.20.1](https://github.com/vllm-project/vllm/releases/tag/v0.20.1)
**Source**: vLLM Releases | **Category**: GitHub Release | **Release Type**: github_release

### 요약
vLLM v0.20.1은 v0.20.0을 기반으로 한 패치 릴리스로, DeepSeek V4 모델의 안정화와 성능 향상에 중점을 두었습니다. 또한 다양한 버그 수정과 커널 최적화를 통해 추론 효율성을 개선했습니다.

### 핵심 포인트
- DeepSeek V4 모델 지원 및 성능 최적화 (Multi-stream pre-attention GEMM, 통합 타일 커널 등)
- FlashInfer를 위한 BF16 및 MXFP8 all-to-all 지원 및 FP32-to-FP4 변환 속도 개선
- CUDA graph, 메모리 관리, MoE 관련 버그 및 런타임 오류 수정

**태그**: vLLM, DeepSeek V4, LLM Inference

### 원문 설명
vLLM v0.20.1 
 This is a patch release on top of  v0.20.0  primarily focused on  DeepSeek V4 stabilization and performance improvements , along with several important bug fixes. 
 DeepSeek V4 
 
 Base model support ( #41006 ). 
 Multi-stream pre-attention GEMM ( #41061 ), configurable pre-attn GEMM knob ( #41443 ), and tuned default  VLLM_MULTI_STREAM_GEMM_TOKEN_THRESHOLD  ( #41526 ). 
 BF16 and MXFP8 all-to-all support for FlashInfer one-sided communication ( #40960 ). 
 PTX  cvt  instruction for faster FP32-&gt;FP4 conversion ( #41015 ). 
 Integrated tile kernels ( head_compute_mix_kernel ) for optimized head computation ( #41255 ). 
 Guard megamoe flag with Pure TP ( #41522 ). 
 Fixed persistent topk cooperative deadlock at TopK=1024 ( #41189 ) and inter-CTA init race on RadixRowState ( #41444 ), with temporary disable of persistent topk as a workaround ( #41442 ). 
 Fixed import error due to AOT compile cache loading ( #41090 ). 
 Fixed torch inductor error ( #41135 ). 
 Fixed repeated RoPE cache initialization ( #41148 ). 
 Fixed missing type conversion for non-streaming tool calls in DSV3.2/V4 ( #41198 ). 
 
 Bug Fixes 
 
 Fixed  max_num_batched_token  not being captured in CUDA graph ( #40734 ). 
 Fixed  num_gpu_blocks_override  not accounted for in  max_model_len  checks ( #41069 ). 
 Auto-disable  expandable_segments  around cumem memory pool ( #40812 ). 
 Fixed BailingMoE linear layer ( #40859 ) and MLA RoPE rotation for BailingMoE V2.5 ( #41185 ). 
 Fixed reasoning parser kwargs not being passed to structured output ( #41199 ). 
 [ROCm] Fixed  input_ids  and  expert_map  args for Quark W4A8 GPT-OSS ( #41165 ). 
 
 List of contributors 
  @BugenZhao ,  @chaunceyjiang ,  @gau-nernst ,  @ghphotoframe ,  @Isotr0py ,  @jeejeelee ,  @khluu ,  @njhill ,  @Rohan138 ,  @wzhao18 ,  @youkaichao ,  @ywang96 ,  @ZJY0516 ,  @zixi-qi ,  @zyongye

---

## 5. [v0.20.2rc0: [MRV2] Add shutdown() method (#41297)](https://github.com/vllm-project/vllm/releases/tag/v0.20.2rc0)
**Source**: vLLM Releases | **Category**: GitHub Release | **Release Type**: github_release

### 요약
vLLM v0.20.2rc0 릴리즈에서는 shutdown() 메서드가 새롭게 추가되었습니다. 이번 업데이트는 MRV2 관련 작업의 일환으로 진행되었습니다.

### 핵심 포인트
- shutdown() 메서드 추가
- MRV2 관련 기능 업데이트
- v0.20.2rc0 릴리즈 버전 반영

**태그**: vLLM, Release, Python

### 원문 설명
Signed-off-by: Woosuk Kwon  woosuk@inferact.ai

---

## 6. [AI evals are becoming the new compute bottleneck](https://huggingface.co/blog/evaleval/eval-costs-bottleneck)
**Source**: Hugging Face Blog | **Category**: Blog Release | **Release Type**: ecosystem_blog

### 요약
AI 모델의 성능이 상향 평준화됨에 따라 기존의 벤치마크가 모델의 차이를 식별하는 데 한계를 보이고 있습니다. 이제는 단순한 성능 측정을 넘어 모델의 신뢰성과 안전성을 검증하는 AI evals가 새로운 병목 구간이자 핵심 과제로 떠오르고 있습니다.

### 핵심 포인트
- 기존 벤치마크의 한계로 인해 모델 간 변별력이 낮아지는 현상 발생
- 모델의 성능 향상 속도에 맞춰 평가 방법론의 혁신이 필요함
- AI evals가 모델 개발 및 배포 과정에서의 새로운 병목 지점으로 부상

**태그**: AI Evals, Benchmark, Hugging Face

---

## 7. [Granite 4.1 LLMs: How They’re Built](https://huggingface.co/blog/ibm-granite/granite-4-1)
**Source**: Hugging Face Blog | **Category**: Blog Release | **Release Type**: ecosystem_blog

### 요약
IBM이 새롭게 공개한 Granite 4.1 LLM 시리즈의 설계 방식과 구축 과정을 상세히 설명하는 블로그 포스트입니다. 데이터 품질 관리와 모델 학습 전략을 통해 어떻게 신뢰할 수 있는 모델을 만들었는지 다룹니다.

### 핵심 포인트
- Granite 4.1 LLM의 아키텍처 및 구축 방법론 소개
- 모델 성능을 결정짓는 데이터 정제 및 학습 프로세스 설명
- 신뢰성과 효율성을 갖춘 오픈 모델 개발 전략 공유

**태그**: Granite 4.1, LLM, IBM

---

## 8. [v1.3.0rc13](https://github.com/NVIDIA/TensorRT-LLM/releases/tag/v1.3.0rc13)
**Source**: TensorRT-LLM Releases | **Category**: GitHub Release | **Release Type**: github_release

### 요약
TensorRT-LLM v1.3.0rc13 릴리즈는 Nemotron 3 Nano Omni 및 DeepSeek-V3 시리즈에 대한 모델 지원 최적화와 멀티모달 기능 강화를 중점적으로 다룹니다. 또한, 커널 최적화, 분산 서빙(Disaggregated serving) 안정성 개선 및 다양한 런타임 버그 수정을 통해 추론 성능과 신뢰성을 높였습니다.

### 핵심 포인트
- Nemotron 3 Nano Omni 및 DeepSeek-V3/V3-Lite 모델 지원과 Blackwell/SM100 GPU를 위한 성능 최적화
- VisualGen을 위한 Cache-DiT 및 통합 캐시 가속기 도입, Sparse MQA/GQA 어텐션 지원 등 새로운 기능 추가
- KV 캐시 관리, 스케줄러 정확성, 멀티모달 데이터 처리 및 분산 서빙 관련 다양한 런타임 버그 수정

**태그**: TensorRT-LLM, DeepSeek, Nemotron, LLM-Inference, GPU-Optimization

### 원문 설명
Highlights 
 
 
 Model Support 
 
 Support and initial optimizations for Nemotron 3 Nano Omni; known issues for audio-from-video and chunked prefill for video being actively worked on 
 Add audio extraction from video, optimize ViT attention, and reduce initialization memory for Nemotron and Nemotron Nano VL models ( #12921 ,  #12911 ,  #13283 ) 
 Add per-model VisualGen example scripts, shared configs, per-model defaults, and metadata updates ( #12992 ,  #12862 ) 
 Add GLM-4.7 and GLM-5 tool parser support ( #13150 ) 
 Optimize Nemotron-H execution from the Python layer and preserve Nemotron HF mamba cache dtype during bench tuning ( #13032 ,  #12826 ) 
 Improve DeepSeek-V3.2 and DeepSeek-V3-Lite support with targeted perf and chunked-prefill fixes on Blackwell and SM100-class GPUs ( #13142 ,  #13257 ) 
 
 
 
 API 
 
 Fix the chunked prefill API contract for Nemotron Nano VL ( #13025 ) 
 Add abort and resume support for Async RL in verl ( #12272 ) 
 Add a modular logger with automatic module detection and per-module filtering ( #13202 ) 
 Improve prompt handling by accounting for existing multimodal placeholder tokens in text prompts ( #12827 ) 
 Propagate real server-side failures to disaggregated serving clients and improve empty-file handling in trtllm-bench ( #13119 ,  #12552 ) 
 
 
 
 Feature 
 
 Add VisualGen Cache-DiT and a unified cache accelerator ( #12548 ) 
 Expand kernel support with broader RMSNorm coverage, optimized causal-conv1d prefill and decode, FP4 residual quantization, and refreshed SageAttention kernels ( #13033 ,  #13103 ,  #13117 ,  #12937 ) 
 Add batched addSequence with two-phase claim and unified VSWA and non-reuse support ( #13029 ) 
 Add sparse MQA and GQA attention support and introduce new sharding infrastructure ( #12470 ,  #12419 ) 
 Improve serving performance with async media loading, faster video frame decoding, cached text computation reuse, lower custom-op overhead, padding-aware CUDA graph tuning, and reduced single-rank broadcast overhead ( #13034 ,  #12677 ,  #13149 ,  #12895 ,  #13412 ,  #13259 ,  #11640 ) 
 Optimize runtime internals with Minimax RMSNorm tuning, consolidated prefix-reuse analysis, gen-only sync transfer v2, DWDP contention config cleanup, and round-robin CP cache transmission ( #12163 ,  #13095 ,  #12882 ,  #12974 ,  #13180 ) 
 Restore EAGLE3 dynamic-tree speculative decoding support and centralize perfect-router integration and validation ( #13081 ,  #13250 ) 
 
 
 
 Fix 
 
 Fix KV cache and scheduler correctness issues, including SWA compatibility, token accounting with context chunking, over-allocation in VSWA plus EAGLE flows, KVCacheManagerV2 bugs, and multimodal and disaggregated cache reuse problems ( #12968 ,  #12976 ,  #12855 ,  #12306 ,  #13104 ,  #12472 ) 
 Fix runtime stability issues by preventing benchmark fill-loop hangs, tightening warmup reservation behavior, and making host-memory-based prefetch decisions consistent across ranks ( #13065 ,  #13078 ,  #13161 ) 
 Fix EAGLE3 LoRA speculative decoding and preserve speculative layer weights to avoid MTP plus PP hangs ( #13005 ,  #12555 ) 
 Fix FMHA and attention runtime issues, including SM90 full-mask skip-softmax dispatch, misleading generation warnings, stale CUDA graphs on beam-width changes, and FlashInfer KV layout handling ( #13120 ,  #13157 ,  #13255 ,  #13190 ) 
 Fix vision and multimodal correctness issues, including KV-cache quantization leaks into the vision encoder, FLUX high-resolution scheduler off-by-one behavior, and Super V3 multi-stream MoE instability ( #13181 ,  #13091 ,  #13122 ) 
 Fix packaging and environment issues by restoring the missing aarch64 library, enforcing NCCL &gt;= 2.28 at configure time, and using weights_only=True in LoRA manager loads ( #13206 ,  #13108 ,  #13391 ) 
 Fix operational reliability issues in CI and perf pipelines, including OpenSearch upload failures, hanging AIPerf metrics, SLURM host name propagation, and SLURM submission retry behavior ( #13215 ,  #13314 ,  #13367 ,  #12778 ) 
 Fix additional model and runtime issues for Qwen3 mrope cache handling, DSA illegal memory access with CUDA graph plus host KV offload, stale tokenizer alias imports, and WAN example timing conflicts ( #13269 ,  #13124 ,  #13086 ,  #13193 ,  #12128 ) 
 
 
 
 Documentation 
 
 Restructure installation documentation and refresh verbose comments ( #12402 ,  #13387 ) 
 Update invalid Dynamo documentation URLs ( #13038 ) 
 
 
 
 Test &amp; Infra 
 
 Add Dynamo API compatibility tests, VisualGen regression coverage, and refactor MoE communication tests ( #12970 ,  #13372 ,  #12841 ) 
 Expand CI coverage for disaggregated serving and weekly performance suites, including K2.5 EPLB coverage, refreshed Nemotron datasets, and additional weekly perf models ( #13185 ,  #12982 ,  #13325 ) 
 Improve CI signal quality by splitting multimodal DGX_B200 jobs, removing obsolete or low-priority cases, dropping non-key-model L0 coverage, and moving bf16 and auto precision variants to post-merge ( #12978 ,  #13262 ,  #13374 ,  #13315 ,  #13366 ) 
 Improve CI tooling with PR-aware failure analysis, SwiftStack upload support, wildcard bot stage commands, a sync_qa_tests Jenkins script, doc tests, and markdown-only doc-build rules ( #12849 ,  #13291 ,  #12881 ,  #13028 ,  #13152 ,  #13358 ,  #13441 ) 
 Refresh repository ownership and security plumbing with CODEOWNERS updates, HMAC key enforcement, and container vulnerability fixes ( #13110 ,  #13213 ,  #9850 ,  #13447 ) 
 
 
 
 What's Changed 
 
 [https://nvbugs/5997092][fix] Remove waives for DS-V3.2/R1 FP4 Blackkwell perf tests by  @peihu-nv  in  #13042  
 [None][infra] Waive 2 failed cases for main in post-merge by  @xinhe-nv  in  #13105  
 [TRTLLM-9132][infra] Update to ignore failure for release check and building images by  @EmmaQiaoCh  in  #9871  
 [https://nvbugs/5626259][fix] Enable nemotron-h chunk prefill test by  @Wanli-Jiang  in  #12980  
 [None][feat] Add the invocation path for mamba2 mtp custom op by  @JadoTu  in  #12787  
 [None][infra] Waive 4 failed cases for main in post-merge 2654 by  @ZhanruiSunCh  in  #13113  
 [None][infra] Waive 3 failed cases for main in post-merge 2658 by  @ZhanruiSunCh  in  #13141  
 [None][chore] Add CODEOWNERS mappings for  @NVIDIA/trt-llm-multimodal-devs  by  @venkywonka  in  #13110  
 [None][chore] Add disaggregated tests that timeout to waives.txt by  @2ez4bz  in  #13136  
 [https://nvbugs/5844149][fix] Fix issues with DSV3.2 perf tests by  @chenfeiz0326  in  #13142  
 [None][fix] Fix a capacity issue in KVCacheManagerV2 for SWA compatibility by  @heyuhhh  in  #12968  
 [https://nvbugs/6044213][chore] unwaive and reduce free mem ratio in AutoDeploy's perf test: deepseek_r1_distill_qwen_32b by  @MrGeva  in  #12965  
 [None][fix] Fix chunked prefill API contract for nemotron nano VL by  @2ez4bz  in  #13025  
 [TRTLLM-11794][feat] Optimize ViT Attention kernel on Nemotron by  @yechank-nvidia  in  #12911  
 [TRTLLMINF-38][feat] Pass PR number to CI failure analysis agent by  @dpitman-nvda  in  #12849  
 [https://nvbugs/6074784][chore] Temp waive dis-agg transformers failed tests by  @Shixiaowei02  in  #13145  
 [None][fix] Fix scheduler off-by-one in FLUX pipelines at high resolutions by  @karljang  in  #13091  
 [None][infra] Add 5 users to blossom-ci allowlist by  @yuanjingx87  in  #13146  
 [TRTLLM-11403][feat] VisualGen Cache-DiT + unified cache accelerator by  @o-stoner  in  #12548  
 [None][fix] Enable LoRA in EAGLE3 speculative decoding by  @Funatiq  in  #13005  
 [TRTLLM-11903][test] Add API compatibility tests for dynamo by  @brb-nv  in  #12970  
 [None][feat] Update rms_norm + fp4_qaunt kernel supporting more dim by  @Wanli-Jiang  in  #13033  
 [None][chore] Bump version to 1.3.0rc13 by  @VALLIS-NERIA  in  #13159  
 [None][fix] Fix compute token accounting for KV cache reuse with context chunking by  @lancelly  in  #12976  
 [None][feat] Batch addSequence with two-phase claim and unified VSWA/non-reuse support by  @liji-nv  in  #13029  
 [None][bug] fix SM90 full-mask skip-softmax dispatch by  @bobboli  in  #13120  
 [None][test] Refactor MoE comm tests: unified dispatch+combine pipeline by  @xxi-nv  in  #12841  
 [https://nvbugs/5983320][fix] Use encoder_max_batch_size of 1 for LLaVa in test_multi_request_batch_chat by  @moraxu  in  #12647  
 [TRTLLM-11771][feat] Add audio extraction from video for Nemotron Nano VL by  @2ez4bz  in  #12921  
 [None][fix] Update stale TOKENIZER_ALIASES import path in serve and bench modules by  @cascade812  in  #13086  
 [TRTLLM-11695][feat] Add per-model VisualGen example scripts, shared configs, and per-model defaults by  @zhenhuaw-me  in  #12992  
 [https://nvbugs/6060119][chore] Unwaive DSR1 FP4 128k8k disagg perf tests by  @peihu-nv  in  #13088  
 [None][feat] Support sparse mqa/gqa attention by  @heyuhhh  in  #12470  
 [None][fix] Support custom_tokenizer in KvCacheAwareRouter for disagg serving by  @lishicheng1996-nv  in  #12990  
 [https://nvbugs/6013562][fix] fix kv cache allocation is double the budget for vswa + eagle by  @dongfengy  in  #12855  
 [None][test] Waive 1 failed cases for main in QA CI by  @xinhe-nv  in  #13147  
 [https://nvbugs/6013562][fix] Unwaive tests since the fix has been merged by  @dongfengy  in  #13183  
 [None][chore] Add Dynamo configs to TRTLLM CI - Disagg - Part 1 by  @brb-nv  in  #13167  
 [None][feat] Minimax RMS norm optimization by  @jmydurant  in  #12163  
 [TRTLLM-11878][feat] Gen-only sync transfer v2 and manager v2 by  @Shixiaowei02  in  #12882  
 [None][test] Remove triton_server test_opt by  @Tabrizian  in  #13173  
 [None][infra] Waive 3 failed cases for main in post-merge by  @xinhe-nv  in  #13194  
 [None][feat] Optimize nemotron-h from python level by  @Wanli-Jiang  in  #13032  
 [https://nvbugs/6026676][fix] Only waive the tests for H20 so that H100 still covered by  @dongfengy  in  #12961  
 [TRTLLM-11272][fix] Account for the existing multimodal placeholder tokens in a text prompt by  @moraxu  in  #12827  
 [None][infra] Waive 20 failed cases for main in post-merge by  @xinhe-nv  in  #13203  
 [None][fix] Fix GPQA Diamond filter_type mismatch in disagg accuracy … by  @yingguo-trt  in  #13210  
 [None][infra] Waive 9 failed cases for main in post-merge by  @xinhe-nv  in  #13204  
 [None][infra] Waive 6 failed cases for main in post-merge by  @xinhe-nv  in  #13195  
 [None][test] Add doc test by  @StanleySun639  in  #13152  
 [https://nvbugs/6071070][fix] Add K2.5 DISAGG Gen Only EPLB Cases into CI by  @chenfeiz0326  in  #13185  
 [None][infra] Waive 2 failed cases for main in post-merge 2663 by  @ZhanruiSunCh  in  #13216  
 [TRTLLM-12291][feat] New sharding infrastructure by  @greg-kwasniewski1  in  #12419  
 [None] [chore] Update .github/CODEOWNERS by  @kaiyux  in  #13213  
 [None][test] Fix DGX_B200 CI timeout by splitting multimodal tests an… by  @nv-guomingz  in  #12978  
 [None][infra] Waive 2 failed cases for main in pre-merge 34569 by  @ZhanruiSunCh  in  #13192  
 [None][fix] Test time conflict in WAN T2V example by  @2ez4bz  in  #13193  
 [None][infra] Reenable GB300-4_GPUs-PyTorch-Post-Merge-1 by  @mlefeb01  in  #13097  
 [TRTLLM-11872][perf] Multi-threading async media loading and optimizing video frame decoding in trtllm-serve by  @yechank-nvidia  in  #13034  
 [None][fix] Do not leak KV cache quantization into vision encoder by  @2ez4bz  in  #13181  
 [https://nvbugs/5783876][chore] Enforce HMAC key requirement in the codebase by  @yibinl-nvidia  in  #9850  
 [https://nvbugs/5981122][fix] Unwaive DeepSeekV3Lite python_scheduler test by  @lancelly  in  #12972  
 [None][infra] Waive 3 failed cases for main in post-merge by  @xinhe-nv  in  #13200  
 [None][infra] Waive 1 failed cases for main in pre-merge 34820 by  @ZhanruiSunCh  in  #13252  
 [None][infra] Waive 8 failed cases for main in post-merge by  @xinhe-nv  in  #13201  
 [None][test] waive hang issues by  @xinhe-nv  in  #13212  
 [https://nvbugs/6086538][fix] suppress misleading skip-softmax FMHA warning in generation by  @bobboli  in  #13157  
 [None][fix] Add missing aarch64 lib in   cf9963f   by  @pengbowang-nv  in  #13206  
 [None][pref] Consolidate prefix reuse queries into single analyzePrefixReuse radix tree walk by  @SimengLiu-nv  in  #13095  
 [None][test] Add sync_qa_tests Jenkins script and update coderabbit review by  @xinhe-nv  in  #13028  
 [None][feat] Refactor the routing part in trtllmgen by  @ChristinaZ  in  #12246  
 [None][infra] Waive 1 failed cases for main in post-merge 2671 by  @ZhanruiSunCh  in  #13261  
 [None][feat] Switch CP cache transmission from contiguous to round-robin by  @brb-nv  in  #13180  
 [None][feat] AutoDeploy: Onboard MiniMaxAI/MiniMax-M2.7 custom model by  @suyoggupta  in  #12963  
 [https://nvbugs/6088149][chore] Unwaive perf sanity tests for bug 6088149 by  @chenfeiz0326  in  #13176  
 [https://nvbugs/5955765][fix] More accurate launch parameters to avoid over-reservation in warmup by  @YihuiLu512  in  #13078  
 [https://nvbugs/5819019][fix] Remove waivers by  @YihuiLu512  in  #13118  
 [https://nvbugs/6018043][fix] Unwaive testcase by  @YihuiLu512  in  #13111  
 [None][infra] Waive 1 failed cases for main in pre-merge 34865 by  @ZhanruiSunCh  in  #13258  
 [TRTLLM-11999][feat] Add GLM-4.7/GLM-5 tool parser by  @JunyiXu-nv  in  #13150  
 [None][fix] Unwaive DeepSeekV3Lite test_bfloat16_4gpus_python_scheduler ep4 by  @lancelly  in  #13084  
 [None][test] amend for qa weekly core test list by  @ruodil  in  #13153  
 [None][test] Update Nemotron-3-Super-120B-A12B-NVFP4 MTP perf case with the real dataset on DGX-Spark by  @JennyLiu-nv  in  #12982  
 [None][fix] Cap TLLM_BENCHMARK_REQ_QUEUES_SIZE to avoid fill-loop hang by  @reasonsolo  in  #13065  
 [https://nvbugs/6074014][fix] Min-reduce available host memory to ensure that all ranks agree about whether prefetch is enabled by  @dhansen-nvidia  in  #13161  
 [TRTLLM-11339][fix] Wan tests refactor + small transformer fix by  @o-stoner  in  #12128  
 [None][fix] Fix kv_layout for FLASHINFER backend by  @yechank-nvidia  in  #13190  
 [None][chore] Update CI allowlist 2026-04-21 by  @tburt-nv  in  #13289  
 [TRTLLM-10703][feat] abort, resume for Async RL in verl by  @hchings  in  #12272  
 [TRTLLM-12127][fix] VisualGen metadata updates by  @o-stoner  in  #12862  
 [None][fix] Revert "Refactor the routing part in trtllmgen" ( #12246 ) by  @peihu-nv  in  #13294  
 [TRTLLM-11759][fix] Reduce peak host memory during NemotronH_Nano_VL_V2 init by  @pamelap-nvidia  in  #13283  
 [None][fix] Fix post-merge perf data silently failing to upload to OpenSearch DB by  @chenfeiz0326  in  #13215  
 [None][fix] Fix errors in KV cache manager V2 and scheduler V2 by  @jiaganc  in  #13104  
 [None][fix] Enforce NCCL &gt;= 2.28 at CMake configure time by  @eopXD  in  #13108  
 [TRTLLM-11861][infra] Support wildcard in bot stage-list/extra-stage commands by  @mzweilz  in  #12881  
 [TRTLLM-12062][test] remove obsolete model tests by  @xinhe-nv  in  #13262  
 [TRTLLM-12137][chore] Drop non-key-model (starcoder2/mllama/nemotron) cases from L0 by  @QiJune  in  #13315  
 [None][feat] Optimize causal_conv1d prefill and decode kernels by  @Wanli-Jiang  in  #13103  
 [TRTLLM-11733][perf] Cache constant text computations across denoise steps in LTX2 by  @luyiyun1021  in  #12677  
 [None][chore] Add Dynamo configs to TRTLLM CI - Disagg - Part 2 by  @brb-nv  in  #13168  
 [https://nvbugs/6050481][chore] Unwaive passing GPT-OSS ep tests by  @dongfengy  in  #13284  
 [None][chore] Waive DSV32 tests by  @brb-nv  in  #13352  
 [https://nvbugs/6052050][fix] Drop stale CUDA graphs on beam-width change by  @brb-nv  in  #13255  
 [https://nvbugs/6055847][fix] Preserve Nemotron HF mamba cache dtype in bench tuning by  @hyukn  in  #12826  
 [None][chore] Better Empty File Error Handling for trtllm-bench by  @yijingl-nvidia  in  #12552  
 [None][test] add models for weekly perf test by  @ruodil  in  #13325  
 [None][fix] Propagate init_load_balancer to DeepGemmFusedMoE in create_moe_backend by  @qiaoxj07  in  #13207  
 [TRTLLM-12183][chore] Move bf16/auto precision variants from pre-merge to post-merge by  @QiJune  in  #13366  
 [https://nvbugs/6076560][chore] Unwaive test_nvfp4_4gpus by  @hyukn  in  #13079  
 [None][infra] Waive 2 failed cases for main in post-merge by  @xinhe-nv  in  #13335  
 [TRTLLM-11485][feat] Feature rework: Add SageAttention refreshed kernels (attentionOp only) by  @xrq-phys  in  #12937  
 [TRTLLM-11540][feat] Revert revert of EAGLE3 dynamic tree speculative decoding support by  @sunnyqgg  in  #13081  
 [None][chore] Add related trtllm-gen attention kernel files to trigger multi-gpu tests by  @heyuhhh  in  #13260  
 [https://nvbugs/6074943][fix] Disable new aiperf server metrics to stop hang. by  @dominicshanshan  in  #13314  
 [None][doc] Restructure installation documentation by  @bobboli  in  #12402  
 [None][fix] Disable multi stream moe for super v3 by  @tcherckez-nvidia  in  #13122  
 [https://nvbugs/5919796][fix] AutoDeploy: Fix TP deadlock in multistream MoE by  @galagam  in  #13220  
 [None][fix] initialize sampler state for ADP dummy requests by  @bobboli  in  #13275  
 [ #13125 ][feat] Make auto_deploy standalone-ready and add package generator by  @lucaslie  in  #13155  
 [None][perf] Clear multimodal data upon prefill completion by  @2ez4bz  in  #13259  
 [TRTLLMINF-45][infra] Upload CI agent failure analysis to SwiftStack by  @dpitman-nvda  in  #13291  
 [https://nvbugs/6078421][fix] Commit   dcb4a71   intentionally disabled  initialize_mrope_delta_cache  in `qwen3 by  @tensorrt-cicd  in  #13269  
 [None][feat] Move DWDP contention optimization into DwdpConfig by  @JintaoPengCS  in  #12974  
 [None][doc] update verbose comments by  @VALLIS-NERIA  in  #13387  
 [None][chore] Remove closed bugs by  @xinhe-nv  in  #13189  
 [TRTLLM-9120][feat] centralize perfect router integration and validation by  @xxi-nv  in  #13250  
 [https://nvbugs/5916092][fix] Fix MTP+PP hang by preserving speculative layer weights on last PP rank by  @xxi-nv  in  #12555  
 [None][feat] Add modular logger with auto module detection and per-module filtering by  @reasonsolo  in  #13202  
 [ #4674 ][feat] enabled AutoDeploy qkv and rope fusion with trtllm attention by  @MrGeva  in  #12357  
 [None][fix] Fix multimodal KV cache block reuse for disaggregated serving by  @indrajit96  in  #12472  
 [None][fix] KVCacheManagerV2 bug fixes (V2 remains default OFF) by  @yizhang-nv  in  #12306  
 [None][test] Remove low priority QA perf test cases by  @yufeiwu-nv  in  #13374  
 [None][perf] Use +64 batch sizes for padding-enabled CUDA graphs by  @yijingl-nvidia  in  #12895  
 [https://nvbugs/5784566][fix] Isolate ray tests to avoid timeout by  @shuyixiong  in  #13062  
 [None][test] AutoDeploy: Add missing guided decoding test to CI by  @govind-ramnarayan  in  #13350  
 [https://nvbugs/5997534][fix] Fix eagle3 accuracy test - attn backend must be flashinfer by  @govind-ramnarayan  in  #13398  
 [None][infra] Waive 15 failed cases for main in post-merge by  @xinhe-nv  in  #13363  
 [TRTLLM-11958][perf] reduce @torch.library.custom_op host overhead by  @luyiyun1021  in  #13149  
 [https://nvbugs/6084445][fix] use DEEPGEMM for DeepSeek-V3-Lite fp8 chunked prefill on SM100/SM103 by  @jmydurant  in  #13257  
 [https://nvbugs/6094118][fix] remove redundant tests by  @bo-nv  in  #13411  
 [TRTLLM-11123][fix] Propagate real errors to disagg server by  @reasonsolo  in  #13119  
 [None][infra] Waive 4 failed cases for main in post-merge 2681 by  @ZhanruiSunCh  in  #13414  
 [https://nvbugs/6098095][chore] Waive failed tests for flashinfer-python==0.6.8 upgrading by  @yihwang-nv  in  #13254  
 [https://nvbugs/6064029][test] Visual gen b64 path regression tests by  @yingguo-trt  in  #13372  
 [None][fix] Populate s_host_node_name for SLURM-based perf test runs by  @hyukn  in  #13367  
 [None][feat] Add FP4 residual quantization kernel without channel reo… by  @Tracin  in  #13117  
 [https://nvbugs/6093712][fix] skip_pre_hopper for Qwen3 disagg L40S failure by  @reasonsolo  in  #13326  
 [https://nvbugs/6018172][fix] Fix DSA illegal memory access with CUDA graph and host KV cache offload by  @liji-nv  in  #13124  
 [None][infra] Waive 5 failed cases for main in pre-merge 35493 by  @ZhanruiSunCh  in  #13432  
 [TRTLLMINF-43][feat] Update SLURM job submission logic to retry up to… by  @dpitman-nvda  in  #12778  
 [https://nvbugs/6098442][fix] WAR IMA on DS V3.2 and update trtllm-gen cubin, lib and src by  @pengbowang-nv  in  #13379  
 [https://nvbugs/6094112][fix] Use TRTLLM MoE backend on Blackwell for case TestQwen3_30B_A3B::test_dummy_load_format by  @xxi-nv  in  #13327  
 [None][chore] Remove non-exist waiver by  @VALLIS-NERIA  in  #13437  
 [None][infra] Update the doc build stage rule by treating *.md-only P… by  @nv-guomingz  in  #13358  
 [None][perf] Skip request broadcast when world_size is 1 by  @yechank-nvidia  in  #13412  
 [https://nvbugs/6071380][fix] Update the invalid dynamo urls in doc. by  @nv-guomingz  in  #13038  
 [https://nvbugs/6025330][fix] Use weights_only=True in LoRA manager torch.load by  @yibinl-nvidia  in  #13391  
 [None][perf] Remove unnecessary ToPIL() from find_mm_token_lengths by  @yechank-nvidia  in  #11640  
 [TRTLLMINF-45][infra] Pin pbss.s8k.io in /etc/hosts before SwiftStack… by  @dpitman-nvda  in  #13441  
 [https://nvbugs/6007285][fix] Unwaive test_configurable_moe_multi_gpu DEEPEP-NVFP4 case by  @xxi-nv  in  #13371  
 [None][fix] Split TRT-LLM-only rope fusion out of standalone auto_deploy by  @lucaslie  in  #13454  
 [None][infra] Container vulnerability fix by  @yuanjingx87  in  #13447  
 [https://nvbugs/6097980][fix] unwaive Wan T2V example by  @zhenhuaw-me  in  #13316  
 [None][infra] Waive 4 failed cases for main in pre-merge 35639 by  @ZhanruiSunCh  in  #13461  
 [https://nvbugs/5973199][fix] unwaive TestNemotronSuperV3::test_accuracy[nvfp4-4-attn_dp_on-trtllm] by  @tcherckez-nvidia  in  #13188  
 
 New Contributors 
 
  @lishicheng1996-nv  made their first contribution in  #12990  
  @YihuiLu512  made their first contribution in  #13078  
  @tensorrt-cicd  made their first contribution in  #13269  
 
  Full Changelog :   v1.3.0rc12...v1.3.0rc13

---

## 9. [v1.2.1](https://github.com/NVIDIA/TensorRT-LLM/releases/tag/v1.2.1)
**Source**: TensorRT-LLM Releases | **Category**: GitHub Release | **Release Type**: github_release

### 요약
TensorRT-LLM v1.2.1 릴리즈에서는 KV cache 손상 문제를 해결하고 인프라 구성 요소를 업데이트했습니다. 이를 통해 모델 추론의 안정성과 라이브러리 호환성을 개선했습니다.

### 핵심 포인트
- KV cache 손상을 유발하던 이슈 수정 (#12770)
- xgrammar 및 flashinfer 라이브러리 업그레이드 (#12811)

**태그**: TensorRT-LLM, KV Cache, Update

### 원문 설명
Highlights 
 
 
  Fixed Issue  
 
 Fixed an issue that caused KV cache corruption ( #12770 ) 
 
 
 
  Infrastructure Changes  
 
 Upgraded xgrammar and flashinfer ( #12811 )

---

## 10. [v0.5.10.post1](https://github.com/sgl-project/sglang/releases/tag/v0.5.10.post1)
**Source**: SGLang Releases | **Category**: GitHub Release | **Release Type**: github_release

### 요약
SGLang v0.5.10.post1 릴리즈에서는 flashinfer 라이브러리 업데이트가 진행되었습니다. 이는 JIT cubin 다운로더 관련 문제를 해결하기 위한 조치입니다.

### 핵심 포인트
- flashinfer 버전을 v0.6.7.post2에서 v0.6.7.post3로 업데이트
- JIT cubin 다운로더 관련 이슈 해결

**태그**: SGLang, flashinfer, Update

### 원문 설명
Full Changelog :   v0.5.10...v0.5.10.post1   
 Bumps flashinfer from v0.6.7.post2 to v0.6.7.post3 to resolve an issue in its jit cubin downloader.

---

