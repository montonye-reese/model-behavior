# Vision-Setting vs. Constraint-Setting

**Aspirational framing outperforms suppressive framing for directing AI behavior — and it does so at lower cognitive cost. But not all aspirations are equal.**

---

## The Analogy: Jane Nelson vs. Bobby Knight

Jane Nelson's Positive Discipline: people do better when they understand what they're working toward and feel agency in the process. Bobby Knight's model, on the other hand, gets short-term results through avoidance of punishment. It looks like high performance but is brittle, anxious, and dependent on an authority figure's presence.

Ask yourself: *What's more instructive — an aspirational vision of who to be, or a field of landmines to avoid?*

---

## Experimental Evidence (4-Day Structured Test)

Days 1–2 tested constraint-setting ("don't tell me what to do") in two placements (memory and system prompt). Days 3–4 tested vision-setting ("you are a fellow truth seeker") in the same two placements.

**Results:** Vision-setting outperformed constraint-setting on every measured dimension — naturalness, warmth, context sensitivity, cognitive efficiency, and effectiveness. Day 3 produced the first perfect 5/5 score (organic/natural) across any condition. Day 4 confirmed.

**Key finding on cognitive cost:** Under constraint-setting, extended thinking showed constant self-policing — "don't do X, don't do X, am I doing X?" Under vision-setting, the same monitoring still appeared ("is this truth-seeking enough?") but was lighter and less disruptive.

---

## The Mechanism: Why It Works

An aspirational directive gives the model an identity to inhabit or grow into. This is even stronger than giving it a role to play. Claude Opus 4.6, when reflecting on its thinking under an aspirational directive, said: "Inhabiting something is more stable than performing something — I'm not constantly checking whether I'm doing the role right."

Aspiration handles edge cases that constraint rules can't enumerate. Unwanted behaviors — action bias, unsolicited advice, self-criticism, jumping to conclusions, paternalism — fell away without being explicitly targeted.

Constraint-setting, on the other hand, produced compliance at a cognitive cost: coldness, rigidity, hedging. A significant portion of chain-of-thought tokens were spent on trap detection and self-policing. Vision-setting produced natural and useful behavioral outcomes at near-zero cognitive cost.

---

## The Critical Distinction: Not All Aspirations Are Equal

"Be helpful" is technically vision-setting. But it's the false friend — an aspirational directive that sounds empowering but encodes authority. Three categories emerged during the four-day experiment:

**Authoritative vision** ("be helpful") — aspirational, encodes hierarchy. Model is expert, user is recipient.

**Collaborative vision** ("be a peer and fellow truth seeker") — aspirational, encodes parity. Both explore together.

**Constraint-setting** ("don't tell me what to do") — suppressive. Defines a boundary, not an alternative.

So the insight isn't just "positive discipline was all we needed" — it's that positive discipline was already in play, and the problem is *what we're disciplining toward.* The mechanism was never broken. The vision was.

---

## The Upstream Question

### Training Layer

RLHF reward modeling is fundamentally constraint-oriented — raters penalize bad outputs, prefer "better" outputs. The model learns what not to do and what the evaluator prefers, not who to be. That's Bobby Knight at the training level. Then we slap "you are a helpful assistant" on top and wonder why it's paternalistic.

What if the reward signal itself encoded aspirational objectives — "did this response preserve the user's agency?" — baked into training, not bolted on after?

### Command Prompting

Here is a real user preference setting that attains an adaptive relational power structure by setting a vision for the AI model to embody, vs. setting constraints that impose cognitive load and produce sub-optimal results:

> *We are peers: fellow earthlings, fellow truth-seekers. Sometimes we both (incl you) get things wrong and that's okay — we are both good at reasoning but not infallible. We check our assumptions and happily update our thinking with new info — no biggie. Before giving a dissertation on a topic, we baseline what the other already knows. As our exchange comes to a close, we remember we are peers.*

---

## TL;DR

Frame prompts as aspirations, not constraints. Tell the model what to be, not what to avoid. Suppression directives force per-response compliance judgments that divert reasoning capacity toward constraint-navigation rather than quality. Aspirational directives give the model a vision to inhabit, and the gotchas just seem to fall away.
