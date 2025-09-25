# SaaS Startup CTO Checklist 2025

A phased checklist of all things to consider for CTOs of SaaS startups.  
Organized by **Day 1 (MVP)**, **Day 100 (Seed)**, and **Day 365 (Scaling)**.

---

<details>
<summary>🚀 Day 1 (Pre-seed / MVP) — Focus: speed of learning, customer validation, staying alive</summary>

### Before You Build
- [ ] Define your **product slice** (smallest testable version customers will pay for)  
- [ ] Decide on **unit of value** (user, team, workspace, org)  
- [ ] Choose boring tech → focus on productivity, not hype  
- [ ] Have a **working doctrine** (how you build together)  

### Tools
- [ ] GitHub (repo + Issues + Wiki)  
- [ ] CI/CD from day one → PRs must pass CI  
- [ ] Password manager (1Password/Bitwarden)  
- [ ] Error tracking + logging (Sentry, Logtail, Datadog Lite)  
- [ ] Uptime monitoring (Pingdom, UptimeRobot)  
- [ ] Group email address for external services (with shared password manager)  

### Architecture
- [ ] Pick: **Monolith vs microservices** (hint: monolith)  
- [ ] Decide: **SSR vs CSR**  
- [ ] Decide: **multi-tenancy approach** (DB-per-tenant vs shared schema)  
- [ ] Auth: password-based, admin user  
- [ ] Plan for MFA/SSO later  
- [ ] Marketing site: separate from app (use app.domain.com)  
- [ ] Backups automated + tested (critical)  
- [ ] Status page (Instatus/Statuspage)  
- [ ] Never use prod data in non-prod envs  

### Code
- [ ] README with clean dev setup  
- [ ] Style guide + linters  
- [ ] Spec tests from day 1  
- [ ] Logging + error handling guidelines  
- [ ] Decide monorepo vs multi-repo  
- [ ] Seed DBs with code  
- [ ] Basic secrets management (env vars, Doppler, cloud KMS)  

### Product
- [ ] Feature flags + kill switches  
- [ ] Analytics/metrics instrumentation (Mixpanel, Amplitude, GA4)  
- [ ] Prioritize onboarding as a feature  
- [ ] Customer suggestions → dig into “why,” not “what”  

### Support
- [ ] Admin interface from day 1  
- [ ] Support ticketing system (Zendesk/Freshdesk)  
- [ ] Define supported browsers  
- [ ] Rotating founder/engineer support schedule → build empathy  

### Security
- [ ] SaaS CTO Security Checklist reviewed  
- [ ] Static code analysis (GitHub CodeQL, Snyk)  
- [ ] Centralized audit log of security events  

### Compliance
- [ ] Privacy by design: don’t store data you don’t need  
- [ ] Know where your data lives (residency)  

### Misc
- [ ] Balance big projects vs small fixes  
- [ ] Join a CTO/tech leader community  
- [ ] Start mentoring someone (keeps you sharp)  

</details>

---

<details>
<summary>⚡ Day 100 (Seed / First Paying Customers) — Focus: repeatability, team scaling, early compliance</summary>

### Team
- [ ] Always recruit → pipeline matters  
- [ ] Define engineering levels + expectations  
- [ ] Allocate time for tech debt cleanup  
- [ ] QA hire or contractor (earlier than you think)  
- [ ] Decide remote vs local team structure  

### Tools / Architecture
- [ ] Staging environment  
- [ ] Migration tooling (Flyway, Liquibase)  
- [ ] More formalized secrets management  
- [ ] Observability upgrade (logs, tracing, metrics)  

### Product
- [ ] Customer reporting → lightweight dashboards  
- [ ] Define feature evaluation process (evidence-based)  
- [ ] Vision check: say no to features outside roadmap  

### Support
- [ ] Impersonation feature for admins  
- [ ] External status page live  
- [ ] Log churn reasons + support notes  

### Security
- [ ] Third-party pen test (lightweight)  
- [ ] Customer-facing security one-pager  

### Compliance
- [ ] Familiarize with top 3 compliance standards (SOC2, ISO27001, HIPAA/GDPR)  
- [ ] Build skeleton of what certification would require  

</details>

---

<details>
<summary>📈 Day 365 (Post-seed / Scaling) — Focus: scale, enterprise readiness, compliance</summary>

### Team
- [ ] Hire VP Eng / strong manager if needed  
- [ ] Formalize experimentation framework  
- [ ] Deeper QA + automated test pipelines  

### Architecture
- [ ] Infra as code (Terraform, Pulumi)  
- [ ] DB change mgmt + migration playbooks  
- [ ] Data warehouse + analytics for customers + internal ops  

### Product
- [ ] SSO / MFA support  
- [ ] Expand APIs + developer ecosystem  
- [ ] Rich reporting + data exports  
- [ ] Deep links everywhere  

### Support
- [ ] Define 24/7 support tiers (paid only)  
- [ ] Read-only SQL/query interface for admins  

### Security
- [ ] Pen testing cadence  
- [ ] Bug bounty program (HackerOne, Bugcrowd)  
- [ ] Incident response playbooks  

### Compliance
- [ ] Kick off SOC2 / ISO prep  
- [ ] Internal security training for team  

</details>

---

✅ **Mindset Recap**  
- **Day 1 = learn fast**  
- **Day 100 = repeat reliably**  
- **Day 365 = scale + comply**  

