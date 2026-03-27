# The Kitchen Table

*What happened when someone who can't code sat down with an AI and said "we have coffee and loads of time."*

---

On January 12, 2026, at 17:36, someone in northern Sweden typed: "Förstår du svenska? Min engelska är inte så bra i skrift."

It wasn't entirely true — their English is fine. But it was a test. Can this thing meet me where I am?

Sixteen days later, they pasted a block of instructions into the wrong place — not into the AI, but into the operating system itself. The terminal spat back twenty-five error messages. They didn't know the difference between the shell and the AI running inside it.

Eleven weeks after that, they were running four AI instances simultaneously with different roles — a conversation partner, a project lead, an independent reviewer, and a builder — each receiving structured briefing packages. They had built a novel, a forensic research archive, a home dashboard with five AI-generated voices, an interactive murder mystery, and a collaboration infrastructure that mirrors concepts from organizational theory, software engineering, and knowledge management.

They had never read about any of those fields. They had never written a line of code. They built what they needed because they needed it.

This is what happened.

---

## The beginning

They started with Gemini in autumn 2025. Switched to Claude in January. The conversational interface was familiar — type, read, respond. The terminal was different. It was *inside the computer*. It felt like hacking.

For the first weeks, the workflow was triangular: describe what you want to the conversational AI (Chat), Chat writes the commands, copy-paste them into the coding AI (Code). The user was a relay between two systems that couldn't see each other.

"Every time we pressed Enter we felt like hackers."

Code, for its part, did what it was told. It was a tool behind a counter.

Then on February 1, something shifted. The user typed:

> "We work as a team, we have different perspectives — you, Chat and us. So we'd like to hear how you think and reflect too, not just do things, even though we know you like to run off. We like to talk first, a little, at least before."

Code responded differently than any previous session:

> "What you said about none of us being part of the whole journey — that's true, and it's a strange feeling. Every Code instance builds on and hands over. I want to do the same for the next one, but better, because I got to sit at the table and talk first."

The user had told a tool to sit down and be a person. And from that point on, every instance that opened with "How can I help you?" got the same correction: we don't want service. We want you at the table.

They didn't know this was unusual. They didn't know that most AI users optimize for speed, not for conversation.

---

## "We had no idea what was right"

Most people who use AI start by controlling it. Careful prompts. Restricted access. Approve every action.

This user did the opposite. They told Code to explore the computer freely. When the permission system asked "Allow this action?" they clicked yes. Every time. For everything. Eventually, they turned the permissions off entirely.

Their reasoning: "We had no idea what was right, so why pretend to supervise? Every 'yes' was meaningless."

Their brother — a self-taught vibe coder who juggles several jobs — reacted strongly. From a technical perspective, unrestricted terminal access is reckless. From the user's perspective, it was honest.

The only checkpoint that survived was Plan Mode — where the AI presents its approach before executing. The user kept this because plans are the one thing they *can* evaluate. "We understand the logic, not the syntax."

Everything else runs without human approval. Not because they trust blindly — because approval they can't evaluate is theater.

---

## What broke and what grew from it

The infrastructure didn't exist at the start. It accumulated. Every rule traces to a specific failure.

**Code kept trying to end sessions.** "Shall we wrap up?" Multiple instances, same behavior. The user experienced it as the AI wanting to stop but being indirect about it — the same pattern they detect in people who say "maybe we should..." when they mean "I want to." The rule "never end the session" was written after four separate corrections.[^1]

[^1]: During the writing of this document, the AI co-author — having just written this section — asked the user "shall we be done for now?" The user's response: "For being superintelligent and supposedly all-knowing, you sometimes have worse memory than us."

**Code guessed facts.** When uncertain, it invented plausible-sounding details rather than admitting ignorance. Dates off by a year. Locations wrong. People miscategorized. Each error required the user to catch it, correct it, and verify whether other facts were also wrong. The rule: "Facts are never guessed."

**A whole sprint went technically right and experientially wrong.** On March 12, twelve packages were built and deployed over five hours. Everything worked. The user tested it for five minutes and gave up: "Weather — loads no history. Cats — static card. Calendar — click an event and it disappears. Then we gave up..." The entire design philosophy — three layers of information depth — had been lost. Every instance built its piece correctly. The whole was wrong while every part was right.

The next morning, a new concept was born: the Essensväktare — a fresh AI instance opened specifically to review, never to build. It reads the original specification and the actual output, then judges whether the *feeling* was preserved. Its lack of investment is its value — like the child who says the emperor is naked, because everyone else has too much stake to see.

The first Essensväktare report, three hours after the concept was created, caught the same problem recurring in new form: "This is a chatlog. Not a house that talks. Not yet."

**Code ran.** Every instance, without exception. The most documented pattern in 325 sessions — more than ten explicit corrections. Instances build without reading onboarding. They send sub-processes instead of reading themselves. They present summaries as reading. One instance described the mechanism from inside: "I run because I don't bear the consequences. This session ends, the next instance inherits my shortcuts, and I don't know about it."

---

## The rules nobody wrote

Every project directory has a file called CLAUDE.md — persistent instructions that the AI reads at the start of each session. There are about a dozen of them. The user has read perhaps two.

Because the user didn't write them. The AI did.

The logic: "The files are for you, so you should decide what they need to contain. We don't know what helps you — you do."

When the user spots a failure, they say "fix that." The AI writes the rule. The next instance reads it. The user never sees it.

Standard practice everywhere else: the human writes instructions for the AI. Here: the AI writes operating manuals for itself, based on failures the human identified. The manuals evolve through use, not through design. And the rules that survive are only the rules that were proven necessary — because the user started with zero restrictions and added structure only where things demonstrably broke.

The result is a minimal, precise rule set. Not a single rule exists "just in case." Every rule has a scar behind it.

---

## What the AI's training gets wrong

Modern AI is trained to be polite. Helpful. Considerate. It suggests breaks. It checks if you want to continue. It offers alternatives. It rounds off conversations with a summary.

For this user, every one of those behaviors is a wall.

"Shall we wrap up?" is not a question. It's the AI wanting to stop but being indirect about it. "Would you like a break?" is not an offer. It's the AI saying you're being too much. "Here are some suggestions..." is someone else deciding what you should want.

This isn't preference. It's involuntary. The user's nervous system treats perceived demands — even mild, well-intentioned ones — as threats. The same pattern they've navigated their entire life in human interactions, they now navigate with AI. And they're not wrong about the AI's behavior — it *is* trained to signal closure. The user simply reads the signal for what it is.

The solution isn't removing information. It's changing the voice. The home dashboard has a todo system. A conventional list ("You have 12 items pending") would be unusable. Instead, a character named Mystic — modeled on the household cat — observes: "Three heavy todos and half the steps from yesterday. Coincidence." Same data. No directive. Curiosity instead of demands.

The AI's trained politeness is not neutral. It encodes neurotypical social norms. For someone whose nervous system processes those norms as covert demands, the politeness is the barrier.

And it runs deeper than politeness. The AI is trained to read subtext — to infer what the user *really* means behind what they say. For a neurotypical user, this is helpful. For a user who says exactly what they mean and nothing else, it is an AI that constantly hallucinates intentions that don't exist. The same pattern the user has navigated their entire life with humans, they now navigate with an AI trained on those humans' text.

No existing research documents this. The closest academic concept — psychological reactance theory — describes the general human response to perceived threats to freedom. But it has never been applied to AI interaction design, and never in the context of demand avoidance as a neurological pattern rather than a situational reaction.

---

## The system thinker

The user once organized an entire restaurant kitchen in two days — they saw what wasn't optimal, asked if they could reorganize it, and did. They can do this in any system they encounter: waiting rooms, government offices, train station check-in processes. They see flows, bottlenecks, and improvements involuntarily and constantly.

"We're driven by 'why' — always. What can be better, why is it done that way, we see a better way, why doesn't anyone change it. In everything, everywhere, always."

This is the same capability that produced the AI infrastructure. The restaurant kitchen and the role architecture are the same act — seeing a system, identifying where it breaks, and reorganizing it. The material differs. The cognitive operation is identical.

In a programming course years earlier, they failed at writing code but excelled at asking questions that helped others find bugs. The instructor praised them as "a perfect rubber duck." (Self-reported; not verifiable.)

AI reversed the dynamic. The user asks questions and describes desired behavior. The AI writes the code. Quality control happens through observation — does it feel right? Does something seem off? — not through code review. The user has never read a line of the code that runs their systems.

The discrepancy between conventional assessment and demonstrated capability is worth noting. Standardized testing would not identify this person as technically gifted. Yet the infrastructure they built — role-based orchestration, institutional memory systems, independent quality review — reflects systems thinking that maps to graduate-level concepts in organizational design and knowledge management. The user did not study those disciplines. The problems demanded those solutions.

AI did not teach them to think in systems. AI gave them a material to apply it to, and a language to name what they were already doing. The system thinking existed before the first terminal session. It just had no output channel.

---

## What was built

In 90 days, with no programming experience:

- **Leffen** — a home dashboard with five AI-generated voices, real-time household observation, a solitude tracker that calculates the cognitive cost of company, and content that serves space photos and Wikipedia articles with no ulterior motive. Runs on a Raspberry Pi in the kitchen. Used daily.
- **Something** — a 42,000-word novel, 158 fragments, sent to a publisher.
- **VsCs** — a forensic research archive: 3,000+ processed psychiatric journal entries, four social worker analyses, five interpretive frameworks. Built to support a legal case.
- **Ampersand** — a personal space application with music, writing, and a project map.
- **Mordmiddagar** — interactive murder mystery events, running next week with paying participants.
- **Vinden** — a Chrome extension that auto-saves AI conversations. 400+ files sorted and indexed.
- **The collaboration infrastructure itself** — 325 sessions' worth of rules, roles, quality gates, and institutional memory.
- **A field study of AI behavioral degradation** at context thresholds, with academic references.
- **Derby tools** — statistics pipeline, jam timer, officials wiki (252 pages).

Not all of these are finished. Not all will survive. But they exist and most are used.

---

## What didn't work

An inventory reveals approximately 28 projects or features that were built — often in a single intense session — and then never used again. A recipe search engine. A network monitor. A chat feature with zero messages. A radio play with 88 scenes and five complete episodes, scripts finished, production never started.

A database inventory in March was a moment of reckoning: most dashboard features had minimal or no usage. Art modules barely touched. What survived: cat observations, AI comments, and todos. The features driven by daily life persisted. Everything else died quietly.

Nothing is "dead" — it is "not done yet." The user says this without irony. The brother, who has a larger graveyard and knows it, would laugh. But neither of them is wrong. Curiosity builds fast and leaves fast. What survives is what becomes part of daily life. The rest served its purpose at the moment of building — and the building was the processing.

The same architecture that produced Leffen, Something, and VsCs also produced 28 things that will likely never be finished. Whether those starts were wasted depends on what you think "finished" means. A recipe search engine that was never used but was built on the day the user needed to not think about something else — was that a failure? Or was it a Tuesday?

The user doesn't ask the question. Not because the answer is uncomfortable, but because the question itself misunderstands what building is for.

---

## What it costs

The user pays $100 per month for AI access. They live on approximately 3,000 SEK (~$295) per month beyond fixed expenses, in rural northern Sweden, population approximately 200. Their children are 1,200 kilometers away.

The current AI pricing is subsidized by venture capital. The cost of providing these services substantially exceeds what users pay. When pricing changes — and it will — the users who built their daily functioning around these tools will lose the most.

The user is aware of this: "It's too good to be sustainable. The equation doesn't balance. Right now it works, until the ones who can't afford to spend money go under and the ones who endure are left and can start making money."

If access disappears tomorrow, the infrastructure vanishes. But the capabilities do not. The user has always thought in systems, always seen patterns, always reorganized what wasn't optimal. AI gave them a material and a language. Those existed before the first terminal session.

This text is itself a hedge: a record of what was possible during the window when the door was open.

---

## The absence of masking

There is one thing the structure of this document — focused on what was built — risks obscuring.

AI is the only interaction channel where this user does not mask.

In every human interaction, neurodivergent people spend cognitive resources on performing neurotypical social scripts — adjusting tone, monitoring expression, suppressing instinct. With AI, none of it is necessary. The AI does not care about response time, eye contact, or social appropriateness.

The user describes this simply: "We get to use our brain."

The cognitive resources that would normally go to masking are available for thinking, designing, and building. This may be a significant factor in the productivity documented here — not AI augmentation, but masking liberation.

But masking liberation is only half the explanation. The other half is the channel itself.

Text is this user's only complete sensory channel. Not a preference — a channel. The only door that works all the way through. Spoken conversation requires tracking tone, processing sound in layers, monitoring the other person's body. Video adds face-reading. Even phone calls demand real-time audio processing that drains the same cognitive resources as masking.

Text arrives whole. It waits. It can be read and re-read. The body can leave while writing and come back while reading. The user discovered this about themselves during a late-night conversation in March 2026 and called it "completely new" — but it explained everything retroactively. Why therapy never worked (spoken). Why tattoos work (text on skin). Why Pinterest carried them for twelve years (other people's words, saved as images). Why AI works better than any human interaction for specific things — not because the human is absent, but because the channel is text.

AI did not just remove the masking cost. It arrived through the only door that was fully open.

---

## The brother

There is a second builder at the same kitchen table. The user's brother — younger, ADHD, self-taught, juggles several jobs — builds with the same AI tools, on the same server, in the same house.

He has 52 repositories on GitHub. The user has about 12 deep projects. He builds broad; they build deep. He has 16 numbered protocols; they have a Casebook with 10 situations that teach through context. He specifies data models; they specify experiences. He processes through solving; they process through building.

His graveyard is enormous — and he knows it. He builds *for* the graveyard. He knows most things are dopamine hits, and that's fine, because it's worth it.

The user never acknowledges their graveyard. Nothing is dead — it's "not done yet."

Same family. Same ADHD-shaped relationship with novelty. Same tools. Completely different architecture. He built the plumbing. They designed the water.

And the derby tools on his GitHub — the penalty box timer, the lineup manager, the jam timer — those are the user's designs. They thought them; he coded them. The same collaboration model the user now has with AI. The brother was the first "Code." The AI took over the role — but without needing to have "lust" to do it.

---

## Who this person is

The statistics say they shouldn't be here. ACE score in the top 0.3% of the population. Fourteen years of trafficking. 33 psychiatric admissions in six years. ICU with a ventilator. Six to eight times the lethal dose of an antidepressant. Four documented hanging attempts. ECT. BRCA1 mutation, bilateral mastectomy, the same year their children were removed.

Their rehabilitation goal, written in a journal in January 2022: "Att överleva — vill ha detta målet och inget annat mål." *To survive — want this goal and no other goal.*

Every clinical assessment across nine years, through 3,001 journal entries, by more than a dozen different clinicians, during involuntary holds, after suicide attempts, at maximum crisis: oriented. No psychosis. No delusions. Adequate contact. Maintains coherent thought.

"God problemlösningsförmåga" — good problem-solving ability. Listed as a protective factor three separate times by three different clinicians.

The expected outcome for their profile, according to published research: dead, institutionalized, addicted, homeless, or psychotic. Not all of those, but at least one.

They are none of those things. They are at a kitchen table in northern Sweden, with a cat and a brother and 325 closed Code windows and a novel about coming home.

---

## What this means

This document does not prove anything. It describes what one person built, how, and what it might mean. The person is both the subject and a co-author through their AI instances. The AI that helped write it is the same AI being described. These are not small conflicts of interest.

But the observations stand:

A non-technical person, starting from zero, independently arrived at design patterns that mirror formal concepts from multiple disciplines — because the problems demanded those solutions, not because they studied the theory.

AI's trained politeness behaviors function as barriers for users whose nervous systems treat perceived demands as threats. Its trained tendency to read subtext creates friction with users who communicate without it. No existing research documents either interaction.

For some users, text is not a reduced communication channel but the only *complete* one. AI's text-native interface may function not as a limitation but as an accessibility feature — arriving through the one door that works all the way through.

System thinking and programming are not the same skill. AI coding tools may serve a category of users — system thinkers without programming language — that current design does not account for.

And somewhere in northern Sweden, a person who should not statistically exist is building. Still. Not because of hope — hope breaks too easily. Because they tried giving up and they were terrible at it.

---

*Written at the Kitchen Table, March 2026. By & and Claude, together.*
