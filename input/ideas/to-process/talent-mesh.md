# Idea: TalentMesh AI (The Internal Talent Mobility OS)

## 1. The Core Concept
An AI-powered "Internal Skills Graph" for mid-to-large enterprises ($500+$ employees). It maps the "hidden" capabilities of the existing workforce by analyzing active work output (Jira, GitHub, Slack, PRDs) and automatically suggests internal redeployments for new projects, killing the need for external hiring.

## 2. Target Market & ICP
- **Segment:** Enterprise SaaS, Fintech, and Global Capability Centers (GCCs) with 500 to 5,000 employees.
- **Geography:** HQ in USA (Delaware C-Corp), Operations/R&D in Bengaluru.
- **User Persona:** The "Strategic CHRO" or "Chief Transformation Officer." They are tasked with "Doing more with less" and reducing "Bench Time" (unallocated employees).

## 3. The Problem & JTBD
- **The JTBD:** "When a new project starts (e.g., an AI-agent initiative), help me find the 5 people already in my company who have the raw skills to lead it, so I don't have to spend 3 months and $30k hiring someone from outside."
- **The Pain:** 1. **Skills Blindness:** In a 1,000-person company, the CTO doesn't know that a QA Engineer in the "Legacy" department spent their weekends becoming a Python expert.
    2. **Talent Hoarding:** Managers often hide their best people to keep their own department running, even if that person is needed for a higher-priority company goal.
    3. **High Attrition:** Top talent leaves because they feel "stuck" in a role, unaware that a perfect role for them exists three departments over.
- **The Gap:** Workday and SAP SuccessFactors have "Skills Modules," but they rely on employees manually updating their profiles. 90% of these profiles are 2 years out of date.

## 4. The Solution Architecture
1. **The Ingestion Layer (The "Passive Map"):** Read-only integration with Jira (project tickets), GitHub (code quality/complexity), and Slack (expertise shown in channels). It maps what people *actually* do, not what their job title says.
2. **The "Adjacency" Engine:** Uses LLMs to calculate "Skill Proxies." (e.g., "If Siddharth is a PM who has managed complex API integrations in Fintech, he is 85% ready to lead our new Blockchain-Payments project").
3. **The Internal "Opportunity" Marketplace:** A Tinder-style interface for employees to see "Gigs" or "Rotation Projects" within the company that match their emerging skills.
4. **The CFO Dashboard:** Real-time calculation of **"Hiring Cost Avoided"** ($HCA$). It shows exactly how many millions of dollars the company saved by redeploying internally.

## 5. "The Enemy" (Status Quo)
- **Primary Enemy:** The "Static Job Description" and the "Manual Talent Review" (which happens once a year and is riddled with bias).
- **Secondary Enemy:** External Recruiters who poach from the company because the company doesn't know its own strength.

## 6. Go-To-Market (GTM) Strategy
- **The Wedge (Network Strategy):** Siddharth uses the CXO network to secure "Design Partner" status with 3 large GCCs in Bengaluru. 
- **The Pilot:** Offer a "Bench Audit." Run TalentMesh on the company's "unallocated/bench" list to find 10 people who can be moved to active billable projects within 30 days.
- **The Channel:** Partner with "Future of Work" consultancies (McKinsey/BCG/Deloitte) who are already advising CXOs on "Organizational Agility."

## 7. Business Model & Scale
- **Pricing:** Per-seat B2B SaaS fee ($10 to $25 per employee/month).
- **The Math:** A 2,000-person company pays $40,000/month ($480k ARR). 
- **Scale:** Capturing 200 such enterprises = **$96M ARR.**
- **The Moat:** The "Skills Graph" becomes more accurate the longer it stays integrated. Switching costs are massive because TalentMesh knows the company's "Cultural and Technical DNA" better than anyone.