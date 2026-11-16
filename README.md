# Luman (Grace) Zhan

Computer Science at Duke University, concentrating in Machine Learning and AI and minoring in English. I build AI systems end to end, deploy them the way production teams do, and design the evaluation needed to show where they work, where they fail, and whether their outputs deserve trust.

I am targeting Summer 2027 AI & machine learning and SDE internships.

## 1. What I Build

My strongest work sits at the intersection of LLM agents, cloud deployment, evaluation, and product engineering. I enjoy taking a system from experiment to a deployed, access-controlled service, adding measurable quality and cost gates, and documenting the tradeoffs honestly.

Current focus areas include agent infrastructure on Amazon Bedrock AgentCore with MCP, text-to-SQL safety, LLM-as-judge methodology, execution-based evaluation, open-weight inference with vLLM and SLURM, and preference alignment with QLoRA and DPO.

---

## 2. Featured Systems

| Project | What it proves | Stack and evidence |
|---------|----------------|--------------------|
| **[Lumina Reach Analytics Agent](https://github.com/evelindsayyy/lumina_reach_analytics_agent-project)** ([live demo](https://luminareachanalyticsagent-project-2.vercel.app)) | An analytics agent deployed the enterprise way: the agent and its MCP tool server run as two AgentCore runtimes, IAM decides who may call the tools, every request is a signed-in user, and its SQL cannot write to the warehouse | Amazon Bedrock AgentCore, MCP, Strands, Claude, Snowflake, Cognito, AWS CDK, Next.js; MCP cold start 27 s to 2 s, prompt caching cut input tokens about 70%, 513 Python tests at 99% coverage |
| **[AI Model Advisor](https://github.com/evelindsayyy/security-and-qa-for-ai-models)** | Model governance across artifact security, adversarial safety, institutional evaluation, and public benchmarks, run in production at Duke during Code+ 2026 | Flask, Postgres, Docker, LLM-as-judge, execution scoring, vLLM, SLURM, 1,272 Python tests |
| **[LyricMood](https://github.com/evelindsayyy/lyrics_mood_predictor)** ([live demo](https://lyricsmoodpredictor-zrtbnhzdwavalcsqriyexb.streamlit.app/), may take a minute to wake) | Fine-tuned text classification with interpretable predictions and semantic retrieval over 76,000 songs | DistilBERT, ONNX, FastAPI, SHAP, Qdrant, 106 tests |
| **[ReCaLL Reproduction](https://github.com/evelindsayyy/recall-mini-reproduction)** | A tested, multi-seed reproduction of an EMNLP 2024 membership-inference result: four-shot ReCaLL lifts ROC-AUC from 0.615 to 0.899 on Pythia-2.8B | PyTorch, Hugging Face Transformers, WikiMIA, Colab T4, three seeds |

More: [Deadline Tracker](https://github.com/evelindsayyy/ddl_reminder) (Next.js + Supabase, [live app](https://ddl-reminder.vercel.app/)) · [Trading Agent Analyzer](https://github.com/evelindsayyy/trading-agent-analyzer) (LangGraph multi-agent research) · [DeepFact Bench Audit](https://github.com/evelindsayyy/deepfact-bench-audit) (evaluator vs human label disagreement)

---

## 3. Current Work

At Duke Code+, I own major parts of the efficacy and report-card experience for AI Model Advisor. My work includes rubric and execution-based LLM evaluation, a frozen evaluation contract, a six-rater judge validation study, DCC-hosted open-weight inference, cost-versus-performance analysis, and the frontend used to launch and compare runs.

I also contribute to sickle-cell-disease data research at the Duke Global Health Institute.

---

## 4. Technical Toolkit

| Area | Tools |
|------|-------|
| Agents and cloud | Amazon Bedrock AgentCore, MCP, Strands Agents, AWS CDK, IAM, Cognito, SSM, DynamoDB |
| ML and alignment | PyTorch, Hugging Face Transformers, TRL, PEFT, QLoRA, DPO, ONNX |
| LLM systems | LiteLLM, LangGraph, LLM-as-judge, vLLM, SLURM, prompt caching, structured evaluation |
| Backend and data | Python, FastAPI, Flask, Postgres, Snowflake, Supabase, Qdrant, sqlglot |
| Product and operations | TypeScript, Next.js, React, Docker, GitHub Actions, Vercel |

---

## 5. Contact

[LinkedIn](https://www.linkedin.com/in/luman-z-22198a2a2/) · [lz302@duke.edu](mailto:lz302@duke.edu) · [zhanluman0612@gmail.com](mailto:zhanluman0612@gmail.com)
