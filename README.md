# Joseph Li

Sunnyvale, CA · [lijoseph894@gmail.com](mailto:lijoseph894@gmail.com) · [LinkedIn](https://www.linkedin.com/in/lijoseph894/) · [josephl894.github.io](https://josephl894.github.io/)

M.S. Computer Science, University of Southern California

## Research and Projects

### [Efficient LLMs](https://github.com/josephl894/llama-int4-moe-inference)

*PyTorch, CUDA, LoRA · Jan. 2026 - May 2026 · USC*

- Converted **Llama 3.2-1B** into a **Mixture-of-Experts** model with **LoRA** adapters and kept held-out quality level with the original, perplexity **9.60 versus 9.66**
- Quantized weights from **FP16** to **INT4**, cutting model size **61%** while keeping generated answers coherent

### Power Grid Dispatch Model

*Python · Jan. 2026 - May 2026 · USC*

- Engineered a **learning-to-optimize** pipeline for New York's grid, where a model learns generation costs from public load, price, and outage data and an optimizer sets the hourly plan
- Cut the extra cost above the cheapest possible hourly plan **by 47%** versus the old schedule by adding transmission limits and a reserve margin

### [Math Reasoning Fine-Tune](https://github.com/josephl894/COT-SFT-LLM-MATH)

*Python, LoRA · Aug. 2025 - Dec. 2025 · USC*

- Trained **Qwen2.5-1.5B** with **LoRA** on 1,000 grade-school math problems to write its reasoning before the answer
- Rebuilt the grader until a correct final answer **scored consistently**, then implemented a **GRPO** trainer that rewards a correct, clearly reasoned solution among 4 candidates

### Weenix (A Unix-Like OS Kernel)

*C, x86, QEMU · Aug. 2025 - Dec. 2025 · USC*

- Constructed a Unix-like kernel in **C**, with process scheduling, a file system, and virtual memory
- Integrated the three parts in **QEMU** so processes could be scheduled, files created and removed, and a copied process shared memory until one side wrote to it

### PostgreSQL Buffer Manager

*C, PostgreSQL · Jan. 2025 - May 2025 · USC*

- Replaced **PostgreSQL**'s default memory rule with a first-in, first-out rule that discards the oldest unused data
- Benchmarked its performance against PostgreSQL's default implementation and found the simpler rule **matched its speed** at 1MB of memory

## Professional Experience

### Cortex AI — Menlo Park, CA

*AI Engineer Intern · Jun. 2026 - Aug. 2026*

- Designed and launched an LLM API gateway in **Go**, **PostgreSQL**, and **Redis** that routes OpenAI, Anthropic, and **AWS Bedrock** through one endpoint for a 2,000-seat customer and meters $10K in monthly model spend
- Built a pre-release test suite with **GitHub Actions**, expanding coverage from 5 smoke tests to 159 tasks so tool regressions were caught before release
- Established live monitoring in **Langfuse**, adopted by all 9 engineers, tracking per-session latency and failures and routing each failure to the engineer responsible
- Reduced wasted model spend by stopping runaway agent loops and using an **LLM judge** to flag unnecessary tool calls

### Yoyo Markets Inc. — New York, NY (Remote)

*AI Engineer · Aug. 2025 - Dec. 2025*

- Automated manual research and editorial work with a **Python** and LLM generation pipeline, producing **50+ markets per week at 5x the hand-curated rate**
- Developed an **asynchronous Python** scraper tracking 150+ high-signal Twitter accounts in real time, feeding that pipeline **3x the signal volume** of public trend aggregators
- Devised a ranking step that uses pairwise LLM comparisons and Elo ratings to screen 200+ candidate markets per cycle and send the strongest to founder review
- Shipped a **Next.js** review dashboard on **Vercel** that founders use daily, cutting **publishing turnaround from 30 minutes to under 5 minutes**

## Education

**University of Southern California** — Los Angeles, CA
M.S. Computer Science | GPA: 3.6/4.0 · Sep. 2024 - May 2026
Relevant Coursework: ML Accelerators, Operating Systems

**University of Michigan, Ann Arbor** — Ann Arbor, MI
B.S.E. Data Science | GPA: 3.7/4.0 · Sep. 2020 - May 2024
