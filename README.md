# Sibdou Ibrahim Issifu

**Security researcher** working at the intersection of **AI systems**, **cloud infrastructure**, and **operational technology (OT) / critical infrastructure**.

I study how intelligent systems fail — in models, in the platforms that host them, and in the physical processes they sense and control — and how to make those failures observable, bounded, and governable.

Teaching Assistant, Department of Cybersecurity and Information Systems, [University of Mines and Technology (UMaT)](https://www.umat.edu.gh/) · Tarkwa, Ghana

[Email](mailto:sibdooissifu@gmail.com) · [LinkedIn](https://www.linkedin.com/in/sibdou-issifu) · [Portfolio](https://sibdou-issifu-portfolio.netlify.app) · [ssshhadesCTF_](https://ssshhadesctf.geekbyte.tech/) · [Medium](https://medium.com/@sibdooissifu) · [TryHackMe](https://tryhackme.com/p/iamsibdou) · [Hack The Box](https://app.hackthebox.com/users/overview/3130744)

---

## Research interests

I am preparing for graduate research (MSc / PhD) in computer science. The questions I want to work on are not school-specific; they sit in one research programme:

1. **Security of AI systems and agents** — prompt injection and tool misuse, RAG poisoning, membership and data leakage, evaluation and guardrails that live in application code rather than in a system prompt. How do we threat-model, test, and govern models that retrieve, call tools, and act?
2. **Cloud and software supply chain as the AI control plane** — IAM, isolation, Kubernetes runtime integrity, logging, and lab/sandbox design. AI systems inherit the attack surface of the platforms they run on.
3. **OT, IoT, and critical infrastructure** — sensing, telemetry, and control in mining, agriculture, and industrial environments. How do we secure cyber-physical systems when connectivity, AI analytics, and resource constraints collide — especially in developing regions?

Adjacent interests: digital forensics and cybercrime investigation, privacy-preserving ML, and AI governance (NIST AI RMF, EU AI Act, ISO/IEC 42001).

---

## Education

**BSc. Computer Science and Engineering** · University of Mines and Technology (UMaT), Tarkwa, Ghana · Graduated November 2025

### Undergraduate thesis

**Cloud-Based Supply Chain System for Smart Agriculture with Sentiment-Driven Analytics and Blockchain for Transparency**

A cloud-native platform for verified agricultural produce: IoT sensing and geolocation, consortium blockchain for traceability, and sentiment models trained on a custom Ghanaian feedback corpus. The work treats supply-chain integrity as a security and trust problem, not only a software-delivery problem.

**Manuscript:** E. Affum, S. I. Issifu, and Okai, *Cloud-Based Supply Chain System for Smart Agriculture with Sentiment-Driven Analytics and Blockchain for Transparency*. *Ghana Journal of Technology*. **Under review** (sent to review, September 2026).

---

## Selected research and systems

Work that best represents how I think. Full code: [github.com/iamissifu](https://github.com/iamissifu).

### AI systems security

| Project | Focus |
| --- | --- |
| [Red-Team-Harden-RAG-AI-Agent](https://github.com/iamissifu/Red-Team-Harden-RAG-AI-Agent) | Assess, exercise, and harden a RAG agent with tools against the [OWASP LLM Top 10](https://genai.owasp.org/llm-top-10/) (prompt injection, retrieval poisoning, task hijacking); launch-readiness reporting. |
| [healthguardAI-grc-audit](https://github.com/iamissifu/healthguardAI-grc-audit) | Pre-launch GRC review of a clinical risk model: EU AI Act, GDPR/CPRA, [MITRE ATLAS](https://atlas.mitre.org/), NIST AI RMF register, fairness/SHAP/proxy-bias audit, KRIs, model card. |
| [salesops-agent](https://github.com/iamissifu/salesops-agent) | AgentOps runtime: input / tool / output policies in code, sandboxed analysis, human-in-the-loop side effects, traces, live evaluation. |
| [llm-ops-capstone](https://github.com/iamissifu/llm-ops-capstone) | Production-shaped RAG service: retrieval, tracing, semantic cache, cost, input/output guards, evaluation. |

### Agentic systems

| Project | Focus |
| --- | --- |
| [Enterprise-Multi-Agent-Code-Review-Orchestrator](https://github.com/iamissifu/Enterprise-Multi-Agent-Code-Review-Orchestrator) | Multi-agent review with MCP tools, scoped subagents, and schema-validated outputs (failure isolation). |
| [legal-intelligence-ai-system](https://github.com/iamissifu/legal-intelligence-ai-system) | Vertex AI persona pipeline with context chaining and an algorithmic quality gate before a section is accepted. |
| [agentic-data-analysis](https://github.com/iamissifu/agentic-data-analysis) | Semantic Kernel group-chat pipeline with a hard human checkpoint before generated code runs, plus full message audit logs. |

### Cyber-physical, cloud, and detection

| Project | Focus |
| --- | --- |
| UMaT IoT Lab | IoT and AI for smart agriculture and sustainable mining: environmental safety, pollution control, resource management. |
| [cyber-threat-intelligence-forecasting](https://github.com/iamissifu/cyber-threat-intelligence-forecasting) | Phishing classification, imbalanced CVE exploit prediction, attack-volume forecasting — prevention, prioritization, anticipation. |
| [network-intrusion-detection-nslkdd](https://github.com/iamissifu/network-intrusion-detection-nslkdd) | Supervised, unsupervised, and rule-based detection compared on NSL-KDD. |
| [mined-tonnes-predictor-Hybrid-models](https://github.com/iamissifu/mined-tonnes-predictor-Hybrid-models) | Hybrid models for haulage / production in a mining setting (domain ML on industrial data). |
| [ubuntu-server-hardening-for-k8s](https://github.com/iamissifu/ubuntu-server-hardening-for-k8s) | Ansible hardening, Docker, and a single-node Kubernetes baseline. |
| [gyaakye-student-portal](https://github.com/iamissifu/gyaakye-student-portal) | Session-bound OTP, cross-browser challenge rejection, and security-event logging. |
| [ssshhadesCTF_](https://ssshhadesctf.geekbyte.tech/) | Founder-built CTF platform: challenges and vulnerable machines so beginners can learn and practice cybersecurity. |

---

## Appointments

**Teaching Assistant** · Department of Cybersecurity and Information Systems, UMaT · Nov 2025 – present  
Labs and instruction in cybersecurity, AI in engineering, and data science; Python, network security tooling, and ML experiments; grading, research support, and mentorship.

**IoT Researcher** · UMaT IoT Lab · Jan 2024 – present  
IoT and AI systems for smart agriculture and sustainable mining.

**Associate Projects Reviewer** · Udacity (remote) · Oct 2022 – present  
Reviewed 5,000+ cybersecurity and AI projects against rubrics; technical guidance for Nanodegree learners.

**Cloud and Cybersecurity Engineer** · CloudSec Network (remote) · Sep 2025 – Nov 2025  
Secure, automated LMS lab service on AWS with Terraform: provision, monitor, teardown, IAM, sandboxing, and logging.

**Cybercrime and Digital Forensics Intern** · Ghana Police Service — Cybercrime Unit and Digital Forensics Lab, Kumasi · May 2025 – Jul 2025  
Device imaging and analysis, OSINT for threat profiling, and security-awareness training for public institutions.

**Software Developer and Application Security Intern** · Kologsoft, Bolgatanga · Oct 2023 – Dec 2023  
Secure coding in Flutter and web apps; vulnerability analysis; digital-literacy workshop content.

---

## Teaching and community

- **Cybersecurity Instructor and Program Manager**, Geek Byte Tech Training, Ghana (Sep 2024 – present) — curriculum and labs for 50+ learners across cybersecurity, AI/ML, and related tracks; cloud-based defensive labs.
- **Founder and CTF Engineer**, [ssshhadesCTF_](https://ssshhadesctf.geekbyte.tech/) (Dec 2025 – present) — I design and run a learning platform where I create CTF challenges and vulnerable machines so beginners can practice cybersecurity in a controlled lab.
- **IoT Instructor**, Aaenics Robotics Club, UMaT (Jan 2023 – Jul 2025) — microcontroller programming, sensing, and student projects in automation and environmental monitoring.

---

## Writing

Selected notes on cloud, Kubernetes, and infrastructure security:

- [Three-tier architecture on AWS](https://medium.com/@sibdooissifu/three-tier-architecture-on-aws-164a4d5b3033)
- [Getting started with kube-bench (CIS Kubernetes)](https://medium.com/@sibdooissifu/getting-started-with-kube-bench-for-kubernetes-cis-benchmarking-dd6f0045721f)
- [Deploying a Java application with MySQL on Kubernetes](https://medium.com/@sibdooissifu/how-to-deploy-a-java-application-with-mysql-on-kubernetes-1a363f3374a7)
- [Vulnerability assessment on Docker images](https://medium.com/@sibdooissifu/vulnerability-assessment-on-docker-images-9e73d18715c9)

More: [medium.com/@sibdooissifu](https://medium.com/@sibdooissifu)

---

## Methods and tools

**Languages and systems:** Python, C/C++, Bash, Go, TypeScript/JavaScript, Terraform, Docker, Kubernetes, AWS, Ansible, FastAPI, Git, MySQL

**Security and research:** threat modeling (MITRE ATLAS, OWASP LLM/ML), GRC mapping (NIST AI RMF, ISO/IEC 27001, ISO/IEC 42001), digital forensics and OSINT, network analysis (Wireshark, Nmap), lab isolation and logging (ELK)

**AI / ML:** RAG and agent pipelines, evaluation and tracing, classical ML and time series, fairness and explainability (SHAP), transformers for text

---

## Certifications (selected)

| Credential | Issued |
| --- | --- |
| HTB Certified Penetration Testing Specialist (CPTS) | May 2026 |
| Hackviser Certified Associate Penetration Tester | Jan 2026 |
| EC-Council Certified Ethical Hacker (CEH v13) | Mar 2025 |
| ISO/IEC 27001:2022 Lead Auditor | Jul 2025 |
| ISO/IEC 42001:2023 AI Management System Lead Auditor | Jul 2025 |
| Certified Cyber Security Analyst (C3SA) | Jul 2025 |
| Cloud Audit Academy — Cloud Agnostic | Jul 2025 |
| Kubernetes and Cloud Native Associate (KCNA) | May 2025 |
| AWS Certified Cloud Practitioner | Jan 2025 |
| Google Cybersecurity Professional Certificate | Jun 2024 |

Practice: [TryHackMe](https://tryhackme.com/p/iamsibdou) · [Hack The Box](https://app.hackthebox.com/users/overview/3130744)

---

## Contact

Open to **graduate research** (MSc / PhD) and research assistantships in AI security, cloud security, and OT / critical-infrastructure security.

**sibdooissifu@gmail.com** · [linkedin.com/in/sibdou-issifu](https://www.linkedin.com/in/sibdou-issifu)
