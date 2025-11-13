# Global-Conference-Intelligence-System---MAS
# 📊 Global Conference Intelligence System  
### **Mind-Alliance Systems — Internship Project (2025)**  
**Automated Global Conference Scraper • Agentic Pipelines • n8n Backend • Vibe-Coded Frontend (Replit) • Future: Knowledge Graph + Agentic Graph RAG**

---

## ⭐ STAR SUMMARY  

### **S — Situation**  
Mind-Alliance Systems needed an automated, scalable way to collect, analyze, and structure global conference and event data.  
This data directly supports:  
- Marketing & Sales lead generation  
- Competitive intelligence  
- Strategic foresight and scenario-planning workflows  

Manual research or generic LLM/Google queries were not sufficient — the company required **deep, structured, and continuously updated** event intelligence.

---

### **T — Task**  
Build a system that can:  
- Automatically **crawl and extract** global events based on user-defined keywords and locations  
- Capture **deep details** (agenda topics, speakers, roles, session descriptions)  
- Provide **filters and search** similar to Amazon facets  
- Enable an **AI chatbot** capable of answering event-related queries using real-time structured data  
- Supply insights for **scenario-planning software**, including drivers of change, industry trends, and competitor movement  
- Create the foundation for future **knowledge graph** and **Agentic Graph RAG** integrations  

---

## 🚀 A — Approach  

### **1. System Architecture**
#### **Frontend (UI)**
- **Vibe-coded the entire frontend in Replit**  
- Built clean UX for filters, event details, lists, relevance tagging, etc.

#### **2. Backend (Core Engine)**
- Developed multiple **agentic pipelines** using **n8n**, including:  
  - Web crawlers  
  - Deep-page scrapers  
  - Keyword-sensitive search agents  
  - Agenda + speaker extraction agents  
  - Classification + enrichment agents  
  - De-duplication + standardization workflows  
  - Calendar integration agent  
  - Confidence scoring agent  
- Designed the internal **conference data model** (industry, topic, speaker, role, metadata taxonomy)

#### **3. AI + Chat Layer**
- RAG-first chatbot design:  
  - Structured retrieval from internal database  
  - Deep extraction only if information missing  
  - Hallucination-resistant responses  
  - Query routing to appropriate agentic pipelines  

#### **4. Future Vision (Planned + Explored)**
- Investigated **Knowledge Graph** tooling (Stardog, Neo4j)  
- Planned mapping for speaker → topic → industry → company → trend → scenario  
- Prepared architecture for **Agentic Graph RAG** for high-precision reasoning  

---

## 🙅‍♂️ Rejected Approaches (and Why Not)

| Approach | Why It Was Rejected |
|----------|----------------------|
| One-time scrapers | Events change daily → continuous automation needed |
| ChatGPT/Google for event lists | No deep agenda/speaker extraction; not reliable |
| Manual spreadsheet maintenance | Not scalable; error-prone |
| Single-agent pipeline | Too fragile; multi-agent distributed design required |
| Surface-level metadata only | Not useful for strategy, foresight, or competitive intel |

---

## 🧠 R — Result (Work-in-Progress, Not Final)  
Over the internship, I built a strong **foundation** of the system:  
- Multiple **agentic pipelines** running in n8n  
- Interactive **vibe-coded frontend** with filters and event detail pages  
- Early-stage RAG-enabled chatbot integration  
- Structured conference data model and taxonomy  
- Workflow ready for future knowledge graph integration  

The system was **partially functional**, providing early outputs and demonstrating the full architecture, but was not production-complete.

---

## 🧩 Internship Outcomes (6 Months)  
During my 6 months at Mind-Alliance Systems, I:

- **Identified inefficiencies** in the company’s management of global events and conference data.  
- **Developed an AI assistant** using **RAG-integrated agentic workflows in n8n** to automate global event tracking and related tasks, enabling context-aware responses grounded in real-time knowledge and reducing manual tracking time.  
- **Explored real-time web scraping frameworks** and **knowledge graph integration** to enable semantic search and enhance entity-level reasoning over global event data.  

---

## 🧩 Recommended Repository Structure  

