# Brutal Startup Council: ProofPoint (The Verified Talent Marketplace)

**Founder:** Siddharth Chattar | **Date:** 2026-04-21 | **Verdict:** See Bottom

---

## 1. The Enemy & The Gap

**The Exact Status Quo Being Replaced:**

Today, a Series B startup in San Francisco needs to hire 3 backend engineers. The Engineering Manager posts a job on LinkedIn and Lever. Within 72 hours, she has 400 applications. At least 200 of them are AI-generated --- polished resumes with perfectly tailored keywords, cover letters that read like they were written by a novelist, and GitHub profiles with suspiciously clean commit histories. She can't tell the real from the fake. She spends 15 hours in the first week doing resume screens, reducing the stack to 50. Her recruiter does phone screens, cutting to 20. She and two senior engineers block off three full days for technical interviews --- live coding on Zoom, system design whiteboarding, behavioral questions. Of the 20, 6 no-show. 4 clearly cheated by having someone else on the other side of the screen. 3 froze under pressure despite looking strong on paper. They extend offers to 3 candidates. One declines for a better offer. One accepts but ghosts on their start date. One starts and is put on a PIP within 60 days because they can't perform at the level their interview performance suggested.

Total cost: 120+ engineering hours across the team (worth ~$30,000 in loaded time), 8 weeks of calendar time, recruiter fees, and they're still short 2 engineers. The process restarts.

For the candidate side, a genuinely skilled developer in Bangalore who graduated from a Tier-2 college submits the same resume to 200 companies. She gets rejected by automated ATS filters because she doesn't have the "right" company names on her CV. She's better than 80% of the candidates who get interviews, but the system never lets her prove it. Her skills are invisible because the only credential the market accepts --- a resume --- is a self-reported document that rewards storytelling over substance.

**The Gap This Idea Claims to Fill:**

The gap is between **what someone claims they can do** and **what they can actually do**, verified in a way that both sides trust. The resume is a 1970s artifact that has been completely destroyed by AI generation tools. The live interview is expensive, biased, and a poor predictor of on-the-job performance (Google's own research found structured work-sample tests are 2x more predictive than unstructured interviews). But there is no widely adopted middle layer that says: "This person solved this specific real-world problem, in this much time, with this approach, and we verified no one helped them." That verified, portable proof-of-work doesn't exist at scale.

**What "Replaced" Actually Means:**

ProofPoint replaces the resume-screen + phone-screen + take-home-test gauntlet with a pre-verified "Skill Passport" that the candidate earns once and carries everywhere. For the employer, it replaces the first 80% of the hiring funnel (sourcing, screening, initial assessment) with a curated shortlist of candidates whose competence has been independently verified through simulation. The enemy isn't LinkedIn per se --- it's the entire chain of trust that currently runs on self-reported credentials.

---

## 2. Mom Test Failure Points

### Lie #1: "Resume spam is my biggest hiring problem."
- **Why they lie:** It's a convenient, externally-blameable complaint. Every hiring manager *says* resume spam is overwhelming. But many have already adapted: they use ATS keyword filters, recruiter pre-screens, employee referrals, and sourcing tools that bypass the inbound funnel entirely. The "400 applications" problem is real but may not be the *binding constraint* on hiring velocity.
- **How to actually test:** Ask: *"Walk me through your last 3 hires. Where did each candidate come from?"* If all 3 came from referrals or recruiter outreach (not inbound applications), resume spam isn't the problem they're actually solving for --- they've already routed around it. ProofPoint would be solving a problem they've abandoned, not one they're stuck on.

### Lie #2: "I'd trust a third-party assessment over my own interview."
- **Why they lie:** No engineering manager will admit that their interview process is bad. They will *agree* that "industry interviews are broken" while simultaneously believing their own process is the exception. The hiring manager's identity is partially constructed around their ability to judge talent. A product that says "trust our score, not your gut" is an ego threat.
- **How to actually test:** Offer to pre-screen 10 candidates for a live role using ProofPoint simulations. Deliver ranked results. Then ask: *"Would you hire #1 without doing your own interview?"* If the answer is "no, I'd still want to interview them myself," you haven't replaced the funnel --- you've added a step to it. That makes you a *cost*, not a savings.

### Lie #3: "Students would love a ProofPoint Score to bypass resume screening."
- **Why they lie:** Students will sign up for anything that promises to help them get a job. That's not signal --- that's desperation. High engagement on the supply side of a marketplace tells you nothing about demand-side willingness to pay.
- **How to actually test:** Get 100 PES University students to complete simulations and earn Skill Passports. Then cold-email 50 hiring managers with: "Here are 5 candidates pre-verified by our simulation platform, ranked by performance. Would you interview any of them?" Track response rate and interview-to-offer conversion. If hiring managers ignore or distrust the scores, your supply-side traction is a vanity metric.

### Lie #4: "I'd pay $1,000 per successful hire through this platform."
- **Why they lie:** $1,000 sounds cheap compared to a recruiter's 20% fee. So they'll nod. But the comparison is misleading. They pay a recruiter $20,000 because the recruiter does sourcing, screening, scheduling, offer negotiation, and candidate closing --- an end-to-end service. For $1,000, they expect ProofPoint to be a *tool*, not a *service*. And tools compete with free alternatives: HackerRank ($249/month), Codility, take-home assignments, or just... doing the interview.
- **How to actually test:** Don't pitch the price. Instead, run a pilot: source and pre-verify 5 candidates for a real role using the simulation platform. After the hiring manager reviews them, ask: *"What is this shortlist worth to you versus what you normally spend to get to 5 qualified candidates?"* Let them name the number. If they say less than $500, your pricing model needs a complete rethink.

### Lie #5: "Detecting AI cheating is really important to us."
- **Why they lie:** It sounds like it should be important. But most engineering managers have a simpler solution to the cheating problem: the on-site (or live Zoom) interview. They don't need an AI proctoring system because they have a human proctoring system --- it's called "watching the candidate code live." The proctoring feature solves a problem that live interviews already address.
- **How to actually test:** Ask: *"In the last year, how many hires turned out to have cheated in the interview process?"* If the answer is zero or one, cheating detection is a nice-to-have, not a must-have. If the answer is "we literally can't tell and it terrifies us," there's real pain.

---

## 3. Council Deliberation

### Opening Statements

**The Cynical VC (CV):** Let's address the TAM first. The pitch claims 1% of 1.5M global tech hires = $150M+ ARR potential. Let me check that math. 1.5M hires x 1% = 15,000 hires x $1,000 = $15M from success fees. To get to $150M, you need the "SaaS fee for the simulation platform" to do 10x the work of the per-hire fee. That means you need thousands of companies paying significant monthly subscriptions --- which means you're not a marketplace anymore, you're an assessment SaaS tool. Fine, but now you're HackerRank. HackerRank has been around since 2012, has raised $100M+, and has 2,000+ enterprise customers. Codility, similar vintage, similar scale. TestGorilla raised $70M. Karat raised $110M and offers "interviewing as a service." This is one of the *most funded and most competitive* categories in HR tech. You're not entering a gap in the market. You're entering a bloodbath. What, specifically, is your wedge against HackerRank?

**The GTM Hustler (GH):** The college wedge is the most differentiated element. Starting at PES University --- where Siddharth has alumni credibility --- and giving students a "ProofPoint Score" that they can put on their resume is smart supply-side seeding. It's the LinkedIn playbook: capture ambitious people early, give them a credential they want to display, and let social pressure pull in employers who want access to that talent. But here's where it breaks: **the credential is only as valuable as the employers who recognize it.** A "ProofPoint Score" from an unknown startup means nothing on a resume. It needs to be adopted by employers *first* for students to want it, but students need to have it *first* for employers to see it. This is the classic two-sided marketplace cold start. LinkedIn solved it by being a professional network first (utility without marketplace dynamics), then layering in recruiting. ProofPoint has no standalone utility --- if no one recognizes the score, the product is worthless.

**The Domain Expert (DE):** I've lived inside the hiring stack for a decade. Let me be direct about the JTBD. The hiring manager's actual job-to-be-done is not "verify this candidate's skills." It's "fill this seat with someone who won't be a disaster, as fast as possible, with minimal risk to my reputation." That framing matters because it reveals why assessment tools have a structural ceiling. The hiring manager doesn't want to *delegate* the evaluation --- she wants to *do less of it*. She'll use HackerRank to filter from 400 to 50, but she'll still interview the final 10 herself. ProofPoint's "Skill Passport" thesis --- that a verified score can replace the interview --- asks the hiring manager to trust a third party with the most consequential decision she makes (who joins her team). No assessment tool has ever achieved that. Triplebyte tried *exactly this* --- pre-vetted candidates with verified scores, sent directly to final-round interviews --- and it failed. They raised $50M, had Y Combinator backing, and still couldn't make the model work because employers wouldn't skip their own process.

**The Technical Pragmatist (TP):** Three technical realities to confront. First, the "Staged Crisis" simulation environments. Building a realistic in-browser IDE that simulates a production codebase with meaningful bugs, realistic constraints, and auto-evaluation of the solution is not a weekend project. It's what Karat charges $110M-funded prices for. And that's *just for engineering*. The spec also mentions "PM-Dashboard" simulations where candidates draft PRDs. Evaluating a PRD's quality programmatically is an unsolved problem --- you'd need human reviewers, which means you've just rebuilt the interview with extra steps. Second, the "Behavioral AI Proctor" that detects ChatGPT usage by tracking screen-switches and "Time-to-Insight." This is an adversarial AI problem. Candidates will use second devices, voice-to-text, or simply memorize ChatGPT outputs beforehand. Every proctoring system in education (ProctorU, ExamSoft, Respondus) has been defeated by motivated test-takers. You're proposing to fight an arms race against every AI coding assistant simultaneously. Third, the "on-chain Skill Passport." Blockchain-based credentials have been attempted by dozens of well-funded projects (Learning Machine, Blockcerts, MIT's digital diplomas). None have achieved meaningful adoption because employers don't verify credentials on-chain --- they verify them by calling references and doing their own interviews. The blockchain adds cost and complexity with zero demonstrated employer demand.

### The Debate

**CV:** The Triplebyte comparison is the one that should haunt Siddharth. Triplebyte was founded by a former YC partner (Harj Taggar) with deep Silicon Valley networks, had YC's full distribution engine behind it, offered exactly this value proposition --- "we pre-screen engineers so you can skip straight to the final interview" --- and spent $50M over 7 years trying to make it work. They eventually pivoted to a job board, then got acqui-hired by Karat for a fraction of their raised capital. And their failure mode is instructive: employers used Triplebyte as a *sourcing channel* but never trusted the scores enough to skip their own interviews. The entire "replace the interview" thesis was wrong --- not because the scores were bad, but because hiring is a trust relationship, and employers trust themselves more than any third party.

**GH:** I want to push back slightly. Triplebyte failed in 2019-2022, before AI resume spam became the crisis it is today. The landscape has genuinely shifted. When 60% of inbound applications are AI-generated, the traditional funnel *stops working*. Employers who were happy with their own process in 2021 are now drowning. There might be a new opening for a verification layer that didn't exist when Triplebyte was active. But --- and this is my real concern --- if the opening exists, HackerRank, Codility, and Karat are already rushing to fill it. They have existing employer relationships, existing candidate pools, and engineering teams building AI-detection features right now. ProofPoint would be entering a "new urgency in an old market" where incumbents have a massive head start. Siddharth's differentiation can't be the product (incumbents will copy any feature in 6 months). It has to be distribution. And his distribution edge --- CXO network + PES University --- is geographically narrow and won't scale past the first 20 customers.

**DE:** Let me add a structural concern about the cross-border angle. "India/SEA talent to US/EU companies" is the stated geography. This is a real trend, and Siddharth's US Citizenship + Bangalore base is a genuine advantage for building this bridge. But cross-border hiring introduces enormous complexity: work authorization, time zone management, tax implications, contractor-vs-employee classification (especially post the Deel/Remote.com legal battles). ProofPoint's spec says nothing about these. If you're just an assessment tool, Turing and Andela already own the "pre-vetted India/SEA talent for US companies" positioning with hundreds of millions in funding. If you're the full cross-border hiring stack, you're building a staffing company with legal complexity in 30+ jurisdictions. Neither is a clean lane for a first-time founder.

**TP:** I want to stress something about the PM simulation angle specifically, because Siddharth is a PM and might naturally lean toward it. "Draft a PRD for this churning feature" as a simulation exercise sounds compelling --- finally, a way to assess PMs beyond behavioral interviews! But evaluating PM work output is inherently subjective. Two excellent PMs will write very different PRDs for the same problem. There's no "correct" solution like there is for a coding challenge. You'd need: (a) domain experts to design each scenario, (b) trained evaluators to score each submission, and (c) a rubric that's consistent across evaluators. That's not a technology product. That's a consulting service with a UI. And if you go engineering-only to avoid this complexity, you're HackerRank with a different logo.

**CV:** Here's my fundamental question for Siddharth. HackerRank is valued at $500M+. Codility at $500M+. Karat at $800M. Turing at $1.1B. If I'm an investor, I'm looking at a market with four well-funded unicorns already fighting for the same buyer, the same candidate pool, and the same "verified skills" thesis. What is ProofPoint's unfair advantage that none of these companies can replicate? "Better UX" is not an answer --- HackerRank has 200 designers. "AI proctoring" is not an answer --- everyone's building it. "Blockchain credentials" is not an answer --- no employer has asked for it. "PES University network" is not an answer at Series A scale. What is the actual moat?

**GH:** Let me try to steelman this. The *one* angle I think could work is hyper-niche vertical positioning. Instead of "assessment platform for all tech roles" (which is HackerRank's positioning), what if ProofPoint was "the hiring platform for Indian engineering talent going to US startups"? Narrow geography. Narrow persona. Tight network effects in the Bangalore startup ecosystem. Siddharth's US Citizenship handles the cross-border trust issue. His CXO network handles employer acquisition. His PES connection handles supply. But that's not the current pitch --- the current pitch is a global "Skill Passport" platform, which is an existential fight against billion-dollar incumbents.

**DE:** Even the niche version has a problem. "Indian talent to US startups" is Turing's exact positioning. They have 2M+ developers on their platform, AI-based vetting, and deep US employer relationships. They've raised $140M. If ProofPoint narrows to this lane, Turing is the direct competitor, and the founder is bringing a bicycle to a Formula 1 race.

**TP:** One last technical point. The spec mentions detecting "screen-switches" and "Time-to-Insight" to catch AI cheating. Modern AI assistants are integrated directly into IDEs (Copilot in VS Code, Cursor). There's no "screen switch" to detect --- the AI is *inside* the coding environment. Detecting whether a code solution was AI-assisted when the AI lives within the same window as the code editor is essentially impossible without building a proprietary sandboxed IDE from scratch that blocks all extensions. That's a massive engineering undertaking, and motivated candidates will still find workarounds (second laptop, memorization, etc.). The proctoring thesis is technically unwinnable.

---

## 4. The Fatal Flaw

**The #1 reason this specific founder will fail at this specific idea:**

**ProofPoint is a direct assault on a market dominated by four well-funded unicorns (HackerRank, Codility, Karat, Turing) with no defensible wedge that survives first contact with their competitive response.** Siddharth's strengths --- product taste, UX design, CXO network, cross-border positioning --- are real but categorically insufficient against incumbents who have spent a combined $400M+ building assessment platforms, employer relationships, and candidate pools. Every feature in ProofPoint's spec (simulated assessments, AI proctoring, portable scores) is either already shipping or actively being built by these companies. The founder's distribution edges (PES University, Bangalore CXO network) are geographically narrow and cap out at 20-50 customers before requiring a GTM engine that competes head-to-head with enterprise sales teams at Karat and HackerRank.

The fatal flaw is not that the problem is fake. AI resume spam is a genuine, worsening crisis. The fatal flaw is that **Siddharth would be the 5th entrant in a market where the first 4 have raised a combined billion dollars, and his only differentiation is "I'll do it with better UX from Bangalore."** That's not a company. That's a feature request filed against HackerRank's product roadmap. Triplebyte proved that even with elite Silicon Valley networks, Y Combinator backing, and $50M in funding, the "replace the resume with verified skills" thesis couldn't achieve escape velocity. ProofPoint has less capital, less network, less technical depth, and faces a strictly harder competitive landscape than Triplebyte did.

---

## 5. Final Verdict

## **KILL**

This is a kill, not a pivot, because the competitive dynamics are structural and unfixable by repositioning. The hiring assessment market has consolidated around well-funded incumbents who are already shipping AI-era features. No pivot within this space avoids the competitive problem.

### Why Kill, Not Pivot:

1. **The Triplebyte post-mortem is definitive.** The highest-pedigree version of this exact thesis --- pre-verified talent with portable scores that let employers skip early-round interviews --- was executed by a Y Combinator insider with $50M and failed. The failure was not execution. The failure was that employers structurally refuse to outsource hiring judgment to a third party. This is a behavioral barrier, not a product problem, and ProofPoint offers no mechanism to overcome it that Triplebyte didn't already try.

2. **Four unicorn-class incumbents occupy every viable positioning.** General assessment (HackerRank, Codility). Interview-as-a-service (Karat). Pre-vetted India-to-US talent (Turing). ProofPoint cannot find a positioning niche that isn't already owned by a company with 100x more capital. "Better UX" is not a moat against a $500M competitor --- it's a 6-month feature cycle for their design team.

3. **The blockchain "Skill Passport" is dead weight.** No employer in the hiring ecosystem has ever expressed demand for on-chain credential verification. This feature adds technical complexity, confuses the value proposition, and signals to investors that the founder is chasing buzzwords rather than solving real buyer problems. Remove it, and ProofPoint becomes a generic assessment tool. Keep it, and ProofPoint becomes an un-fundable blockchain play in a market that has aggressively rejected blockchain-based credentials for 7 consecutive years.

4. **The AI proctoring arms race is unwinnable.** Detecting AI assistance in coding assessments is a technically losing proposition. AI is moving into the IDE itself (Copilot, Cursor, Claude Code). Within 12 months, "AI-assisted coding" will not be cheating --- it will be the standard operating mode for professional developers. Building a proctoring moat against a behavior that is rapidly becoming the norm is investing in a melting ice cube.

5. **The founder's actual edges are wasted on this battlefield.** Siddharth's CXO network, cross-border positioning (US Citizen in Bangalore), product/UX instincts, and design taste are genuine competitive advantages. But in a market where the buyer (HR/engineering manager) is already saturated with assessment vendor pitches, these advantages get no oxygen. The CXO network gets 20 pilot meetings. Then what? Enterprise sales at scale against HackerRank's 50-person sales team? This market demands enterprise GTM muscle that a solo founder cannot manufacture.

### What to Salvage:

The *insight* that "AI has destroyed the resume as a trust signal" is correct and timely. But the response should not be "build a better assessment platform" (solved, funded, competitive). If Siddharth is drawn to the future-of-work space, he should look for problems where:

- **(a)** The incumbents are slow or non-existent (not a market with four unicorns).
- **(b)** His specific cross-border positioning (US Citizen + Bangalore) is a structural advantage, not just a nice-to-have.
- **(c)** Product/UX excellence is the primary moat (not infrastructure, data network effects, or enterprise sales execution).
- **(d)** The buyer is underserved by current tools (not oversaturated with vendor pitches).

Examples of adjacent spaces that fit these criteria better: tools for async-first remote team collaboration, cross-border contractor compliance/payments for small companies (below Deel's ICP), or AI-powered internal skills mapping for companies trying to redeploy existing talent instead of hiring externally. These are upstream or adjacent to the hiring problem, face less entrenched competition, and align more naturally with the founder's product-and-design-led approach.

---

*Council Signed: The Cynical VC, The GTM Hustler, The Domain Expert, The Technical Pragmatist*
*Evaluation Date: 2026-04-21*
