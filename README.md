<div align="center">

# Hi, I'm Muazzam Amanat 👋

### AI Engineer building reliable, self-correcting agentic systems — RAG pipelines that catch their own mistakes, and multi-agent workflows that don't quietly drift off course.

[![Email](https://img.shields.io/badge/Email-muazzamgil1731%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muazzamgil1731@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muazzamgill-ai-engineer)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-1F3864?style=for-the-badge&logo=googlechrome&logoColor=white)](https://muazzam-amanat.github.io/portfolio/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/muazzamamanat)

</div>

---

## 🧠 About Me

I'm an Information Technology undergraduate at **UET Lahore**, and somewhere in the last year I fell down the rabbit hole of agentic AI and never really climbed back out.

It started conventionally enough — TF-IDF spam classifiers, a PyTorch digit recognizer, the usual first steps into applied ML. Then an AI/ML internship at Takhleeq Soft put me in front of real production workflows, and I started asking a harder question: *what actually happens when you let multiple AI agents run without a human checking every step?*

Turns out, quite a lot goes wrong. Agents loop infinitely. Retrieved context gets noisy and drags generation down with it. Worst of all, multi-agent systems quietly contradict their own memory — and nothing tells you until the damage is done. That's the problem space I now spend most of my time in: designing systems that catch their own failures before they compound, rather than pretending failure isn't part of the design space.

So today, that means building Self-RAG and Corrective RAG pipelines with real guardrails, orchestrating parallel agent workflows with LangGraph, and — for my final year project — building a diagnostic agent whose entire job is to hunt down contradictions hiding inside another system's memory. I'm not interested in AI that sounds confident. I'm interested in AI that knows when to double-check itself.

**A little about how I work:** I'd rather ship something small that's actually evaluated than something large that's never been tested against a baseline. Precision-over-accuracy tradeoffs, hard iteration guardrails, refusal boundaries — the unglamorous engineering choices are usually the ones that matter most in agentic systems, and I try to make those visible rather than hide them behind a nice demo.

---

## 🎯 Research Interests

- 🔁 **Self-correcting Retrieval-Augmented Generation** — Self-RAG and Corrective RAG (CRAG), and closing the loop between what a system retrieves and what it actually generates
- 🤝 **Multi-agent orchestration** — coordination, shared state, and parallel fan-out/fan-in workflows with LangGraph
- 🧩 **Memory consistency & drift** — contradiction detection in the persistent memory of multi-agent systems
- 📏 **Evaluation methodology for agentic AI** — precision, recall, grounding, and utility metrics for systems that don't have a single "correct" output
- 🛡️ **Reliability & guardrail design** — loop prevention, state resets, and human-in-the-loop escalation for autonomous agents

---

## 🔭 Currently Building

<table>
<tr>
<td width="30%"><b>🧠 Memory Drift & Contradiction Detection</b><br><i>Final Year Project — in progress</i></td>
<td>An LLM-based diagnostic agent that detects contradictions in the persistent memory of multi-agent AI systems, using context-aware scoping and a severity-based human-in-the-loop escalation workflow. Evaluated against a manually labeled test set using precision, recall, and F1. Team of 4, supervisor-approved.</td>
</tr>
<tr>
<td width="30%"><b>🔍 Adaptive RAG System</b></td>
<td>An enterprise-style RAG pipeline combining pre-retrieval Self-RAG (dynamic routing across vector search, web search, and parametric LLM knowledge) with post-generation Self-RAG (dual critique agents for grounding and utility), plus paper-accurate Corrective RAG (CRAG) document-relevance grading. Resolved infinite execution loops and token bloat with graph state resets and a hard 3-iteration guardrail; mitigated hallucination and context poisoning through dynamic query rewriting and strict refusal boundaries.</td>
</tr>
<tr>
<td width="30%"><b>✍️ Multi-Agent Blog Generator</b></td>
<td>A LangGraph Send-API pipeline that decomposes a topic into a structured writing plan, fans it out to independent worker agents in parallel, and reduces the output through a 3-stage subgraph (merge, image decision, image generation) — with an adaptive router choosing closed-book, hybrid, or live-search research modes, and a real-time Streamlit dashboard streaming the whole execution graph.</td>
</tr>
</table>

---

## 🛠️ Tech Stack

**Languages & Core**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**Data Science & Analysis**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**Generative AI & Agentic Systems**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![Self--RAG](https://img.shields.io/badge/Self--RAG-4B8BBE?style=for-the-badge)
![Corrective RAG](https://img.shields.io/badge/Corrective_RAG_(CRAG)-4B8BBE?style=for-the-badge)
![Multi-Agent Systems](https://img.shields.io/badge/Multi--Agent_Systems-4B8BBE?style=for-the-badge)
![Vector Databases](https://img.shields.io/badge/Vector_Databases-4B8BBE?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-4B8BBE?style=for-the-badge)

**LLM & Search APIs**

![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek_API-4D6BFE?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Tavily](https://img.shields.io/badge/Tavily_Search_API-2E8B57?style=for-the-badge)

**Backend & Deployment**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

---

## 📌 Featured Repositories

> 🔗 See the full, up-to-date list on [my GitHub repositories](https://github.com/muazzamamanat?tab=repositories)

| Project | Stack | Highlight |
|---|---|---|
| **Adaptive RAG System** | LangGraph, LangChain, Vector DB, Tavily | Dual critique agents + CRAG document grading, with hard loop guardrails |
| **Multi-Agent Blog Generator** | LangGraph (Send API), Gemini, DeepSeek, Streamlit | Parallel map-reduce agent fan-out with a live execution dashboard |
| **SMS Spam Detector** | Python, Scikit-learn, TF-IDF | 97.2% accuracy, 1.00 precision, zero false positives — chosen over a higher-accuracy variant to minimize false-positive risk |
| **MNIST Digit Classifier** | PyTorch | Fully connected neural network for handwritten digit classification |
| **Movie Recommendation System** | Python, Streamlit | Content-based recommender using cosine similarity over TMDB genre/cast/plot data |
| **WhatsApp Chat Analyzer** | Python, Streamlit | Analytics app surfacing chat activity, word frequency, and emoji trends |

---

## 📚 Additional Research

Beyond AI/ML, I've run independent quantitative and field research studies:

- **Employee Burnout & Transformational Leadership** — a cross-sectional study using stratified sampling and SPSS regression analysis, grounded in Hobfoll's Conservation of Resources theory
- **Supply Chain Analysis of Stylo Pvt. Ltd.** — primary field research via an on-site interview with the Head of Supply Chain Management, mapping operations and proposing process improvements

---

## 📜 Certifications

![RAG](https://img.shields.io/badge/Advanced_RAG-Campus_X-4B8BBE?style=flat-square)
![IT](https://img.shields.io/badge/IT_Certification-PESDC-1F3864?style=flat-square)
![IELTS](https://img.shields.io/badge/IELTS-English_Proficiency-009688?style=flat-square)

---

## 🏅 Academic Record

**Bachelor of Business & Information Technology (BBIT)** — University of Engineering and Technology, Lahore *(Expected 2027)*

| Level | Institution | Score |
|---|---|---|
| 🎓 BBIT (in progress) | UET Lahore | **85.6%** |
| 📘 Intermediate | Govt. Degree College | **97.4%** |
| 📗 Matriculation | Govt. High School | **89%** |

Relevant coursework spans core AI/CS foundations and applied business-technology domains:

`Artificial Intelligence` `Distributed Databases` `Database Systems` `Data Structures & Algorithms` `Software Engineering` `Object-Oriented Programming` `Data Communication & Computer Networking` `Web Development` `Business Statistics` `Business Mathematics` `Research Methods for Social Sciences` `Business Finance` `Financial Management` `Enterprise Systems` `Organizational Behavior`

---

## 📊 GitHub Stats

<div align="center">

![Muazzam's GitHub Stats](https://github-readme-stats.vercel.app/api?username=muazzam-amanat&show_icons=true&theme=default&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=muazzam-amanat&layout=compact&hide_border=true)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=muazzam-amanat&hide_border=true)

</div>

---

<div align="center">

## 📫 Let's Talk Agentic AI

I'm always up for a conversation about RAG evaluation, multi-agent reliability, or where LLM agents actually break in practice. If you're working on something in this space — or hiring for it — reach out through any of the links above.

*"The interesting failures in AI agents aren't the loud ones — they're the quiet ones that keep running."*

</div>
