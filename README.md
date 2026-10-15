# Awesome-AI-Agent-Auditing-Verification

## Top AI Agent Auditing & Verification Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Agent Evaluation, Behavior Verification, Misalignment Detection, Guardrails, Observability & Trustworthy AI Agents*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Auditing & Verification**. These tools evaluate agent behavior, detect misalignment, score trajectories, apply guardrails, run red-team tests, and provide independent verification that agents stay within intended authority and business rules.



**Examples** include Arize AI, Lakera, Patronus AI, Fiddler AI, Braintrust, Arthur AI, TruEra, WhyLabs, Humanloop, and Galileo (the category leaders).



**Open-source emphasis**: Strong open tooling exists for agent evaluation and auditing. **iFixAi**, **Langfuse**, **Arize Phoenix**, **DeepEval**, **Ragas**, **promptfoo**, and related projects enable independent verification and observability without proprietary lock-in. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Arize AI](https://arize.com/)**  

  ML and LLM observability platform with tracing, evaluation, and monitoring capabilities for production AI systems and agents (includes open-source Phoenix).



- **[Lakera](https://www.lakera.ai/)**  

  AI security and guardrails platform focused on prompt injection defense, content filtering, and runtime protection for LLM applications and agents.



- **[Patronus AI](https://www.patronus.ai/)**  

  Evaluation and testing platform for LLM applications and agents, emphasizing automated scoring, hallucination detection, and quality assurance.



- **[Fiddler AI](https://www.fiddler.ai/)**  

  Model performance and responsible AI platform providing monitoring, explainability, and governance for ML and generative AI systems.



- **[Braintrust](https://www.braintrust.dev/)**  

  Evaluation-first platform for scoring LLM and agent outputs, managing datasets, and running experiments with strong developer workflows.



- **[Arthur AI](https://www.arthur.ai/)**  

  AI performance and monitoring platform focused on model and agent reliability, drift, and operational metrics.



- **[TruEra](https://truera.com/)**  

  AI quality and observability platform (now part of broader offerings) known for evaluation, diagnostics, and trust metrics for ML systems.



- **[WhyLabs](https://whylabs.ai/)**  

  AI observability platform specializing in data and model monitoring, drift detection, and production quality for ML and LLM workloads.



- **[Humanloop](https://humanloop.com/)**  

  Prompt engineering, evaluation, and monitoring platform for teams building and iterating on LLM applications and agents.



- **[Galileo](https://www.rungalileo.io/)**  

  LLM and agent evaluation platform with trajectory analysis, automated scoring, and production monitoring focused on agent quality.



## Open-Source GitHub Projects

- **[iFixAi](https://github.com/ifixai-ai/iFixAi)**  

  Independent auditing and behavior verification for AI agents — focuses on misalignment (authority, policy, workflow, responsibility) rather than only task success, covering dozens of audit categories and supporting self-audit or human-driven runs.



- **[Langfuse](https://github.com/langfuse/langfuse)**  

  Open-source LLM engineering platform for tracing, evaluation, prompt management, and analytics — widely used to observe and score agent runs in production or offline.



- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  

  Open-source (source-available) platform for LLM tracing, evaluation, and experimentation built on OpenTelemetry / OpenInference conventions.



- **[DeepEval](https://github.com/confident-ai/deepeval)**  

  Open-source evaluation framework with pytest-style metrics for RAG, agents, tool correctness, faithfulness, and custom LLM-as-judge scorers.



- **[Ragas](https://github.com/explodinggradients/ragas)**  

  Open-source library focused on RAG and agent evaluation metrics (faithfulness, context precision/recall, etc.) and synthetic test data generation.



- **[promptfoo](https://github.com/promptfoo/promptfoo)**  

  Open-source tool for prompt and application testing, red-teaming, and CI-friendly evaluation of LLM and agent behaviors.



- **[TruLens](https://github.com/truera/trulens)**  

  Open-source library for evaluating and tracking LLM applications with feedback functions, groundedness, and relevance metrics.



- **[Guardrails AI](https://github.com/guardrails-ai/guardrails)**  

  Open-source framework for adding validation, structured output, and safety rails around LLM and agent responses.



- **[Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai)**  

  Open-source evaluation framework (UK AI Security Institute) supporting agent evaluations, sandboxed tools, and a wide range of scorers.



- **[Documentation and evaluation guides](https://langfuse.com/docs)**  

  Official docs and community resources for combining tracing (Langfuse/Phoenix) with offline metrics (DeepEval, Ragas, promptfoo) and independent audits (iFixAi).



### Additional Strong Open-Source Options

- Running independent behavioral audits with **iFixAi** to check authority, policy, and misalignment beyond simple task success.

- Instrumenting agents with **Langfuse** or **Phoenix** for full trace-level observability and online scoring.

- Writing CI-friendly unit tests for agents with **DeepEval** or **promptfoo**.

- Measuring RAG/agent quality with **Ragas** and applying runtime constraints with **Guardrails**.

- Combining open evaluation stacks with your own LLM-as-judge or human review loops.

- Accepting that commercial platforms (Arize, Lakera, Patronus, Braintrust, Galileo, Fiddler, etc.) still lead in polished dashboards, managed hosting, enterprise SLAs, and specialized security features.



**Frameworks for building custom systems**: Trace with **Langfuse** or **Phoenix** → evaluate offline with **DeepEval** / **Ragas** / **promptfoo** → run independent misalignment audits with **iFixAi** → add runtime guardrails. Suitable for teams that need transparency and control over agent verification. Many organizations still adopt commercial platforms for integrated security, compliance reporting, and support.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Agent auditing and verification tools help surface risks but do not guarantee safety or compliance. Always combine automated checks with human oversight, proper access controls, and domain-specific testing. This list is not legal, security, or risk-management advice.



---

**Made for AI safety engineers, MLOps teams, and trustworthy-AI practitioners.**

Let's keep agent verification independent, rigorous, and as open as practical.
