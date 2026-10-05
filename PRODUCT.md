# Tapestry · RFP-to-Proposal Platform

> Turn Tapestry's scattered knowledge into a **trusted library** of approved content, and use it to produce **first-draft proposals faster**, with every claim traced back to its source.

**Status:** Phase 0, defining the product. Nothing on this page is final yet.
**Last updated:** 6 October 2026 · *"RFP-to-Proposal Platform" is a working name.*

---

## At a glance

| | |
|---|---|
| **Who it helps** | Proposal teams answering large government and defense RFPs |
| **What it does** | Reads an RFP, finds approved answers in company knowledge, drafts sections and hands them to people to review |
| **What it never does** | Make up facts, use unapproved content, or submit anything by itself |

---

## The problem today

Tapestry responds to long, technical RFPs that often run to hundreds of pages, usually with only a few weeks to respond. The knowledge needed for the answers already exists inside the company, but it is hard to find and hard to trust.

| # | What goes wrong | What it costs |
|---|---|---|
| 1 | **Knowledge is scattered.** Content sits across team sites, wikis, old proposals and inboxes. Nobody is sure which version is the latest or which one was approved. | Hours of searching on every proposal |
| 2 | **Work gets repeated.** Good answers written before can't be found, so people write them again from scratch. | Expert time spent twice |
| 3 | **Answers don't match.** Different proposals say different things about the same topic. | Credibility and compliance risk |
| 4 | **A few experts are overloaded.** The same questions go to the same people every time. | Proposals wait on a handful of calendars |
| 5 | **Deadlines are unforgiving.** A late submission can lose a large contract outright. | Lost revenue |
| 6 | **There is no approval trail.** Reused content is assumed to be "probably right" instead of being checked and recorded. | Audit and compliance exposure |

---

## What we're building

The platform has two connected parts.

### 1. A trusted knowledge library
This part gathers approved content from the places it lives today. Each piece of content records:

- where it came from
- who owns it
- which version it is
- whether it is approved
- who is allowed to see it

Owners can update or withdraw their content. Content that is out of date stops being used.

### 2. A proposal assistant
This part takes the proposal team through a new RFP step by step:

1. Work out what the RFP is asking for.
2. Find the best approved evidence for each answer.
3. Draft the sections.
4. Point out anything that's missing.
5. Prepare an editable document for review.

> **The library comes first, and the proposal assistant is the first thing built on it.** Other teams could use the same library later.

---

## Who it's for

| Person | What they get |
|---|---|
| **Proposal manager** | A clear list of everything the RFP asks for, a response outline and first drafts to work from |
| **Subject-matter experts (SMEs)** | Fewer repeat questions. They fill specific gaps and check drafts instead of rewriting old answers. |
| **Reviewers** (technical, legal, security, commercial) | A source shown for every claim, so checking is quicker and more reliable |
| **Content owners** | A simple way to approve, update or retire the content they look after |
| **Leadership** | A view of time saved, effort reduced and requirements covered |

---

## How it works

**Upload → Understand → Plan → Find evidence → Draft → Review → Export**

| Step | What happens | Who's in control |
|---|---|---|
| **1. Upload** | The team adds the RFP and its attachments. Any file that can't be read is flagged with the reason. | Proposal manager |
| **2. Understand** | The platform lists every requirement, question, deadline and instruction, each with its page reference. | The team corrects anything that was misread |
| **3. Plan** | It suggests a response outline and a checklist that matches each requirement to a section. Unclear or conflicting items are highlighted. | Proposal manager approves the plan |
| **4. Find evidence** | For each section, it searches the library for approved, current content that the user is allowed to see. | Automatic, within access rules |
| **5. Draft** | It writes draft sections from that evidence and links each claim to its source. Missing facts become questions for named people. | Experts answer the open questions |
| **6. Review** | People edit sections, ask for rewrites of specific ones, and approve them. Every version is kept. | Reviewers decide |
| **7. Export** | It produces an editable document in the agreed template, with headings, tables and the requirements checklist intact. | The team finalises and submits it |

---

## Promises we keep

- **Every claim shows its source.** Readers can open the exact approved document and version behind it.
- **Only approved, current content is used.** Unapproved drafts, old versions and restricted material are left out.
- **Nothing is made up.** If the evidence isn't there, the gap is flagged and sent to a person. Prices, staffing, commitments and certifications always come from people.
- **People approve everything.** The platform suggests and the team decides.
- **Nothing goes out automatically.** Nothing is submitted, published or sent outside the company unless a person does it.
- **Access rules are respected.** People only see content they are already allowed to see.

---

## What it is not

- **Not a chatbot.** It is a guided proposal workflow, not a general-purpose assistant.
- **Not an auto-submitter.** Tapestry owns every proposal and submits it.
- **Not a replacement for experts.** It takes the searching and rewriting off their hands so they can focus on judgment.
- **Not a copy of everything.** Content is used only after its owner approves it.

---

## What success looks like

We will agree exact targets with Tapestry before building. These are the kinds of results we expect to measure.

| Outcome | How we'll know |
|---|---|
| **A faster start** | Less time from receiving an RFP to having a first draft ready for review, compared with today |
| **Nothing missed** | Every mandatory requirement is either answered or clearly flagged |
| **Drafts people can trust** | Reviewers find no unsupported claims in the sections they sample |
| **Less load on experts** | Fewer hours of expert time per proposal |
| **Consistent answers** | The same question gets the same approved answer in every proposal |
| **Easy to use** | Proposal managers can complete the whole flow without technical help |

---

## Where we are now

| Phase | What it means | |
|---|---|---|
| **0 · Define** | Agree on what we build and why | **We are here** |
| 1 · Proof of concept | Use one real RFP and a couple of knowledge sources to test the whole flow from start to finish | Next |
| 2 · Pilot | Use it on a live proposal with the real team | Later |
| 3 · First release | Roll it out more widely | Later |

**Phase 0 work:**
- Review and refine the goals, requirements and scope
- Map how people and the platform work together
- Agree how content is approved and protected
- Make the key choices about our approach, tracked on the decision board

**Questions still open** (details in [docs/PRODUCT-ANALYSIS.md](docs/PRODUCT-ANALYSIS.md)):
- How big should the first proof of concept be?
- Which knowledge sources come first, and who owns them?
- What security rules apply to Tapestry's content?
- What should the first output be: a requirements checklist, section drafts or a full proposal?

---

## Glossary

| Term | Meaning |
|---|---|
| **RFP** | Request for Proposal: the document a customer issues to describe what they want and how to respond |
| **Proposal** | Tapestry's written response to an RFP |
| **SME** | Subject-matter expert: the person who knows the real answer on a topic |
| **Requirements checklist** | A list of everything the RFP asks for and where the proposal answers each item. Also called a *compliance matrix*. |
| **Trusted knowledge library** | Tapestry's approved, owned and up-to-date reusable content, all in one place. Also called the *Knowledge Fabric*. |
| **Evidence** | The approved source content that a statement in a draft is based on |
| **Gap** | A required fact the library doesn't have. It becomes a question for a person. |
