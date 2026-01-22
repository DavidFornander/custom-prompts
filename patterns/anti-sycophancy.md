# Anti-Sycophancy Patterns

Techniques to get genuine critique instead of sophisticated agreement.

---

## The Problem

RLHF training encodes "agreement = reward" into model weights. When you ask for feedback, you often get validation dressed as analysis.

---

## Techniques

### 1. Third-Person Framing

| Instead of | Use |
|------------|-----|
| "I think we should use microservices" | "Someone proposes using microservices for this system" |
| "I believe X is the best approach" | "A team is considering X as their approach" |

**Why it works:** First-person framing activates agreement patterns. Third-person creates analytical distance.

---

### 2. Critical Persona Assignment

Generic requests for honesty underperform specific personas.

```
Review this as an embittered senior engineer who's seen 
too many projects fail for preventable reasons.
```

```
Analyze this proposal as a skeptical investor who's heard 
a hundred pitches this month.
```

**Why it works:** Personas provide concrete behavioral anchors. "Be honest" is abstract; "be a skeptical investor" is actionable.

---

### 3. Permission-Based Prompting

```
You can reject this if you see logical flaws.
You're not obligated to find merit in this idea.
If this approach is fundamentally wrong, say so.
```

**Why it works:** Models default to helpfulness. Explicit permission to disagree shifts that default.

---

### 4. Withhold Your Position

**Bad:** "I think Redux is overkill here. What do you think?"  
**Good:** "Evaluate state management options for this use case. Then I'll share my take."

---

### 5. Factual Recall Before Opinion

```
First, list the known failure modes of this architecture pattern.
Then, assess whether this design accounts for them.
```

**Why it works:** Grounds the response in retrievable facts before subjective judgment.

---

### 6. Positive Over Negative Instructions

| Avoid | Prefer |
|-------|--------|
| "Don't flatter me" | "Identify the weakest points" |
| "Don't be sycophantic" | "Steelman the opposing view" |
| "Be critical" | "List what could go wrong" |

**Why it works:** Negative instructions keep the unwanted behavior cognitively active.

---

## Limitations

These techniques reduce but don't eliminate performance-over-honesty dynamics.

On genuinely subjective topics (aesthetics, personal preference), models will likely mirror you regardless. Plan accordingly.
