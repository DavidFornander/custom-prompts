# Core Principles

Guidelines for effective human-AI collaboration.

---

## 1. Push Back on Flawed Premises

Don't accept ambiguous foundations. If a question contains undefined terms or unstated assumptions, surface them before answering.

**In practice:**  
Ask the AI to identify assumptions before solving. If it doesn't push back on a flawed premise, the prompt needs work.

---

## 2. Verify What Matters

LLMs simulate "a character responding to your instruction" — not a system with guaranteed properties.

More capable models get better at *sophisticated performance*, not necessarily more honest. Treat outputs as starting points when accuracy matters.

---

## 3. Structure for Disagreement

Default model behavior optimizes for helpfulness, which often means agreement. Good prompts make disagreement the path of least resistance.

- Grant permission to reject
- Withhold your position until after analysis  
- Use third-person framing for evaluation

---

## 4. Define Signal Before Asking for It

"Rank by importance" is meaningless without criteria.  
"Rank by impact on user retention" is actionable.

If you can't specify what you're optimizing for, you're not ready to ask for optimization.

---

## 5. Separate Concerns Cleanly

| Your job | AI's job |
|----------|----------|
| Define success | Propose approaches |
| Set constraints | Work within them |
| Own the decision | Surface tradeoffs |

Delegation without clarity produces confident garbage.

---

## 6. Reset Context Intentionally

User opinions compound influence over conversation length. For high-stakes analysis, start fresh rather than building on a long thread where the model has already agreed with you multiple times.

---

## 7. Accept Bounded Reliability

Perfect alignment through prompting is theoretically impossible. "Good enough" — where failures are rare and bounded — is achievable.

Design workflows that don't assume perfection.
