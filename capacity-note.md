# Capacity Note

Locked model: Qwen/Qwen2.5-1.5B-Instruct-AWQ

Target p95 latency: 3.0 s

Knee concurrency: 16 (sweep-bounded)

Tokens/s at knee: 747.7

p95 latency at knee: 2.327 s

Max sustainable request rate:
At least concurrency 16 within the 3.0 s p95 SLO.

Limiting family:
The system appears to be primarily compute-limited at the tested range, because throughput continues to rise with concurrency while p95 latency remains under the SLO and errors stay at zero.
