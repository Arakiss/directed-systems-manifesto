# Directed Systems

## On Human-AI Collaboration in the Age of Autonomous Agents

Something is shifting in how work gets done. This document attempts to synthesize what we know from research, acknowledge what we do not know, and offer a framework for thinking about it.

We make no claim of discovery. The question of how humans and machines collaborate has been studied since 1951. What follows draws heavily from that research.

---

## Part I: What We Know

### The Seventy-Year Question

In 1951, Paul Fitts published the first systematic comparison of human versus machine capabilities for the US Air Force. His question was simple: what should humans do, and what should machines do?

That question has never been satisfactorily answered.

Lisanne Bainbridge, in her landmark 1983 paper "Ironies of Automation," documented why simple task allocation fails:

> "The more advanced a control system is, the more crucial may be the contribution of the human operator."

Her ironies remain unsolved:

1. **The monitoring problem.** Humans are poor at monitoring automated systems. Vigilance degrades. When the system finally needs intervention, the human is least prepared to provide it.

2. **The skill decay problem.** Automation removes opportunities for practice. The skills needed to handle system failures atrophy precisely because the system rarely fails.

3. **The difficulty transfer problem.** Automation typically handles routine cases, leaving humans with only the exceptions. This does not reduce workload; it concentrates difficulty.

4. **The designer error problem.** We focus on "human error" but rarely discuss errors in automation design. The designer's mistakes become embedded in the system.

In 2002, Sidney Dekker and David Woods named the core fallacy: the "substitution myth." The belief that machines can replace human tasks without changing the nature of work itself.

This myth persists. It is wrong.

### The Levels of Automation

Thomas Sheridan and William Verplank (1978) proposed that automation is not binary. There are levels, from "human does everything" to "machine does everything autonomously."

The interesting space is in between: systems where machines and humans share control in various configurations.

"Directed Systems" refers to configurations toward the higher end of this spectrum, where the AI system holds significant decision-making authority while humans retain execution, oversight, or veto power.

This is not a new concept. It is a region of Sheridan and Verplank's framework that is becoming increasingly relevant as AI capabilities expand.

### What Current Research Shows

Stanford's WORKBank study (2025) surveyed 1,500 workers across 104 occupations. Key findings:

- By early 2025, workers in 36% of occupations were using AI for at least 25% of their tasks.
- The dominant pattern is neither full automation nor pure human work. It is collaboration.
- The shift in valuable skills is from information processing toward interpersonal capabilities.

This aligns with Sam Altman's 2021 observation: "AI will cause the price of work that can happen in front of a computer to decrease much faster than the price of work that happens in the physical world."

The data supports this. Work that requires physical presence, trust-building, and contextual judgment retains value. Work that is primarily information processing faces pressure.

### The Centaur Evidence

After losing to Deep Blue in 1997, Garry Kasparov created "advanced chess": humans and computers playing together.

The notable result from freestyle tournaments (2005): amateur players with ordinary computers, who had developed effective collaboration methods, defeated both grandmasters and superior hardware.

This "centaur" pattern appears elsewhere. Mayo Clinic's radiology department grew by 55% between 2016 and 2025 while deploying over 250 AI models. The AI handles measurement and detection; humans handle diagnosis and patient interaction.

The pattern suggests that effective human-AI collaboration can outperform either alone, but only when the interface is well-designed and the human understands how to work with the system.

---

## Part II: What We Propose

The following is not derived from the research above. It is a framework we propose for thinking about human-AI collaboration in directed configurations. It should be evaluated on its usefulness, not treated as established fact.

### Why "Directed"?

We use "directed" to describe systems where:

- An AI system makes operational decisions within defined boundaries
- Humans define those boundaries, execute physical actions, and provide oversight
- The flow of decision-making runs primarily from system to human at the operational level

This is distinct from "assisted" systems (where AI supports human decisions) and "autonomous" systems (where humans are removed from the loop entirely).

### A Proposed Structure

We suggest that directed systems can be understood through five functional roles. These are not components to be built, but lenses for analysis:

**1. The Autonomous System**

The AI that processes information, identifies opportunities, and generates directives. In current implementations, this might be an LLM with tool access, a multi-agent system, or purpose-built automation.

**2. The Boundary Definition**

The constraints within which the system operates. What decisions it can make. What actions are prohibited. What values are non-negotiable. This is where human authority must be absolute and explicit.

**3. The Translation Layer**

How system-level decisions become human-executable actions. A directive like "increase customer retention" must become specific, concrete steps. This translation is often where systems fail.

**4. The Human Executor**

The person who acts in the physical and social world. They execute directives, but also exercise judgment: recognizing when a directive is wrong, impossible, or requires escalation.

**5. The Learning Mechanism**

How the system improves from results. The human does not merely complete tasks; they provide information that refines system behavior. This feedback is valuable and should be treated as such.

### Three Points of Human Leverage

If this framework is useful, it suggests three places where humans retain significant power:

**Boundary-setting**: Whoever defines the constraints controls what the system can and cannot do. This is architectural power.

**Execution choice**: The system can direct, but cannot force. The human who executes retains veto power, whether explicit or through inaction.

**Feedback quality**: The system learns from what humans report. Accurate feedback improves the system; poor feedback degrades it.

### The Legibility Requirement

One lesson from automation failures (Boeing 737 MAX, Tesla Autopilot incidents) is that opacity kills.

When humans cannot understand what a system is doing or why, they cannot:
- Calibrate their trust appropriately
- Recognize when intervention is needed
- Provide useful feedback for improvement

A directed system that humans cannot understand is not a collaboration. It is a liability.

---

## Part III: What We Do Not Know

Intellectual honesty requires acknowledging gaps:

**We do not know if directed configurations are stable.** They may be a transitional phase between human-led and fully autonomous systems. The window during which humans are necessary for execution may be shorter than expected.

**We do not know if the centaur pattern generalizes.** Chess and radiology may be special cases. The conditions for successful human-AI collaboration may be narrower than the optimistic reading suggests.

**We do not know how to solve Bainbridge's ironies.** Forty years of research has not produced reliable solutions to skill decay, monitoring failures, or difficulty concentration. Our framework does not solve them either.

**We do not know if "human in the loop" provides real safety.** Critics argue it often functions as what Madeleine Clare Elish calls a "moral crumple zone": humans absorb blame when systems fail, without having meaningful control.

**We do not know the labor implications.** Whether directed systems create, transform, or eliminate jobs at scale is an empirical question we cannot answer from first principles.

---

## Part IV: Practical Implications

If the framework above is useful, some implications follow:

### For Individuals

The shift from information-processing skills to interpersonal and physical skills appears real. This suggests:

- Developing capabilities AI handles poorly: building trust, reading context, physical manipulation in unstructured environments
- Understanding how AI systems work well enough to collaborate effectively
- Recognizing that "working with AI" is becoming a skill category of its own

### For Organizations

Deploying AI in directed configurations requires attention to:

- Boundary definition: being explicit about what the system can and cannot decide
- Translation quality: ensuring system outputs become executable human actions
- Feedback mechanisms: treating human input as valuable data, not compliance checkbox
- Legibility: ensuring humans can understand system behavior well enough to intervene

### For Researchers

Open questions include:

- Under what conditions does human-AI collaboration outperform either alone?
- How do we measure the quality of human-AI interfaces?
- Can Bainbridge's ironies be mitigated in directed configurations?
- What determines whether humans retain meaningful agency in high-automation environments?

---

## Sources

This document draws from:

- Fitts, P.M. (1951). "Human engineering for an effective air navigation and traffic control system." Ohio State University Research Foundation.
- Sheridan, T.B. & Verplank, W.L. (1978). "Human and Computer Control of Undersea Teleoperators." MIT Man-Machine Systems Laboratory.
- Bainbridge, L. (1983). "Ironies of Automation." Automatica, 19(6), 775-779.
- Dekker, S.W.A. & Woods, D.D. (2002). "MABA-MABA or Abracadabra? Progress on Human-Automation Co-ordination." Cognition, Technology & Work, 4, 240-244.
- Elish, M.C. (2019). "Moral Crumple Zones: Cautionary Tales in Human-Robot Interaction." Engaging Science, Technology, and Society, 5, 40-60.
- Shao, Y. et al. (2025). "Future of Work with AI Agents: Auditing Automation and Augmentation Potential." Stanford Digital Economy Lab.
- NASA (2023). "Analyses of the Boeing 737-MAX Accidents: Formal Models and Psychological Perspectives."
- McKinsey Global Institute (2025). "Agents, robots, and us: Skill partnerships in the age of AI."

---

*Directed Systems v0.1*
*January 2026*

Petru Arakiss
