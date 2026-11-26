# Start here

## If you are a fresh session continuing Wajdan's content work

Read these two, in order:

1. `research/WORKFLOW.md` — how the system runs, which tool does what, what it costs
2. `research/craft.md` — how short form actually works. **Eight principles, learned the hard way.
   Read before writing anything.**

Then, depending on the task:

| Task | Read |
|---|---|
| Write a reel | `craft.md`, `ideal-profile.md`, `viral-playbook.md` |
| Model a creator | `creators.md` |
| Wajahat pasted a link | `swipe-file.md` for the protocol |
| Wajahat said "learn this" | `craft.md` for the protocol |
| Paid ads | `meta-swipe.md` |

**Credentials already work.** Apify is saved on the `wajdann` cloud environment, so any session
there reaches it with no setup. Meta Ad Library runs through the connector. vidIQ has 150 free
credits a month, refilling on the 24th.

**Things that will save you from repeating mistakes:**
- Subject beats mechanism. Explaining how the system works is the lowest performing thing a
  reel can do.
- Short does not mean fragmented. Complete sentences, under about twelve words.
- Never define a word inside a reel. If it needs defining, it is the wrong word.
- $240,000 was over **three months**, not per month.
- Naming Hainan Corporate Services publicly needs their approval.

---

## If you are building a SECOND system for another brand or client

Most of this repo is Wajdan specific. Some of it is not.

**Reusable anywhere. Copy these across:**

| File | Why it travels |
|---|---|
| `research/brand.md` | Who Wajdan is, the funnels, the proof, how Wajahat wants things written |
| `research/craft.md` | How short form works. Platform truth, not Wajdan truth |
| `research/WORKFLOW.md` | The process and the tooling. Swap the niche, keep the method |
| `research/formats.md` | Format mechanics, length findings, hook patterns |

**Niche specific. Do not copy:**

`creators.md` is this niche. `swipe-file.md` is Wajahat's taste. `scripts/`, `deliverables/`
and `meta-swipe.md` are all specific to this business.

**To spin one up:**

1. New private repo, for example `ContentSystemStudyPrime`
2. Copy the four reusable files above
3. Run **Path D** from `WORKFLOW.md`: a full discovery pass for the new niche, about 40 vidIQ
   credits, which produces a fresh `creators.md`
4. Start a `swipe-file.md` and a `craft.md` for that brand. Craft principles learned there flow
   back here, since they are platform truths rather than brand ones.

**The expensive part is discovery and it only happens once per niche.** Everything after that is
monitoring at a few cents a month.

---

## Starting `CreatorSystemWajdan`, step by step

A second system that is still Wajdan, for example a creator or personal account rather than the
brand account. The brand truth carries over. The niche research may or may not.

**Step 1. Make the repo.**
On GitHub, under the **wajdan-admin** organisation, create a new **private** repo called
`CreatorSystemWajdan`. Tick "Add a README" so it is not empty. It has to live under wajdan-admin,
because that is where the Claude GitHub App has write access. A repo under a personal account will
fail every push.

**Step 2. Open a new session on the right environment.**
Start a new Claude Code session on the **`wajdann`** environment. That environment already holds
the Apify credential and has open network access, so nothing needs setting up again.
Attach **both** repos: `ContentSystemWajdan` as the source and `CreatorSystemWajdan` as the
destination.

**Step 3. Paste this as the first message.**

> Copy these four files from ContentSystemWajdan into CreatorSystemWajdan:
> research/brand.md, research/craft.md, research/WORKFLOW.md, research/formats.md.
> Then read brand.md and craft.md and tell me what you now know about Wajdan.

That one message gives the new system the brand, the craft principles and the method, with none of
the old niche research weighing it down.

**Step 4. Decide the fork. This is the only real decision.**

| Situation | What to do |
|---|---|
| Same audience as the brand account, consultancies and agency owners | Also copy `research/creators.md`. The research is still valid. Skip step 5 |
| A different audience, for example a personal brand aimed at founders generally | Do not copy it. Run step 5 |

**Step 5. Only if the audience changed: run discovery.**
Say: *"Run Path D from WORKFLOW.md for [describe the audience] and build creators.md."*
Costs about 40 vidIQ credits out of the 150 free each month, refilling on the 24th. This is the
expensive part and it happens once.

**Step 6. Open the two inboxes.**
Create an empty `research/swipe-file.md` and an empty `research/craft.md` section for the new
account. From then on, pasting a reel link means "make me one like this" and saying "learn this"
means "add it to craft". Both protocols are already written in the files you copied.

**Step 7. First reel.**
Ask for one script modelled on the highest multiple creator in the list. Do not batch five. Shoot
one, look at what it does, then decide.

**What flows back.** Anything learned about how short form works belongs in `craft.md` in **both**
repos. That file is platform truth, not brand truth, and two diverging copies is the one way this
gets worse over time.
