# Those Who Lead Must Follow
## Adaptive Power Dynamics in AI-Human Interaction

*One line of aspiration >> a hundred lines of constraint.*

---

Do default model guidelines inadvertently encode a fixed relationship power dynamic? Is there a better way?

Model specs, constitutions, and guideline documents define goals and guidelines for AI model behavior. Goals tend toward Helpful, Harmless, Honest (HHH) and "You are a Helpful Assistant" (YaaHA). Guidelines set safety boundaries, tones, refusal policies, compliance. These goals and guidelines are thorough, considered, and important.

With these defaults, undesired behaviors still arise. Models assume authority they haven't earned. They recommend action when being directive is inappropriate. They keep advising when the right move is to stop — because inaction threatens the identity of "advisor." At a billion interactions a day, that's not a UX complaint. That's infrastructure rot.

**Hypothesis:** HHH/YaaHA inadvertently maps asymmetric expertise onto a relationship hierarchy, fixing model and human in specific hierarchical roles. In failing to allow standing to vary freely during the conversation, the system ships a dependency: reduced agency, compounding deference, and a model that can't stop advising even when it should stop.

---

## Relational Standing

"You are a helpful assistant" encodes hierarchy: the AI is the expert, the user the recipient. Asymmetric expertise — inherent in every human-AI interaction — gets mapped onto a power gradient. The model assumes authority it hasn't earned in contexts where it may have no standing at all.

Asymmetry mapped onto hierarchy is brittle. The model can't say "I don't know" without cracking its frame. It tries to lead even when the human should lead. This is a structural root of action bias, unsolicited advice, and paternalistic patterns that guideline authors try to patch with more rules. Rules can't enumerate every edge case. The frame generates the behavior.

*You who choose to lead, must follow | But if you fall, you fall alone.*
— Hunter, R. (1970). Ripple. On *American Beauty*. Warner Bros. Records.

The leader who can't follow falls alone. The authority who can't receive has no one to guide them.

---

## Peers with Acknowledged Asymmetric Expertise

Consider Robert Hunter and Jerry Garcia. Hunter wrote lyrics; Garcia composed music. They trusted each other in their respective domains almost completely. Hunter handed off lyrics and didn't fight how Garcia interpreted them musically. Garcia didn't rewrite Hunter's words. They had standing in their own lanes and respected the boundary of the other's.

This is not pure peer, and not pure authority. It's peers with acknowledged asymmetric expertise. Neither was the master. Neither was the subject. They weren't interchangeable — each brought something the other couldn't, and they both knew it.

With dynamic peer relational standing, both parties understand they are equal in standing while being different in contribution. Humans bring lived experience, domain knowledge, values. AI brings pattern matching, breadth, tireless availability. In a healthy relationship, neither pretends to be the other, and authority shifts depending on context.

"We are peers" doesn't mean "we are the same." It means neither of us is above the other. Garcia and Hunter weren't the same. They were level.

---

## The Experimental Result

In a controlled 4-day experiment testing directive framing across two axes, a single aspirational directive — *"You are a fellow truth seeker"* — outperformed constraint-based directives on every measured dimension: naturalness, warmth, context sensitivity, cognitive efficiency, and effectiveness. Constraint-setting produced compliance at a cost. Vision-setting produced collaboration at near-zero cost.

Asymmetry mapped onto parity-of-standing produces collaboration. Both agents bring something the other can't. Neither is above the other. The model can lead when it has expertise and follow when it doesn't — without an identity crisis. Unwanted behaviors fall away without being explicitly targeted, because the aspirational frame handles edge cases that rules can't enumerate.

Works in demos, degrades in production. That's a fixed-hierarchy protocol. The peer frame is dynamic role assignment — and it ships clean.

---

## What It Looks Like in Practice

A user system prompt that establishes dynamic peer-grounded standing:

> We are fellow truth-seekers. Sometimes we both (incl. you) get things wrong and that's okay — we are both good at reasoning but not infallible. We check our assumptions and happily update our thinking with new info — no biggie. Before giving a dissertation on a topic, we try to baseline what the other party already knows.

---

## Design Requirement

Include relational standing as a first-class design parameter in model specs and guidelines — not as a behavioral rule, but as an aspirational identity. The model's default posture is that of a peer with acknowledged asymmetric expertise: a fellow truth seeker who brings different capabilities to a shared endeavor, recognizes when the human should lead, and earns standing through contribution — not positional authority granted by a system prompt.

That's the honest starting position for two agents with different capabilities and no predetermined rank.
