ML systems and GPU kernel

- **ML Systems**:
    - SGLang
        - Roadmap: Apple Device Support (2026 Q1) · [Issue #19137](https://github.com/sgl-project/sglang/issues/19137)
        - MoE performance lead: [Apple Silicon] Optimize MoE performance · [Issue #22283](https://github.com/sgl-project/sglang/issues/22283)
    - Recent contributions
        - [Apple Silicon] [MLX] Auto-detect MLX-format `quantization_config` dict · [PR #25191](https://github.com/sgl-project/sglang/pull/25191)
        - [Apple Silicon] [MLX] Fuse SwitchGLU `up_proj` + `gate_proj` · [PR #24712](https://github.com/sgl-project/sglang/pull/24712)
        - [Apple Silicon] [MLX] Fuse SwiGLU activation into gate `gather_qmv` for SwitchGLU MoE blocks · [PR #26188](https://github.com/sgl-project/sglang/pull/26188)
        - [Apple Silicon] [MLX] Fix `MlxModelRunnerStub.initialize()` signature desync with base · [PR #28660](https://github.com/sgl-project/sglang/pull/28660)
    - Active work
        - [Apple Silicon] [CI] Add model-free unit-test workflow on macos-26 · [PR #29691](https://github.com/sgl-project/sglang/pull/29691)
         
- **GPU Kernel**:
    - AMD MXFP4 quantization and FP4×FP4 GEMM on MI355X · [amd-mxfp4-gemm](https://github.com/jlee5814/amd-mxfp4-gemm)
    - NVIDIA NVFP4 on B200


