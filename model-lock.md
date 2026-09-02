# Model Lock

Model id: Qwen/Qwen2.5-1.5B-Instruct-AWQ

vLLM launch flags:
--dtype half
--max-model-len 4096
--gpu-memory-utilization 0.85
--quantization awq
--enable-auto-tool-choice
--tool-call-parser hermes

Smoke test:
10/10

Distractor compliance:
2/2 call-free

Decision:
LOCKED
