# TakeMeter

> ### 👋 Start here
>
> **New to this repo? Read [RUNNING.md](RUNNING.md) first** — setup, the
> notebook, the baseline, and what to do when something breaks.
>
> Once `python test.py` passes:
>
> ```bash
> head -5 data/practice_labels.csv     # the shape your labels.csv needs
> ```
>
> Then open `takemeter.ipynb` **in this folder** — in VS Code, or with
> `jupyter notebook` if you prefer. Pick the kernel: the `.venv` inside this
> project. Run section 1, which reports the hardware you'll be training on.
> Everything else waits until you have data.
>
> Nothing to upload, nothing to connect, no accounts and no keys. The notebook
> runs on your machine and writes next to your code.
>
> **The rest of this file is your submission.** Fill it in as you go.

---

<!-- ─────────────────────────────────────────────────────────────────────────
     HOW TO USE THIS FILE

     Unit 5 asks for the first five sections. Unit 6 adds the five below them.

     Everything is pasted as TEXT. No screenshots, no images.

     ⚠️ The confusion matrix especially. The notebook prints one as a markdown
     table, ready to copy. A screenshot of a matrix earns nothing. Paste the
     table.
     ───────────────────────────────────────────────────────────────────────── -->

<!-- ═══════════════════════ UNIT 5 — THE BUILD ═══════════════════════ -->

## What This Does

<!-- Your community, and what your classifier sorts posts into. Three or four
     sentences. -->



---

## Label Taxonomy

<!-- Each label: a one-sentence definition and two real examples from your
     reading. Then your decision rule for the hardest boundary.

     The decision rule is worth a point on its own and it's the thing most
     people leave out. Every taxonomy has a hardest boundary. Name yours. -->

### `analysis`

**Definition: A post whose primary purpose is to evaluate, complain about, advocate for, or make a hot take about the game without enough specific supporting evidence to qualify as analysis**

**Example 1:**
>The current state of lance genuinely makes me want to cry [RANT]
`Disclaimer: This is going to be a LONG rant, so bear with me. I’ve added subtitles to break up a bit, and there's a TL;DR at the end for those who can't be bothered to read the whole thing

———————————————————————————

First off all, for as much as I complain about lance, I genuinely love this weapon. I love its playstyle & the identity that sets it apart from the rest of the weapons in the game. So no, I don’t want to switch weapons. I shouldn’t have to abandon the weapon I enjoy just to play something that actually feels rewarding. I want to keep playing lance & feel like the time I put into it is actually worth something.

Anyway,…

1. March 2026: Patch 10.04 nerfed some of lance’s most important attacks
Let's start with a more recent balance patch, because I genuinely think this one deserves MORE attention

In March 2026, Patch 10.04 nerfed four of lance's main attacks in a single patch. Here’s what changed:
- Side Light: Time to hit increased from 10 to 12 frames
- Neutral Air: Damage decreased from 16 to 14, stun reduced from 29–24 to 26–21, and acceleration reduced
- Side Air: Force decreased from 65 fixed / 42 variable to 50 fixed / 40 variable
- Down Air: Threat coverage near the user reduced
That’s FOUR attacks getting nerfed in one patch, & the sair nerf was immense. Its fixed force went from 65 to 50, a 23% reduction. I don't know how anyone can look at that and call it insignificant. Sair is one of lance's main attacks, & losing that much force obviously affects its ability to kill

We've also seen lance get nerfed over and over again throughout the years. Since 2020, it's received about 23 nerfs compared to just 9 buffs. Obviously, some of those nerfs were justified, but that gap is still pretty insane

And look, I understand WHY lance gets nerfed. It can be annoying to fight against, especially when people struggle to deal with its range and movement. I'm not saying it should never get nerfed or that it's never been too strong. But these changes start making the weapon feel worse to play too. Looking at everything that's been changed, it's clear how much lance has lost in terms of damage, movement, coverage, recovery and killing power. And it just feels like they're taking away what makes the weapon rewarding to play in the first place

2. The problem is that lance already has fundamental weaknesses
People see lance range and immediately act like you’re playing some type of killing machine. Apparently, having range automatically means your weapon good

RANGE DOES NOT AUTOMATICALLY MAKE A WEAPON GOOD

Yes, lance has strong horizontal attacks & it destroys people who approach carelessly. But have you ever actually played lance against someone who KNOWS what they're doing?

Playing against people who know how to counter lance is infuriating. And that's fair to an extent. Every weapon should have counterplay. The issue is that lance's playstyle is so predictable that by low/mid plat it feels like most players already know what you're going to do before you even do it & end up having to work twice as hard just to catch up with the rest of the weapons

3. When was the last time you saw lance win in a tournament?
I already elaborated a little bit about this one one of my other posts. But the question speaks for itself…

4. Playing lance feels like working twice as hard for the same results
Losing isn’t even the problem, since I win most of my matches on an average day. It’s just frustrating playing lance be when you’re already trying your hardest to make it work. You have to space properly, predict your opponent's movement, be careful with your approaches & constantly make sure you're not being too predictable yourself. And obviously, that’s part of playing any weapon and I’m not expecting any free wins. But sometimes it genuinely feels like you have to play perfectly just to get the same results other weapons can get away with playing far more casually

I win games with Lance, and so can others. I’m not claiming the weapon is unusable, nor that every loss is the weapon’s fault. I just want to feel like my skill is being rewarded, rather than feeling like I'm constantly having to work around lance's limitations just to keep up

5. So where does that leave lance?
I don't think lance is unusable. Skilled players can still make it work. I just really do think lance needs a more consistent approach to balancing

Lance's design also creates an awkward balancing dilemma. At lower levels, its range & horizontal attacks are difficult to counter. Against experienced players, opponents can quickly identify its weaknesses. Buffing its obvious strengths make it more annoying to fight AGAINST, while nerfing those strengths risks make it more annoying to play

And I wish the discussion around lance went beyond the usual "lance is broken/trash" arguments. Both sides have their reasons. But I also think there's a reason so many lance players are frustrated with its current state & end up switching to another weapon

LANCE, I LOVE YOU. PLEASE GET YOUR SHIT TOGETHER.

TL;DR
Lance has received about 23 nerfs and 9 buffs since 2020 (not sure if it’s the exact number but it’s close), and Patch 10.04 in march 2026 slight, nair, sair and dair were all nerfed, with sairs fixed force dropping by 23%

My problem isn’t that lance is completely unplayable. It’s that its strengths can make it annoying to fight against, while its predictable playstyle & weaknesses make it annoying to use against experienced players

I miss when lance was played in competitive play. I don’t expect it to be overpowered, but I do want it to feel rewarding without having to work twice as hard for the same results

———————————————————————————

Would you guys mind upvoting? 🥹🫰
I’ve put some time into this, so it would be nice if it received some attention. Thank you for reading !!
`
**Example 2:**
>Legends in dire need of new skins.
`King Zuva, Ransom and Rupture have been sitting at 4 since their launch, so they should be the next legends to receive new skins after Vector and Kor in November. And even though Aurus and Qinghua & Baobao are the newest entries they too should get a new skin before any other legend. Teros and Val currently at 19 skins each. And I realize that they’re popular legends, I happen to main Teros, that being said share the love BMG.
`
### `request`

**Definition: A post whose primary purpose is to ask the community for information, explanation, advice, teammates, submissions, participation, or another response or aciton.**

**Example 1:**
>I am a new to the game , can somebody please explain to me what was this guy doing ???
`Attached to a gameplay video.
`
**Example 2:**
>Is there still a way to get Hattori's Akuma no Kogo skin?
`I'd really love to get the Akuma no Kogo skin for Hattori...

When was it first added to the game? Is there still a way to get it?

Is there any chance it'll return to the shop in the future?
`
### `showcase`

**Definition: A post whose primary purpose is to share an accomplishment, gameplay clip, technique, tool, demonstration, meme, funny moment, or other piece of content rather than ask for help or argue a claim.**

**Example 1:**
>Finally reached valhallan but in solo 2v2s
`Dang this solo q 2v2 is crazy easy to reach valhallan i used to grind so much in 1v1 but barely scratch top 100 dreaming to reach it one day (top 50), and last week i just discovered this mode exist and ALREADY reach valhallan in no time even reaching top 10 in my server. Am I actually better than 99.9% SEA players or nobody actually plays this gamemode😭
`
**Example 2:**
>Ranked 1’s Diamond Gameplay
`I’m the sentinel. Hammer feels so good this patch! (yes i dropped 35 dabloons just for the hammer)

Attached to a gameplay video.
`
### `unsupported opinion`

**Definition: A post whose primary purpose is to make an evaluative claim, complaint, hot take, or reccomendation without using specific evidence to suppor the conclusion.**

**Example 1:**
>Oh so NOW you guys think blasters is broken?
`I’ve been saying this for YEARS, since 2020, IDC how bad you think it was, to me it was mental shattering to play them, back then and of course now.

The spam, god the spam, it’s so hard to get around blasters, and you mf’s are only NOW feeling the pain? Fuck outta here.
`
**Example 2:**
>Keep El Gato con Botas away from me
`Every game I play against that tournament-regular clan I get the life beaten out of me and can't do a thing about it. FFA queue? 1 member shows up and I'm fighting for my life. 1v1 queue? I end up fighting them and end up with carpal tunnel trying to keep up and recover because they never stop moving, their characters' attacks have almost no startup lag to speak of, and I can't even get a hit let alone a combo in edgewise. Just goes to show exactly why even free fighting games lose most of their community after year 1, because everybody learns to win and not to have fun. They're great players, and I don't intend to accuse them of anything but being way too good at fighting games for my filthy casual unc self to do anything against.
`
### The hardest boundary

**Which two labels: analysis and unsupported_opinion**

**The decision rule I used every time: If a post uses at least one specific, checkable or reproducible detail as evidence for its conclusion, such as a mechanic, interaction, patch change, statistic, numerical comparison, or concrete gameplay example, I label it analysis. If the post mainly states an evaluation, complaint, hot take, or recommendation without using specific evidence to support that conclusion, I label it unsupported_opinion. The tone of the post does not determine the label. A post can be angry or explicitly call itself a rant and still be analysis if it supports its argument with concrete evidence.**
<!-- e.g. "If the post names a specific checkable fact, it's `analysis`, even
     if the tone is heated." -->



---

## The Dataset

<!-- Where you collected from, how you labelled, your counts, and three hard
     cases. -->

**Where the posts came from:**

**How I labelled them:** <!-- Cold first? Pre-labelled with AI and corrected?
Say so plainly — the disclosure is required, not penalised. -->

**Counts per label:**

| Label | Count | Share |
|---|---|---|
|  |  |  |
|  |  |  |
|  |  |  |
| **Total** |  | 100% |

**Three hard cases**

<!-- Any post that made you pause: what it was, which two labels it could have
     been, and what you chose. These are worth more than the easy 190. -->

**1.**
> *The post:*
>
> *Could have been:*
>
> *I chose, because:*

**2.**
> *The post:*
>
> *Could have been:*
>
> *I chose, because:*

**3.**
> *The post:*
>
> *Could have been:*
>
> *I chose, because:*

---

## The Training Run

<!-- Your starting model, your settings, and anything you changed and why. -->

**Base model:**

**Settings:** <!-- epochs, learning rate, batch size, seed -->

**Anything I changed from the defaults, and why:**

**Split sizes:** <!-- train / val / test, and per-label counts in the test
split. If a label had fewer than about 8 in test, say so — it explains a lot
of next unit's variance. -->



---

## How I Used AI

<!-- Two specific moments — what you asked, what came back, what you changed.

     ⚠️ Plus disclosure of any pre-labelling. If you had a model pre-label a
     batch and then read and corrected every one, say that. It's an allowed
     workflow and disclosing it costs you nothing. Not disclosing it is the
     problem. -->

**Moment 1**

- *What I asked for:*
- *What came back:*
- *What I changed:*

**Moment 2**

- *What I asked for:*
- *What came back:*
- *What I changed:*

**Pre-labelling disclosure:**

<!-- ═══════════════════════ UNIT 6 — THE TEST ═══════════════════════

     Don't fill these in during unit 5.
     ═══════════════════════════════════════════════════════════════════ -->

---

## Baseline vs. Trained

<!-- Both models on the same posts. `python baseline.py --trained results.json`
     prints this table for you. -->

| Measure | Baseline | Trained | Difference |
|---|---|---|---|
| Overall accuracy |  |  |  |
| Macro F1 |  |  |  |
| F1 — `label_one` |  |  |  |
| F1 — `label_two` |  |  |  |

**What I predicted before I looked:**
<!-- Milestone 1 asks you to write this BEFORE seeing the trained numbers. A
     prediction made afterwards isn't one. -->

**What the gap actually means:**
<!-- If the baseline matched your trained model, your fine-tuning added
     nothing — and that is a real finding, not a failure. Say it plainly. -->



---

## Run Log — Before

<!-- Five criteria across three seeds. The notebook's section 6 prints the
     spread table; the Target and Verdict columns are yours. -->

| Criterion | Target | Seed 42 | Seed 7 | Seed 2024 | Verdict |
|---|---|---|---|---|---|
| 1.  |  |  |  |  |  |
| 2.  |  |  |  |  |  |
| 3.  |  |  |  |  |  |
| 4.  |  |  |  |  |  |
| 5.  |  |  |  |  |  |

### Confusion matrix

<!-- ⚠️ TYPED AS A MARKDOWN TABLE. The notebook prints one ready to paste.
     An image of a matrix earns nothing. -->

| true \ predicted |  |  |  |
|---|---|---|---|
| **** |  |  |  |
| **** |  |  |  |
| **** |  |  |  |

**My biggest off-diagonal number, and what it means:**
<!-- Not "the model made mistakes" — WHICH boundary it didn't learn, and which
     direction. "7 real analysis posts were called hot_take and only 3 went the
     other way" is a direction, not just an error rate. -->



---

## Verdicts and Diagnoses

<!-- MET or MISSED against LAST UNIT's target. The target has to hold across
     all three seeds, not turn up sometimes. -->

| # | Criterion | Target | Verdict | How I decided |
|---|---|---|---|---|
| 1 |  |  |  |  |
| 2 |  |  |  |  |
| 3 |  |  |  |  |
| 4 |  |  |  |  |
| 5 |  |  |  |  |

**Diagnoses**

<!-- For each miss: the cause, and how you know. The four common causes are:
     too few examples for a label, a boundary you applied inconsistently, a
     genuinely hard label pair, and a task the model can't reach from this
     much data.

     ⚠️ Use your agreement report as evidence. It is the only instrument you
     have that can tell a LABELLING problem from a MODEL problem, and this
     section is graded on whether you used it that way. -->



---

## Agreement Report

<!-- Your rate against the staff set, and every disagreement adjudicated.

     Remember you labelled these 30 under the STAFF taxonomy in
     data/staff_taxonomy.md, not your own — so every argument below is made
     from those definitions and those decision rules. -->

**Agreement rate:** ___ / 30 = ___%

<!-- Nobody grades this number. A 60% who argues every disagreement from the
     stated rules beats a 95% who wrote "staff was right" nine times. Several
     of the 30 were chosen because they're genuinely ambiguous — you should be
     winning some of these. -->

**Disagreements**

<!-- Three lines each: the post, both labels, and who you think is right and
     why — grounded in the staff definitions you were both applying.

     Then sort each into one of three piles:
       (a) the rule covered it and I applied it loosely → a consistency problem
       (b) the rule genuinely doesn't say               → a gap in the definitions
       (c) the rule is ambiguous here and my reading is defensible → argue it.
           This is a legitimate win.

     Pile (a) is the one that matters most for your diagnosis: if you applied a
     written rule two different ways on 30 posts, that is direct evidence about
     what you did across your own 200. -->

**1.**
> *The post:*
>
> *Staff said / I said:*
>
> *My call, and why:*
>
> *Which pile:*

**2.**
> *The post:*
>
> *Staff said / I said:*
>
> *My call, and why:*
>
> *Which pile:*

**What the pattern in my disagreements tells me:**



---

## The Improvement

**What I changed:**

**Which diagnosis pointed at it:**

### Run Log — After

| Criterion | Target | Seed 42 | Seed 7 | Seed 2024 | Verdict |
|---|---|---|---|---|---|
| 1.  |  |  |  |  |  |
| 2.  |  |  |  |  |  |
| 3.  |  |  |  |  |  |
| 4.  |  |  |  |  |  |
| 5.  |  |  |  |  |  |

**Did it help, and how do I know:**

<!-- If it didn't, say so. Relabelling that didn't help is a genuinely
     interesting result and earns full credit. -->



---

## What's Still Broken

<!-- For each criterion still missed: what you'd do, and why you stopped. -->



**The gap between what I meant my labels to capture and what the model
learned:**
<!-- Two sentences. Your confusion matrix is the evidence. -->



<!-- ═════════════════════════════════════════════════════════════════════

     SUBMISSION CHECKLIST — unit 5

       [ ] criteria.md has five numbered criteria, each naming a NUMBER
       [ ] Each has a reason underneath tied to your data or taxonomy
       [ ] labels.csv: at least 150 rows, text/label/note, ONE file not split
       [ ] No label above 70%
       [ ] All five unit 5 sections have real content
       [ ] Label Taxonomy includes the decision rule for your hardest boundary
       [ ] The Dataset includes three hard cases
       [ ] results.json and test_split.csv committed (the notebook does this)
       [ ] At least four new commits
       [ ] Repository URL submitted — WRITE IT DOWN

     SUBMISSION CHECKLIST — unit 6

       [ ] Baseline vs. Trained table, with your prediction written beforehand
       [ ] Run Log — Before, five criteria across three seeds
       [ ] Confusion matrix TYPED AS A MARKDOWN TABLE
       [ ] A verdict on every criterion
       [ ] A diagnosis for every miss, using the agreement report as evidence
       [ ] Agreement Report with every disagreement adjudicated
       [ ] One improvement, with Run Log — After
       [ ] What's Still Broken
       [ ] results_three_seeds_before.json, results_three_seeds_after.json,
           baseline_results.json and
           agreement_results.json committed
       [ ] At least four new commits
       [ ] The SAME repository URL as last unit

     Do not delete and recreate this repository.
     ═════════════════════════════════════════════════════════════════════ -->

---

📖 **How to run this project: [RUNNING.md](RUNNING.md)**
