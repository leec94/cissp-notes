# Notes on AI Guidance 
## Notes
- ISC2 Guidance on AI Security Concepts in its Certs: https://www.isc2.org/Insights/2026/04/ISC2-Publishes-Exam-Guidance-AI 
- From Dest Cert Video: https://www.youtube.com/watch?v=RLbpr7rv3HU
- AI is going to fit into existing 8 domains, nothing fundamentally new
- key CISSP mindset won't change: understand business and security problem, understand control or capability that best addresses question, and eliminate answers that solve a different problem
- Terms
  - Generative AI (GenAI): produces something new. Like ChatGPT, Midjourney, Copilot
  - Large Language Model (LLM): type of deep learning model trained on massive amounts of data. Claude, ollama
  - Prompt: the input 
  - AI Model: trained mathematical structure from its data
  - Training: process of feeding data into an algorithm so it learns patterns
  - Inference: when a deployed model processes an input and produces an output
- securing AI challenges
  - large attack surface
  - lifecycle problem
- AI regulation
  - EU AI Act: one of the first comprehensive frameworks
    - applies to any entity operating in the EU, with extraterritorial reach
- Data quality
  - central for trustworthy AI
  - must protect data across entire lifecycle
- AI-enabled security tools
  - SIEM
  - SOAR
  - XDR
  - UEBA
- AI related question starts @25:38

Elements of an AI security program

| Principle                      | Description                                                                |
| ------------------------------ | -------------------------------------------------------------------------- |
| Verify then Trust              | Validate AI outputs before adoption                                        |
| AI Acceptable Use Policy (AUP) | Define permitted and prohibited uses for AI systems                        |
| AI Czar                        | Assign accountability (e.g. Chief AI Officer) for oversight and strategy   |
| Cost-Benefit Analysis          | Evaluate benefits against security, privacy, and compliance costs          |
| Adapt Cybersecurity Program    | Extend traditional cybersec to address AI-specific risks                   |
| Traceability                   | Manage audits and maintain transparent lineage of data and model decisions |
| AI Ethics                      | Define organizational ethical principles aligned with global standard      |
| Societal adaptation            | address broader impacts such as workforce disruption and AI literacy |

AI Threats (@21:40)

| Threat                   | Short Description | Mitigation Strategies | Category |
| ------------------------ | ----------------- | --------------------- | -------- |
| Model hijacking          |                   |                       |          |
| AI-augmented attacks     |                   |                       |          |
| Prompt injection         |                   |                       |          |
| Inference attack         |                   |                       |          |
| Fake media               |                   |                       |          |
| Automated misinformation |                   |                       |          |
| Black-box problem |                   |                       |          |