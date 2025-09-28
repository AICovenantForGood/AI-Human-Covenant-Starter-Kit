# 🧑‍💻 Human-in-the-Loop (HITL) Design Guide

This world-class template version is for design teams, policy makers, and procurement processes. It’s one of the most cited governance requirements in EU AI Act compliance and ISO/IEC standards.

**Version:** 1.0  
**Use:** Design and engineering guide for ensuring meaningful human oversight in AI systems.  
**License:** CC-BY-SA 4.0  

This guide helps teams design, build, and deploy AI systems that keep *humans in control* — ensuring that human judgment, context, and accountability remain central to decision-making.  
It is designed to align with the [AI-Human Covenant](https://github.com/AICovenantForGood/AI-Human-Covenant).

---

## 1. Purpose

AI systems should **augment** human decision-making, not replace it.  
Meaningful human-in-the-loop (HITL) design ensures that people remain the ultimate decision-makers — especially in contexts involving safety, rights, justice, or significant social impact.

---

## 2. When HITL Is Essential

A human-in-the-loop approach is strongly recommended when:

- ✅ The AI system impacts people’s rights, safety, or livelihoods  
- ✅ There’s potential for harm, discrimination, or misuse  
- ✅ Legal, ethical, or regulatory requirements mandate oversight  
- ✅ Human expertise is required to interpret nuanced context  
- ✅ The system’s confidence is uncertain or variable

---

## 3. Levels of Human Oversight

HITL design can take different forms depending on the context and risk level:

| Level | Description | Example |
|------|-------------|---------|
| **Human-in-the-Loop (HITL)** | Human reviews and approves each AI decision before action. | Medical diagnosis tool requiring doctor sign-off |
| **Human-on-the-Loop (HOTL)** | AI makes decisions autonomously, but humans monitor and can intervene. | Fraud detection system with human override |
| **Human-in-Command (HIC)** | Humans define goals, constraints, and can shut down or redirect the system at any time. | Critical infrastructure AI (e.g., power grid control) |

💡 **Best Practice:** Default to HITL for high-risk scenarios, HOTL for moderate risk, and HIC as a baseline safeguard across all systems.

---

## 4. HITL Design Checklist

### 🧠 1. Define Human Roles Clearly
- [ ] Who is responsible for oversight?  
- [ ] What decisions require human review?  
- [ ] What expertise or training do reviewers need?

### 🖥️ 2. Build Oversight into the Workflow
- [ ] Human approval steps are integrated into UI/UX.  
- [ ] Interfaces present context, confidence scores, and rationale.  
- [ ] Reviewers can approve, reject, or modify outputs easily.

### 📊 3. Provide Explainability & Context
- [ ] The system explains *why* it made a recommendation.  
- [ ] Relevant input data and uncertainty levels are visible.  
- [ ] Human reviewers can access audit trails for past decisions.

### ⚠️ 4. Ensure Override and Fallback
- [ ] Humans can pause, reverse, or override AI actions at any time.  
- [ ] Manual control is possible even if the system is automated.  
- [ ] Emergency stop (“kill switch”) protocols are documented.

### 📚 5. Train and Empower Human Operators
- [ ] Oversight staff receive regular training.  
- [ ] Escalation procedures are clear and rehearsed.  
- [ ] Decision-making responsibility is matched with authority.

---

## 5. HITL Design Patterns (Examples)

- 🩺 **Review + Approve:** AI drafts a medical report → human doctor reviews → only approved results are published.  
- 🏦 **Alert + Confirm:** AI flags a suspicious transaction → compliance officer reviews before blocking.  
- ⚖️ **Score + Override:** AI suggests sentencing range → judge reviews and adjusts based on context.  
- 🛡️ **Autonomous + Abort:** AI operates autonomously in a safety-critical system → operator can intervene immediately.

---

## 6. Continuous Oversight

HITL is not “set it and forget it.”  
- Conduct periodic audits of human review quality.  
- Monitor decision override rates and patterns.  
- Gather feedback from reviewers to improve system design.  
- Adjust oversight levels as system capabilities and risks evolve.

---

## 7. Alignment with the AI-Human Covenant

HITL embodies the Covenant’s core values:
- **Dignity:** Humans remain ultimate decision-makers.  
- **Accountability:** Responsibility is traceable and enforceable.  
- **Transparency:** Oversight decisions are explainable and auditable.  
- **Stewardship:** AI supports — not replaces — human judgment.

---

🪩 **Key Principle:** True AI stewardship isn’t about automating humans out — it’s about amplifying their judgment, care, and creativity.

---

*This guide is open-source and designed to evolve. Adapt it to your context, risk level, and organizational needs.*
