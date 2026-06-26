# EvenUp Onboarding Playbook — Training Module Script
## "Ask Better, Get Better: Prompting Legal AI for Personal-Injury Work"

**Format:** Self-paced module, built in Articulate Rise
**Audience:** Medical paralegals and case managers at a personal-injury firm (the MedChrons / Demands pilot cohort)
**Length:** ~20–25 minutes · four chapters
**Goal:** Move the user from search-box habits to structured prompting — so the first draft the tool returns is focused, source-grounded, reviewable, and safe to put in front of an attorney.

> *Independent work sample built from public materials. Not affiliated with or endorsed by EvenUp. Set at a fictional firm (Lakefront Injury Group); product names (MedChrons, Demands, etc.) are used descriptively. The CLAIM framing is adapted from Harvey's published prompting guidance and rewritten for personal-injury work.*

---

### How to use this script with Articulate Rise's AI assistant

Paste one chapter at a time into Rise's AI course/block builder. Each chapter gives you the **learning objective**, the **on-screen blocks** (with the Rise block type in [brackets]), the **copy** to drop in, and **answer-keyed knowledge checks**. Keep the theme consistent with the rest of the playbook: light background, deep slate-navy headings, a single periwinkle accent.

This module is deliberately practical. It does not teach prompt theory for its own sake — it teaches the handful of moves that turn a vague request into a usable PI work product, using the records, bills, and demand work the cohort touches every day.

---

## INTRO — Why prompting is a paralegal skill now

**[Cover / statement block]**
Headline: *The quality of the answer is set by the quality of the ask.*
Subhead: A vague prompt gets a generic answer. A structured prompt gets a reviewable draft. The difference is a skill — and it's one you already have from delegating to a new colleague.

**[Text block]**
You'd never hand a new case assistant a stack of records and say only "summarize this." You'd tell them the matter, what you need, who it's for, and what "done" looks like. AI works the same way. When the instruction is thin, the tool fills the gaps with guesses; when the instruction is specific, it produces something you can actually verify and use. This module gives you a repeatable way to write that instruction — and to do it without ever exposing client information you shouldn't.

**[Knowledge check — multiple choice]**
Q: Why do two people get very different results from the same AI tool?
- A) The tool is unreliable and random
- B) The quality and specificity of the prompt drives the quality of the output ✅
- C) One of them has a paid account
- D) AI only works for lawyers, not paralegals
Feedback (correct): The biggest lever you control is the prompt. Same tool, better instructions, better draft.

---

## CHAPTER 1 — The CLAIM framework

**[Statement block]** *Learning objective:* Use a five-part structure — CLAIM — to turn a vague request into a complete prompt.

**[Text block]**
CLAIM is a checklist for a good instruction. You don't need every element every time, but naming them keeps you from leaving out the one that matters.

**[Flashcard grid block]** — CLAIM
- **C — Context** → What matter is this? "A motor-vehicle PI matter; client treated for a neck and lower-back injury after a rear-end collision."
- **L — Legal task** → The verb. Summarize, extract, compare, draft, build a chronology, issue-spot, rewrite.
- **A — Audience** → Who reads the output? An adjuster, the attorney, the client, a demand reviewer — each needs a different tone and depth.
- **I — Instructions** → The constraints. Date range, which records to use, what to flag, what to ignore, what standard to apply.
- **M — Mode of output** → The shape. Table, chronology, bullet list, demand-letter section, checklist.

**[Text block]** — See it work
*Vague:* "Summarize these medical records."
*CLAIM:* "You are helping a personal-injury paralegal at a plaintiff firm (**Context**). From the attached ER and orthopedic records, build a treatment chronology for the demand package (**Legal task**) that the handling attorney will review (**Audience**). Include date, provider, visit type, and key findings; cite the source page for every entry; flag any treatment gap over 30 days and any mention of a prior injury (**Instructions**). Return it as a table sorted by date (**Mode of output**)."

**[Statement block]**
> Vague prompts produce generic answers. Structured prompts produce reviewable work product.

**[Knowledge check — matching / multiple response]**
Q: In the prompt "Draft the damages section of a demand letter for the adjuster, using only the attached bills and chronology; keep it to one page," which CLAIM elements are present? (Select all)
- Legal task (draft the damages section) ✅
- Audience (the adjuster) ✅
- Instructions (use only the attached bills and chronology) ✅
- Mode of output (one page) ✅
- Context (which matter/injury) — missing, add it ✅
Feedback: Four of five are there. The missing piece is Context — name the matter and injury so the draft is grounded, not generic.

---

## CHAPTER 2 — Ground it in the record, and be specific

**[Statement block]** *Learning objective:* Anchor prompts in source documents and name the specifics — parties, dates, standards — that keep the output accurate.

**[Text block]**
AI is most reliable when it's working *from* something, not from memory. A prompt that points to the actual records, bills, or police report will beat a prompt that asks the tool to recall general medical or legal knowledge. The same goes for specifics: the more precisely you scope the request, the narrower — and safer — the answer.

**[Accordion or numbered list block]** — make it specific
1. **Point to the sources.** "Using the attached records from Dr. Patel and Lakeshore Imaging…" beats "based on what you know about back injuries."
2. **Name the window.** Give the treatment date range; ask it to ignore anything outside it.
3. **Name the standard, where one applies.** Jurisdiction, the kind of demand, the adjuster's known objections — context that shapes the answer.
4. **Tell it what to leave out.** "Do not include billing codes" or "exclude unrelated dermatology visits" keeps the output clean.
5. **Ask for what you can check.** Request page citations so every claim can be traced to the record.

**[Text block]** — Example
*Better:* "Using only the attached records and bills for the 1/4/26–6/2/26 treatment window, list each provider, the number of visits, and total billed. Exclude the pre-accident primary-care visit. Cite the source page for each provider's total."

**[Knowledge check — scenario]**
Q: You want a clean provider-and-billing summary, but the file also contains unrelated records from before the accident. What's the best prompt move?
- A) Submit everything and hope the tool sorts it out
- B) Scope the prompt to the treatment window and explicitly exclude the pre-accident records ✅
- C) Delete the pre-accident records from the file first
- D) Ask for the summary, then fix it by hand afterward
Feedback (correct): Scoping the prompt — the date window plus an explicit exclusion — gets you a clean first pass and keeps the unrelated history out of the work product.

---

## CHAPTER 3 — Build in verification, and iterate

**[Statement block]** *Learning objective:* Write prompts that expose their own uncertainty, and refine the output in passes instead of expecting it perfect the first time.

**[Text block]**
The goal isn't an answer you trust blindly — it's an answer you can *check fast*. You can build that into the prompt itself, asking the tool to show its work and surface what it isn't sure about. Then treat the first output the way you'd treat a junior colleague's first draft: useful, and not final.

**[Flashcard grid block]** — verification you can request
- **Cite the source** → "Include a page citation for every entry." If the page doesn't say it, you'll catch it.
- **Separate fact from inference** → "Mark anything you inferred versus what the record states."
- **Flag uncertainty** → "Note where the records are illegible, conflicting, or incomplete."
- **Surface gaps** → "List any provider or date range that appears missing."
- **Call for review** → "Highlight anything that should go to the attorney before it ships."

**[Text block]** — iterate like you delegate
A strong first prompt gets you 80%. You close the gap with follow-ups: "Tighten the damages paragraph and lead with the surgery." "You missed the 3/12 urgent-care visit — add it and re-sort." Refining in steps beats trying to write one perfect mega-prompt.

**[Statement block]**
> The tool drafts; you decide. Verification isn't a step after the prompt — it's part of the prompt.

**[Knowledge check — multiple response]**
Q: Which instructions make an output easier to verify? (Select all)
- "Cite the source page for each entry." ✅
- "Mark inferences separately from stated facts." ✅
- "Just give me the final version, no notes." ❌
- "Flag illegible or conflicting records." ✅
- "Highlight items that need attorney review." ✅
Feedback: Build the checkpoints into the ask. An output that shows its sources and its doubts is one you can trust quickly.

---

## CHAPTER 4 — Prompt without compromising confidentiality

**[Statement block]** *Learning objective:* Protect client and health information in every prompt, and know why the tool you use matters as much as the words you type.

**[Text block]**
Medical-legal work runs on some of the most sensitive data there is — protected health information, client identifiers, case strategy. Good prompting and good data hygiene have to travel together. The rule of thumb: give the tool what the task needs, and no more — especially in any general-purpose, consumer-grade tool that isn't built for legal work.

**[Process block]** — the confidentiality checklist
1. **Mask identifiers.** Replace names with placeholders — "[Client]," "[Provider A]," "[Defendant]" — whenever the analysis doesn't truly need them.
2. **Minimum necessary.** Include only the records and facts the task requires; don't paste the whole file out of habit.
3. **Keep strategy out of open tools.** Privileged mental impressions and case theory don't belong in consumer chatbots.
4. **Know where the data goes.** Understand how the tool stores, retains, and uses what you enter — and whether it trains on it.
5. **You own the output.** Every draft gets human review before it's used in client work.

**[Text block]**
This is exactly why purpose-built legal platforms exist: data isolation, encryption, access controls, audit logs, and a commitment not to train on client data change what you can safely do. Strong prompts and strong governance reinforce each other — neither substitutes for the other.

**[Knowledge check — scenario]**
Q: A colleague pastes a full medical record, with the client's name and DOB, into a free public chatbot to "just get a quick summary." What's the problem?
- A) Nothing — it's faster
- B) It exposes PHI and client identity in a tool that isn't built for confidential legal work; mask identifiers and use an approved platform ✅
- C) The summary won't be detailed enough
- D) Free tools are always fine for medical records
Feedback (correct): Speed never outranks confidentiality. Mask what you can, share only what's needed, and use a tool that's built to protect the data.

---

## CLOSE — wrap, template, final check

**[Text block]**
You now have a repeatable way to ask: frame it with CLAIM, ground it in the record, build verification into the request, iterate like you'd delegate, and protect the client's information throughout. That's the difference between a tool that saves you time and one you can actually trust with the work.

**[Download / file block]** Attach the one-page **Prompting job aid** (below).

**[Statement block]** — A reusable template
> "You are helping a personal-injury [role] on a [matter type] for [Client/placeholder]. Using only [the attached records / bills / chronology], [task]. Focus on [issues]; exclude [out-of-scope items]. Return it as [table / chronology / demand section / checklist]. Cite the source page for each item, mark anything inferred, and flag what needs attorney review."

**[Final knowledge check — multiple choice]**
Q: What's the through-line of this module?
- A) Trust the AI's first answer to save time
- B) Write longer prompts no matter what
- C) Ask with structure, ground it in the record, build in verification, and protect the data ✅
- D) Only use AI for small cases
Feedback (correct): Structure, sources, verification, confidentiality — the four habits that make AI output reviewable and safe.

**[Closing statement block]**
Headline: *Ask better, get better.*
Subhead: A clear prompt is the fastest path to a draft you can stand behind.

---

### One-page job aid (attach in the Close)

**Prompting for PI work — CLAIM · ground · verify · protect**

1. **CLAIM the ask:** Context · Legal task · Audience · Instructions · Mode of output.
2. **Ground it:** point to the actual records/bills, name the date window and standard, say what to exclude.
3. **Verify by design:** ask for page citations, fact-vs-inference, flagged gaps, and items for attorney review.
4. **Iterate:** treat the first draft as a starting point; refine in follow-ups.
5. **Protect:** mask identifiers, share only what's needed, keep strategy out of open tools, review every output.

*Reusable opener:* "You are helping a PI [role] on a [matter type] for [Client]. Using only [sources], [task]. Focus on [issues]; exclude [out-of-scope]. Return as [format]. Cite sources, mark inferences, flag attorney-review items."
