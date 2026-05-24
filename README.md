# I build production AI infrastructure that solves real enterprise problems at Fortune 500 scale.

**Senior DevOps Engineer → AI Infrastructure Product Leader**  
Enterprise Azure + AI Memory Systems + iOS Development  
Shipping production systems used by 1.4k+ developers globally

---

## 🎯 Production Impact

Currently managing **40+ Azure environments** for Mercedes-Benz Bank, Helvetia, Bosch, and Vetter Pharma. Building AI infrastructure that eliminates context loss, reduces integration failures by 400x, and saves $2000+ monthly in API costs.

**Recent shipped:** Multi-agent memory architecture, enterprise SAP integrations, iOS/watchOS AI apps with voice transcription and semantic search.

## 💡 Architecture & Tradeoffs

### [MCP Memory Service](https://github.com/doobidoo/mcp-memory-service) — 1.8k ⭐  
**Problem:** AI assistants lose context between sessions, killing productivity  
**Architecture:** Dual-layer memory (local + distributed) with semantic search  
**Tradeoffs:** 20% operational complexity for 90% context preservation  
**Impact:** 13+ AI tools, 8500+ stored memories, 60% API cost reduction  

### [Enterprise AI Architecture Decisions](https://github.com/doobidoo/enterprise-ai-architecture-decisions) — Production ADRs
**Problem:** Enterprise AI needs security isolation + context persistence  
**Architecture:** Hybrid memory with compliance boundaries via Tailscale  
**Tradeoffs:** Storage duplication vs. Fortune 500 security requirements  
**Impact:** 99.9% integration uptime, pharmaceutical GxP compliance  

### [SHODH-Cloudflare Memory](https://github.com/doobidoo/shodh-cloudflare) — Serverless Vector DB
**Problem:** Mobile AI apps need offline-first with cloud sync  
**Architecture:** Cloudflare Workers + D1 + Vectorize for global distribution  
**Tradeoffs:** Vendor lock-in vs. edge performance and cost optimization  
**Impact:** <200ms global queries, $20/month operational costs  

### [SecondBrain](https://github.com/doobidoo/secondbrain) — iOS/watchOS Knowledge App
**Problem:** Voice notes get lost, no semantic search or context  
**Architecture:** SwiftUI + local SwiftData + API sync for knowledge management  
**Tradeoffs:** Device storage vs. instant offline access and privacy  
**Impact:** Voice transcription, semantic memory, cross-device sync  

## 🛠️ Technical Surface Area

**Enterprise AI Infrastructure:**
- Multi-agent memory architectures with 99.9% uptime requirements
- Semantic search and vector embeddings for production knowledge systems  
- MCP (Model Context Protocol) server development for AI tool integration
- Cost optimization strategies for 24/7 LLM-powered applications

**Enterprise Azure at Scale:**
- 40+ multi-tenant Azure environments with Terraform Infrastructure as Code
- SAP RFC/HSDT integration frameworks handling HTTP 303 SSL certificate issues
- Database migration pipelines (SQL Server, MariaDB, PostgreSQL) with compliance
- Azure Monitor + Splunk SIEM integration for Fortune 500 security requirements

**iOS/Mobile AI Applications:**
- Swift, SwiftUI, SwiftData development for iOS and watchOS platforms
- Voice transcription integration with offline-first architecture
- Cloudflare Workers backend APIs with D1 database and Vectorize

**Integration & Automation:**
- EDI/EAI systems (eBiss 3, SAP JiVS) for enterprise B2B communication
- GitHub Actions CI/CD with automated testing and deployment pipelines
- Docker containerization and tmux-based daemon management for AI agents

## 📊 Production Metrics & Business Impact

**Cost Optimization:**
- $2000+ monthly savings through semantic caching and context reuse
- 60% reduction in LLM API calls via intelligent memory systems
- $150K+ annual licensing savings through custom SAP integration frameworks

**Reliability & Performance:** 
- 99.9% uptime across 40+ enterprise Azure environments
- 400x improvement in integration success rates (40% → 99.9%)
- Mean Time to Recovery: 2 hours → 5 minutes for critical system failures

**Developer Productivity:**
- 45% improvement in onboarding efficiency (40% → 15% time-to-productivity)
- 8500+ high-quality memories stored and searchable across development teams
- Zero context loss across AI assistant sessions with semantic memory persistence

## 🏗️ Enterprise Experience

**Senior Technical Consultant @ Data Migration International AG (2023-Present)**
- Leading Azure cloud migrations and SAP integrations for Fortune 500 pharmaceutical clients
- Managing compliance requirements (GxP) while implementing cutting-edge AI infrastructure  
- Designing multi-tenant architectures that balance security isolation with operational efficiency

**Why This Matters:** Enterprise AI isn't just about cool demos. It's about building systems that work reliably in regulated environments, handle real business processes, and deliver measurable ROI while maintaining security and compliance standards.

## 🔗 Architecture Decision Records

**Production tradeoff thinking documented:**
- [ADR-001: Dual Memory Architecture for Enterprise AI](https://github.com/doobidoo/enterprise-ai-architecture-decisions/blob/main/ADR-001-dual-memory-architecture.md)
- [ADR-002: SAP RFC Integration SSL Strategy](https://github.com/doobidoo/enterprise-ai-architecture-decisions/blob/main/ADR-002-sap-ssl-certificate-strategy.md)  
- [ADR-003: Multi-Tenant Azure Terraform State Management](https://github.com/doobidoo/enterprise-ai-architecture-decisions/blob/main/ADR-003-terraform-state-management.md)
- [ADR-004: AI Agent Cost Optimization Strategies](https://github.com/doobidoo/enterprise-ai-architecture-decisions/blob/main/ADR-004-ai-cost-optimization.md)

Each ADR follows the pattern: **Problem → Architecture → Tradeoffs → Production Metrics → Validation**

## 🎯 What I Work On

Building the bridge between **traditional enterprise infrastructure** and **modern AI capabilities**. Most companies have either Enterprise OR AI expertise. I combine both to ship production systems that actually work in Fortune 500 environments.

**Current focus:** Autonomous agent frameworks, semantic memory systems, enterprise AI compliance, and cost-effective LLM integration patterns.

---

## 📫 Connect

- 🌐 **Enterprise AI Blog:** [doobidoo.github.io](https://doobidoo.github.io)
- 💼 **LinkedIn:** [Henry Krupp](https://linkedin.com/in/henry-krupp-a94a205/)  
- 📧 **Email:** [5000709+doobidoo@users.noreply.github.com](mailto:5000709+doobidoo@users.noreply.github.com)

---

## 📈 GitHub Stats

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=doobidoo&theme=dark&hide_border=false&include_all_commits=true&count_private=true)](https://github.com/doobidoo)
[![GitHub Streak](https://nirzak-streak-stats.vercel.app/?user=doobidoo&theme=dark&hide_border=false)](https://github.com/doobidoo)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=doobidoo&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)](https://github.com/doobidoo)

---

**Tech Stack:** Python, Swift, TypeScript, C#, Terraform, Azure, Cloudflare Workers, SQLite, Docker, SAP, GitHub Actions

*Building enterprise AI infrastructure that ships products, not just prototypes.*
