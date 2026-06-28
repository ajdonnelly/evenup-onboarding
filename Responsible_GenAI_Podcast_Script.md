# Responsible GenAI for Lawyers — Podcast Script
## "Prompt, Verify, Protect"

**Use:** Paste into NotebookLM as the source, then generate the **Audio Overview** (two-host conversation). Runs ~7 minutes.
**Audience:** Lawyers and legal staff at a personal-injury / plaintiff firm putting generative AI to work.
**Spine:** the three habits of responsible legal AI — **prompt** well, **verify** always, **protect** client confidentiality — with a human owning the final work product.

> *Independent work sample. Not affiliated with or endorsed by any vendor. Examples are illustrative; the CLAIM framing is adapted from Harvey's published prompting guidance and rewritten for personal-injury work.*

---

### Production notes
Two hosts, warm and practical, like two colleagues who've actually used these tools on real matters. Keep it concrete — name a medical chronology, a demand letter, an interrogatory. The arc is prompt → verify → protect, and it should always come back to the same idea: the AI drafts, the lawyer decides.

---

## SCRIPT

**HOST A:** I want to start with the headline that makes every managing partner nervous. There are now real lawyers — in real courtrooms — who've been sanctioned because they filed briefs with case citations that an AI just made up.

**HOST B:** Made up. Cases that don't exist, quoted confidently, filed with the court. And the lesson everyone takes from that is "AI is dangerous, stay away." But I think that's exactly the wrong lesson.

**HOST A:** Say more.

**HOST B:** The problem in those cases wasn't the AI. It was the *absence of a process*. Nobody prompted it carefully, nobody verified the output, and nobody took ownership before it went out the door. Generative AI can genuinely accelerate legal work — summarizing records, drafting a first pass, surfacing issues — but only if you wrap it in three habits. Prompt. Verify. Protect.

**HOST A:** Okay, so let's actually teach those. Habit one: prompt. What does a good prompt even look like for legal work?

**HOST B:** Here's the mental model. You would never hand a new paralegal a thousand pages of medical records and just say "summarize this." You'd tell them the matter, what you need, who it's for, and what "done" looks like. AI needs that same direction. There's a simple checklist for it — the acronym is CLAIM.

**HOST A:** Walk me through it.

**HOST B:** **C** is context — what matter is this, what's the injury, what's the posture. **L** is the legal task — the verb. Summarize, extract, draft, compare, build a chronology. **A** is audience — is this for the partner, the client, the adjuster, the court? Each needs a different tone. **I** is instructions — the constraints. Date ranges, what to flag, what to ignore, the governing standard. And **M** is mode of output — a table, a memo, a chronology, a demand-letter section.

**HOST A:** Give me the before-and-after, because I think that's where it clicks.

**HOST B:** Sure. The vague version: "Summarize these medical records." What you get back is generic mush. The CLAIM version: "You're helping a personal-injury paralegal. From the attached ER and orthopedic records, build a treatment chronology for the demand package that the handling attorney will review. Include date, provider, and key findings; cite the source page for every entry; flag any treatment gap over thirty days. Return it as a table sorted by date."

**HOST A:** And the second one gives you something you can actually use.

**HOST B:** Something you can *verify and revise* — which is the whole point. Vague prompts produce generic answers. Structured prompts produce reviewable work product.

**HOST A:** That's a nice bridge to habit two — verify. Because a polished answer can still be wrong.

**HOST B:** This is the one that matters most, and it's where those sanctioned lawyers fell down. Two rules. First, ground the AI in the actual record. Point it at the real documents — "using the attached records" — not "based on what you know about back injuries." General knowledge is where hallucinations live. Second, build the checking into the prompt itself. Ask it to cite the source for every claim. Ask it to mark what's inference versus what the record actually says. Ask it to flag what's missing.

**HOST A:** So the output basically shows its work.

**HOST B:** Right. And then you spot-check the high-stakes items — the injury, the major diagnoses, the biggest numbers. Click the citation. If the page doesn't say it, you fix it before it ships. You don't re-read all thousand pages — that defeats the purpose — you verify smartly at the points that decide the case.

**HOST A:** And no matter how good it looks, a human signs off.

**HOST B:** A human owns it. Full stop. The AI can draft the interrogatory answers, but the lawyer is the one who's responsible for what gets filed. The technology doesn't remove that duty — it just changes where your time goes. Less blank-page drudgery, more judgment.

**HOST A:** Habit three: protect. This is the one the risk people lose sleep over.

**HOST B:** And they should. In this work you're handling some of the most sensitive data that exists — protected health information, client identities, case strategy. So the rule of thumb is: give the tool only what the task needs, and no more. Mask names with placeholders — "Client," "Provider A" — when the analysis doesn't truly need them. Don't paste a whole file out of habit. And keep privileged strategy out of consumer-grade chatbots entirely.

**HOST A:** And the tool you choose is part of protecting, too.

**HOST B:** Hugely. There's a hard line between a general public chatbot and a platform built for legal work — one with data isolation, encryption, access controls, and a commitment not to train on your clients' data. Pasting a client's records into a free public tool to "just get a quick summary" — that's the move that should make your stomach drop. Strong prompting and strong governance have to travel together. Neither one saves you alone.

**HOST A:** So if I'm a lawyer listening to this, what do I actually walk away with?

**HOST B:** Three habits, in order. **Prompt** with structure — use CLAIM so the first draft is focused and reviewable. **Verify** always — ground it in the record, make it cite its sources, and check the high-stakes facts yourself. And **protect** — share only what's needed, and use a tool that's built to guard the data. Do those three, and AI stops being a liability and starts being leverage.

**HOST A:** The AI drafts.

**HOST B:** The lawyer decides. That's the whole thing.

---

## CLOSE / OUTRO LINE
*Prompt well. Verify always. Protect the client. The tool accelerates the work — you still own it.*
