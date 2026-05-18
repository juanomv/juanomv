Hi there, I'm Juan Macías 👋

Senior Backend Engineer | Full-Stack & AI Developer

Systems Engineer | Product-Minded Developer | AI-Assisted Operations
Location: Portoviejo, Manabí, Ecuador 🇪🇨
Email: juanmacias860@gmail.com
LinkedIn: [linkedin.com/in/juan-macias-soft](https://linkedin.com/in/juan-macias-soft)


🚀 About Me

I am a passionate Systems Engineer with over 5 years of professional experience architecting, debugging, and maintaining robust, production-grade systems. My core expertise lies in building end-to-end applications that bridge high-performance backends, interactive user interfaces, and intelligent machine learning workflows.

With a strong foundation in Product Thinking, I don't just write code—I design solutions that align perfectly with business requirements, focus on user experience, and maximize operational efficiency. Currently, I am expanding my capabilities as a Fellow at Anyone AI, mastering advanced Machine Learning operations (MLOps) and large-scale data systems.

🛠️ Technical Stack

Category

Technologies

Backend Frameworks

Python (FastAPI, Flask), JavaScript/TypeScript (Node.js, Express, NestJS), Java (Spring Boot), PHP (Laravel)

Frontend & UI

React 18, TypeScript, Vite, TailwindCSS, shadcn/ui, HLS.js, Flutter, Dart

AI / Machine Learning

YOLOv8 (Custom Fine-Tuning), YOLO-World, Google Gemini (2.0 / 2.5 Flash / Vision), WhisperX, LangChain, ChromaDB

Databases & ORMs

PostgreSQL, MySQL 8, MongoDB, Redis, Cassandra, SQLAlchemy, Hibernate

DevOps & Cloud

Docker, Docker Compose, AWS (EC2, S3), DigitalOcean Spaces, Linux (Ubuntu), Git/GitHub

Testing Frameworks

pytest (Python), Jest (JavaScript/TypeScript), JUnit / Mockito (Java)

🌟 Featured Projects

📺 AdMonitor — Live TV Advertising Intelligence System (Production)

An end-to-end automated platform built to detect, classify, and monitor advertisements in live television broadcasts in real time.

Architecture & Microservices: Designed a multi-file distributed backend using asynchronous Python (FastAPI) split into dedicated streaming and analytical services, leveraging WebSockets for live progress tracking.

Complex Debugging & Memory Optimization: Diagnosed and fixed a critical memory leak that caused system crashes when processing a full day of continuous live streams (~480 .ts segments). Stabilized RAM consumption into a flat, constant baseline by optimizing NumPy array lifecycle management and introducing a sliding-window context mechanism.

AI Pipelines: Implemented parallel multi-modal processing pipelines:

Vision Pipeline: Custom-tuned YOLOv8 for brand logo detection, augmented by Gemini Vision to enrich metadata semantic attributes (brand, sector, exposure type), storing 150+ attributes per detection in MySQL 8.

Audio Pipeline: WhisperX (Large-v2, CPU int8) for automated transcription and Gemini 2.5 Flash with context overlapping to detect advertising block boundaries and continuity.

Interactive Frontend Dashboard: Built a highly reactive dashboard with React 18, TypeScript, and Vite, featuring a custom HLS.js player mapped to an interactive ad timeline, a human-in-the-loop validation interface, and a review queue (pending → approved / rejected).

Deployment: Containerized the entire ecosystem using Docker and Docker Compose, managing assets and dynamic .m3u8 playlist generation over DigitalOcean Spaces (S3).

💰 Scalable RAG Financial Advisor Chatbot (Anyone AI Fellowship)

An advanced enterprise-grade Retrieval-Augmented Generation (RAG) system engineered to ingest and analyze massive financial documentation.

Built an automated document pipeline converting over 10,000+ unstructured PDFs into clean, hierarchical Markdown formats.

Implemented semantic chunking strategy, generated optimized vector embeddings, and orchestrated historical lookups via ChromaDB and LangChain.

Integrated strict validation layers to eliminate LLM hallucinations, exposing the entire flow via a high-performance FastAPI gateway.

Tech Stack: Python, LangChain, FastAPI, ChromaDB, Gemini API, Docker.

📊 End-to-End Predictive Analytics REST API (Anyone AI Fellowship)

A complete machine learning lifecycle (ML Lifecycle) API built to ingest real-world enterprise metrics and generate precise classifications.

Designed robust feature engineering, cleaning, and preprocessing data pipelines handling high-dimensional missing datasets.

Trained, cross-validated, and optimized predictive classification models ensuring high precision-recall balances.

Exposed the final trained model through a highly scalable production-ready REST API with thorough request validation.

Tech Stack: Python, Pandas, NumPy, Scikit-learn, FastAPI, PostgreSQL, Pytest.

💼 Core Professional Achievements

SAP & E-Commerce Integration (Innovus Latam): Developed a robust, bi-directional enterprise data synchronizer linking SAP Business ByDesign and external e-commerce platforms. Used Java, Redis, OData, and SOAP webhooks to automate multi-system inventory, real-time invoicing, and transaction states.

Enterprise Refactoring (Innovus Latam): Legacy overhaul of a production-level billing microservice built with Java and MongoDB, fixing critical computation anomalies and speeding up batch execution records.

99.9% Uptime Maintenance (Altura S.A.): Refactored core modules of an enterprise ERP system using Java and Spring Boot, while also engineering a centralized document management platform that cut record retrieval times by 50%.

🎓 Education & Certifications

B.S. in Systems Engineering (Ingeniería en Sistemas de Información) — Universidad Técnica de Manabí (UTM).

Machine Learning Developer Fellowship — Anyone AI (March 2026 – Present).

Certifications: Ethical Hacking (Certiprof) • Cybersecurity Awareness (Certiprof) • ISO 27001 Analyst • Cisco CCNA 200-301.

🤝 Connect with Me

💼 LinkedIn: linkedin.com/in/juan-macias-soft

🐙 GitHub: github.com/juanomv

📧 Email: juanmacias860@gmail.com

“Building efficient, containerized, and intelligent backends to solve real-world industry problems.”
