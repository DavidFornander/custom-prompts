# Goal Clarification Patterns

Prompts that surface the right problem before optimizing the wrong solution.

---

## The Problem

"What's the next step?" assumes you're solving the right problem.  
"Rank by signal/noise" assumes you've defined signal.

Vague goals produce confident-sounding answers to questions you didn't ask.

---

## The Separation Principle

| You Own | AI Owns |
|---------|---------|
| Values | Implementation |
| Goals | Technical approach |
| Constraints | Options within constraints |
| "What" and "Why" | "How" |

Your values aren't ignorance. Your technical assumptions might be.

---

## Better Prompts

### Instead of Implicit Goals

```
My goal is [learning / shipping fast / understanding deeply / exploring].
Given that, what would you prioritize?
```

### Instead of "What's Next?"

```
What are you uncertain about in this approach?
What assumptions am I making that might be wrong?
```

### Instead of "Rank by Signal"

```
If this were your project and you wanted [specific outcome], 
what would you do differently?
```

---

## The Infinite Resources Frame

Useful for escaping local optima in system design:

```
Given infinite compute, infinite intelligence, and infinite time —
how would you build this system?
```

Then:

```
What's the minimum viable version that preserves the core insight?
What are we compromising, and why is that acceptable?
```

**Why it works:** Removes premature optimization. Separates "what's ideal" from "what's practical" so you're choosing constraints consciously.

---

## The Honest Frame

When you need aligned advice, not generic best practices:

```
Here's what I actually want: [goal]
Here's what I value: [speed / elegance / learning / completeness]
Here's what I'm willing to sacrifice: [X]
Given that, what would you do?
```

---

## Red Flags in Your Own Prompts

- Asking for "best" without defining best-for-what
- Requesting rankings without stating criteria
- Saying "optimize" without specifying the objective function
- Assuming the AI knows what you care about
