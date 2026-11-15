# Jinghao Wang · 王靖皓

Hi, I’m Jinghao Wang. I build and study systems for AI workloads, from GPU scheduling and performance prediction to the orchestration of multi-agent LLM workflows.

I’m a PhD candidate in Software Engineering at Beihang University.

[![Academic website](https://img.shields.io/badge/Academic%20Website-1F6282?style=flat-square)](https://jinghao-coding.github.io/)
[![Publications](https://img.shields.io/badge/Publications-52637A?style=flat-square)](https://jinghao-coding.github.io/#publications)
[![Crater on GitHub](https://img.shields.io/badge/Crater-314C74?style=flat-square&logo=github&logoColor=white)](https://github.com/raids-lab/crater)

## Research Interests

My interests include how AI systems predict workload performance, allocate resources, and coordinate execution.

- **GPU scheduling and resource management** — Allocating accelerators to training and inference workloads as demand changes.
- **Performance prediction** — Modeling workload behavior across hardware and using those estimates to guide scheduling.
- **LLM systems and agent infrastructure** — Scheduling multi-agent workflows and managing the resources they need at runtime.

## Building Crater

I lead the development of Crater, an open-source Kubernetes platform for training and inference on shared GPU clusters. Researchers use it to submit training jobs, deploy inference services, and monitor GPU usage. My work focuses on platform architecture, resource scheduling, and job management.

[![Crater batch jobs console showing job status and CPU, memory, and GPU quotas](https://raw.githubusercontent.com/raids-lab/crater/cbe9485575e64f416b523df6fbe57c98738c5a3d/website/content/docs/user/quick-start/assets/openjob.webp)](https://raids-lab.github.io/crater/en/)

[Source code](https://github.com/raids-lab/crater) · [Project website](https://raids-lab.github.io/crater/en/)

## Currently Exploring

How should an inference system decide where to run a request when it has access to different kinds of accelerators?
