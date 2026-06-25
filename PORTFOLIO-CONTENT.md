# Faisal Khan — Portfolio Content (Source of Truth)

> Curated from LinkedIn, CV, and the IBM profile PDF. This is the *content* we'll
> design the site around. Anything in **CUT** at the bottom is deliberately left off.

---

## 1. Identity & Positioning

- **Name:** Faisal Khan *(full legal: Faisal Ahmed Khan — recommend "Faisal Khan" on site)*
- **Role:** Application Developer / Backend Engineer @ **IBM**
- **Location:** Kolkata, India
- **Pronouns:** He/Him

**Headline (pick one — my top choice first):**
1. **Backend & GenAI Engineer — I build serverless systems that put LLMs to work in production.** ⭐
2. Software Engineer @ IBM · Distributed Systems & AI/LLM Integration
3. I design Python serverless systems on AWS that bring large language models into real enterprise workflows.

**One-line tagline (hero subtext):**
> Backend engineer at IBM building a serverless compliance-analysis platform — AWS Lambda, DynamoDB, SQS, and Amazon Bedrock (Claude) at its core.

---

## 2. About (three lengths — site will likely use the medium one)

**Short (hero):**
Backend engineer specializing in serverless architecture and production GenAI. I turn ambiguous problems into reliable, well-tested systems on AWS.

**Medium (about section):**
I'm a backend engineer at IBM working on a serverless compliance-analysis platform
that evaluates regulatory content across multiple markets. I build and maintain
distributed systems with AWS Lambda, DynamoDB, SQS, and Amazon Bedrock — shipping
everything from RAG chatbots and validation engines to multi-step approval workflows.
A big part of my work is tracing failures across services and fixing them at the root:
debugging model responses, resolving data inconsistencies, and hardening reliability
in AI-driven workflows. I care most about backend systems, distributed architecture,
and making AI actually dependable in production.

**Full (optional long version):** keep the CV "Profile" paragraph as a fallback.

---

## 3. ⭐ Flagship Work — IBM Regulatory Content-Review Platform

*This is the centerpiece. A serverless, multi-market platform for regulatory content
review, built on AWS with Amazon Bedrock + Anthropic Claude. Best framed as 4–5 short
"case study" cards rather than a bullet dump.*

**Architecture one-liner:** Event-driven microservices — **planner → worker → validator**
Lambdas, coordinated over **SQS**, with **DynamoDB** + **S3** for state, and **Bedrock
(Claude / Llama)** for analysis.

| # | Case study | What it does | Tech highlights |
|---|-----------|--------------|-----------------|
| 1 | **RAG compliance chatbot** | Q&A over a domain knowledge base, with multiple retrieval strategies, an extended-reasoning mode, and content segregation by business function | Bedrock, Claude, RAG, embeddings (Titan/Cohere), knowledge bases |
| 2 | **Automated requirement-validation engine** | Validates content against requirements with a feedback loop and market-specific knowledge-base querying; unit-tested | Lambda, Bedrock, prompt engineering, pytest |
| 3 | **Multi-step approval workflow** | Delegation, role-based assignment, and confidential-submission access controls, end to end | Lambda back end + React front end, DynamoDB, RBAC |
| 4 | **PPTX → PDF processing pipeline** | Converts PowerPoint to PDF; fixed image-cropping defects via font embedding | Containerized LibreOffice on **ECS**, Docker, S3, Textract |
| 5 | **SES status-notification system** | Delivery-status notifications with recipient de-duplication and exclusion of prior actors | Amazon SES, DynamoDB |

*Also: extended the platform to a new market with nested sub-markets (data-backfill
scripts + role-permission replication); coordinated releases with disciplined Git
branching across dev/QA/prod (Jenkins, SonarQube, JFrog, Bitbucket).*

---

## 4. Experience (timeline)

**IBM** — *2 yrs 5 mos*
- **Application Developer / Backend Engineer** (Full-time) · Jan 2025 – Present · Kolkata · On-site
- **Application Developer – Cloud Full Stack** (Apprenticeship) · Feb 2024 – Dec 2024 · Remote

**TeleMatrix Global Pvt Ltd** — **Full Stack Developer** (Internship) · Mar 2023 – Jan 2024 · Kolkata · Remote
- Built efficient web apps; front end (HTML/CSS, JS, React) and back end (Node.js, Express, Python).

---

## 5. Selected Personal Projects *(from GitHub — pick the strongest 3–4)*

| Project | What it is | Stack |
|--------|-----------|-------|
| **tinDog** | "Tinder for dogs" responsive landing page | HTML, Bootstrap |
| **Drum Kit** | Interactive drum machine (keyboard + click) | HTML, CSS, JS |
| **Mi Clone** | Pixel-faithful Xiaomi homepage clone | HTML, CSS |
| **Blog Website** | Static blog layout | HTML, CSS |
| *(others)* | todoList, Newsletter Signup, Snake game | JS |

> These are early/learning projects. Recommendation: show 3 best as a small "Also builds
> for fun" strip, and link the GitHub profile for the rest — keep the IBM work as the star.

---

## 6. Skills (grouped — curated)

- **AI / GenAI:** Amazon Bedrock · Anthropic Claude · LLM integration · RAG · knowledge bases · prompt engineering · embeddings (Titan, Cohere) · AI agents · validation/feedback loops
- **Cloud / Backend:** Python · AWS Lambda · serverless · microservices · S3 · DynamoDB · SES · Cognito · API Gateway · Textract · SQS · REST APIs
- **Databases:** DynamoDB (NoSQL modeling) · MySQL
- **DevOps / CI-CD:** Jenkins · SonarQube · JFrog · Git · Bitbucket · CloudWatch · Docker · ECS
- **Frontend:** JavaScript (ES6+) · React.js · HTML/CSS · Bootstrap · responsive design
- **Languages & tools:** Python · JavaScript · C++ · SQL · Java · Postman · NPM · Agile (Jira, Confluence)

---

## 7. Education

- **Heritage Institute of Technology** — B.Tech, Electronics & Communications Engineering · 2020 – 2024 · CGPA **8.6**
- **Young Horizons School** — Higher Secondary (Maths & CS) · 2017 – 2019 · **86.16%**

---

## 8. Languages

English (Fluent) · Hindi (Fluent) · Urdu (Very good) · Bengali (Good)

---

## 9. Contact & Links

- **Email:** faisalak056@gmail.com  *(personal — use this, NOT the IBM address)*
- **LinkedIn:** linkedin.com/in/ifaisalk
- **GitHub:** github.com/iFaisalK
- **Resume:** link the PDF (downloadable)

---

## 10. ✂️ Recommended to CUT (and why)

- **Home address ("New Park Street")** — never put a home address on a public site (privacy).
- **Work email (faisalkhan@ibm.com)** — keep work + personal separate; use Gmail.
- **Phone number** — optional; recommend leaving off the public page (spam/privacy). Add a contact form instead if you want reachability.
- **LinkedIn endorsement counts, skill-assessment badges** — internal LinkedIn noise.
- **Hobbies/activities (Cricket, Volleyball, Coding Club)** — fine as one tasteful line, but not a section.
- **Redundant skills** (MATLAB, Cadence Virtuoso, Snowflake, RDBMS) — off-narrative for a backend/AI portfolio; drop unless you want a "coursework" footnote.

---

## 11. ❓ Open questions / discrepancies to confirm

1. **Degree name:** CV says "Electrical, Electronics and Communications"; LinkedIn says "Electronics and Communications." → I'll use **Electronics & Communications** unless you say otherwise.
2. **Phone on site?** Default = no (see CUT).
3. **Featured projects:** OK to lead with IBM case studies and show only 3 personal projects?
4. **Resume:** keep the existing `Faisal's Resume.pdf`, or will you upload the newer CV?
