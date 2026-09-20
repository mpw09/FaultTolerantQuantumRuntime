# Fault Tolerant Quantum Runtime

## Logical-to-Realtime Fault-Tolerant Quantum Execution

Research project investigating how fault-tolerant logical quantum workloads
translate into classical real-time compute requirements.

The project studies the chain:

logical workload  
→ QEC / detector semantics  
→ detector jobs  
→ dependency graph  
→ decoder sessions  
→ CPU/GPU scheduling  
→ feedback result  
→ dependent logical execution

### Technical areas

- CUDA-Q Logical
- fault-tolerant quantum computing
- quantum error correction
- detector error models
- extended/adaptive detector models
- logical-to-QEC lowering
- classical job generation
- dependency modelling
- runtime architecture
- CPU/GPU placement
- scheduling
- feedback deadlines
- heterogeneous quantum-classical co-design

### Scope principle

This project does not attempt to recreate an entire fault-tolerant compiler.

It uses a deliberately small set of representative logical workloads to
investigate how QEC semantics and logical dependencies translate into
classical workload, scheduling and timing requirements.
