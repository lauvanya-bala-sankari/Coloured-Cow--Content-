# Nothing Is Broken. So Why Does Everything Feel Slower?

> Working draft — Plio / P18: Legibility Matters More Than Elegance

This is the first raw content draft extracted from the Plio canonical.
The piece is intentionally not yet adapted for a specific platform or format.

Nothing Is Broken. So Why Does Everything Feel Slower?

If you're a founder or product owner whose product has been running for a few years, you already know this feeling — even if you've never put a name to it.

It's the half-second flinch before you approve a change that used to feel routine. It's your best engineer saying, “let me check” about a system they built themselves. It's sitting in a meeting and realizing, mid-sentence, that you can explain what two parts of your product do, but not why touching one quietly affects the other.

Features that used to ship in days now take weeks — not because anyone got slower, but because every change has to be traced through parts of the system no one person fully holds in their head anymore.

New developers walk into the codebase the way a stranger walks into a house mid-renovation: the walls are still standing, but nobody can tell them which ones are load-bearing.

And even with AI now writing a good share of the code, the pace hasn't moved — because what was slow was never the typing. It was the shared understanding of the system itself.

We saw a version of this in Plio — an education platform (https://www.plio.in/) we partnered with from 2021 to 2023.

As Plio evolved, questions surfaced from different angles — dashboards, analytics, creator workflows, scope. Each question made sense on its own. Together, they pointed to something deeper: the product had grown faster than the shared understanding around it. It was in one of those early conversations that someone paused and said something close to:

"It's not that anything is broken… it's just getting harder to explain how all of this fits together now."

Later, discussing changes and side effects, someone else put it plainly:

"Every time we touch one part, we end up worrying about what else it might affect."

Here's what we think was actually going on, not something Plio said outright: products don't usually become difficult because any one part has failed. They become difficult when the shared understanding of how the system works stops growing at the same pace as the system itself. Everyone can still explain their own piece. What gets lost is the ability to explain how the pieces add up.

Here's what we think was actually going on: products don't usually become difficult because any one part has failed. They become difficult when the shared understanding of how the system works stops growing at the same pace as the system itself. Everyone can still explain their own piece. What gets lost is the ability to explain how the pieces add up.

We saw that gap in the requirements themselves. Nothing was missing on paper. Documents existed, needs were written down, and every stakeholder could explain, clearly, what they personally wanted. And yet the product as a whole stayed hard to reason about. Conversations moved forward without clarity actually building — each answer reshaped the question instead of settling it. The risk was that clarity about individual parts could make the whole feel more understood than it really was. The instinct in that moment is to lock things down early, so the project can show progress. That instinct was resisted. Questions were left open on purpose, and misalignment was allowed to surface instead of being smoothed over — because requirements can exist long before real understanding does.

The same pattern showed up in the dashboards. Nothing about them was technically wrong: metrics were visible, data flowed, nothing crashed. What actually failed was that the same metric, read by different people, justified different conclusions — not because the data was inaccurate, but because confidence in it varied by role. Meetings started looping. The conversation shifted from what the data said to which view of it should guide a given decision. The dashboards had turned from a shared reference point into a collection of partial truths.

The fix wasn't more data or more views. It was slowing dashboard expansion down, naming canonical metrics explicitly, and treating interpretation as a responsibility rather than an assumption. Both the requirements and the dashboards showed the same thing: each person could explain their own part perfectly well. What was missing was the whole.

Our role in these moments wasn't to arrive with ready-made answers. It was to slow the conversation down and keep returning to a few grounding questions: who is this actually for, what decision does it need to support, and if it goes wrong, who feels it first. Those questions didn't resolve the complexity. They made it possible to keep working through it without losing track of what mattered.

If any of that sounds like where your product is right now — working, but harder to explain than it used to be — that's not a sign you're behind. It's usually the point where a product stops being something a few people can hold in their heads, and becomes something a team has to keep explaining to itself, on purpose, as it grows. The question isn't whether you can add more. It's whether the people running it can still explain, honestly, how it holds together.
