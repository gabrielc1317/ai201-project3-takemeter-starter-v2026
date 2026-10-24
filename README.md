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
TakeMeter is a classifier for posts from r/Brawlhalla. It sorts posts into three categories: discussion, request, and showcase. The goal is to identify the primary purpose of a post rather than classify it based only on whether it contains a question, opinion, or media.


---

## Label Taxonomy

<!-- Each label: a one-sentence definition and two real examples from your
     reading. Then your decision rule for the hardest boundary.

     The decision rule is worth a point on its own and it's the thing most
     people leave out. Every taxonomy has a hardest boundary. Name yours. -->

### `discussion`

**Definition: A post whose primary purpose is to evaluate, complain about, advocate for, or make a hot take about the game regardless of evidence used.**

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
**Example 2**
>Bodvar fanart by me


### The hardest boundary

**Which two labels: discussion and request**

**The decision rule I used every time: If the poster already has a position and the question mainly invites agreement or debate, I label it discussion. If the poster has a genuine unresolved question or need that a response can answer, it'll be labeled request.**
<!-- e.g. "If the post names a specific checkable fact, it's `analysis`, even
     if the tone is heated." -->



---

## The Dataset

<!-- Where you collected from, how you labelled, your counts, and three hard
     cases. -->

**Where the posts came from: r/Brawlhalla (reddit.com/r/brawlhalla)**

**How I labelled them:** I got about 21 posts cold labeled, then after getting samples for each label from the cold labeled ones, i use AI to prelabel the rest of the posts and I reviewed each to ensure correct label.<!-- Cold first? Pre-labelled with AI and corrected?
Say so plainly — the disclosure is required, not penalised. -->

**Counts per label:**

| Label | Count | Share |
|---|---|---|
|Discussion|92|36.8%|
|request|79|31.6%|
|showcase|79|31.6%|
| **Total** |250| 100% |

**Three hard cases**

<!-- Any post that made you pause: what it was, which two labels it could have
     been, and what you chose. These are worth more than the easy 190. -->

**1.**
> *The post:“Why/What got you into Brawlhalla? And why are you still playing it? No like seriously, we all enjoy the game but like all competitive spaces we hate it too. Let me start: Why/what got me into Brawlhalla? Reno. Why do I still play? Honestly I barely do...”*
>
> *Could have been: Request*
>
> *I chose, because: Discussion, because even though the poster is asking questions, its mainly opening a conversation while giving their opinion. There isn't an actual problem or request they're making but more of a conversational strategy to start an open ended discussion.*

**2.**
> *The post: "Replay Analysis, Platinum (1800+)"*
>
> *Could have been: showcase*
>
> *I chose, because: Request, because at first glance it looks like someone showcasing their plat gameplay, but contextually a when someone post a video with the caption replay analysis, they're asking the community to review the gameplay with falls under the request label.*

**3.**
> *The post:“Win Triple A Games if you win a Brawlhalla match! Challenge LIVE on my channel. Going LIVE on my YouTube channel to host a Brawlhalla challenge with 1v1 matches. Winners get Triple A Steam games! Make sure to enter your name on the site.”*
>
> *Could have been: request*
>
> *I chose, because: Showcase, because the post asks people to enter their challenge, but the primary purpose of this post is to showcase and promote the creators event/content, rather then needing the community to solve or answer something.*

---

## The Training Run

<!-- Your starting model, your settings, and anything you changed and why. -->

**Base model: distilbert-base-uncased**


**Settings:Epochs: 3, Learning rate: 2e-5, Batch size: 16, Maximum sequence length: 128, Seed: 42, device: NVIDIA GeForce GTX 1660 SUPER using CUDA, PyTorch: 2.14.1+cu130** <!-- epochs, learning rate, batch size, seed -->

**Anything I changed from the defaults, and why: I kept the provided training hyperparameters unchanged so I could establish a clean first result without tuning the model based on the test set.**

**Split sizes: Train: 174, Val: 38, Test: 38. discussion: 14, request: 12, showcase: 12** <!-- train / val / test, and per-label counts in the test
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

- *What I asked for:I used AI to help stress-test my original taxonomy and find cases where the label boundaries were unclear.*
- *What came back:The biggest problem was the boundary between my original analysis and unsupported_opinion labels because the difference depended too much on how much evidence a post contained.*
- *What I changed:Before training, I merged those two labels into discussion and rewrote the boundary around the primary purpose of the post instead.*

**Moment 2**

- *What I asked for: After I cold labeled my first 21 posts, I used AI to pre-label the remaining posts using examples and definitions from my taxonomy.*
- *What came back: The pre-labels gave me a faster starting point, but there were several ambiguous posts where I disagreed with the suggested label.*
- *What I changed: I personally reviewed every pre labeled post and corrected labels when I thought the post's primary purpose fit another category. Some of those corrections became the hard cases documented above.*

**Pre-labelling disclosure: I cold labeled 21 posts without AI assistance. AI pre-labeled the remaining 229 posts, but I personally reviewed every one and corrected the labels I disagreed with before training the model.**

<!-- ═══════════════════════ UNIT 6 — THE TEST ═══════════════════════

     Don't fill these in during unit 5.
     ═══════════════════════════════════════════════════════════════════ -->

---

## Baseline vs. Trained

<!-- Both models on the same posts. `python baseline.py --trained results.json`
     prints this table for you. -->

| Measure | Baseline | Trained | Difference |
|---|---|---|---|
| Overall accuracy | 0.553 | 0.658 | +0.105 |
| Macro F1 | 0.513 | 0.608 | +0.096 |
| F1 — `discussion` | 0.667 | 0.718 | +0.051 |
| F1 — `request` | 0.585 | 0.250 | -0.335 |
| F1 — `showcase` | 0.286 | 0.857 | +0.571 |


**What I predicted before I looked:**
<!-- Milestone 1 asks you to write this BEFORE seeing the trained numbers. A
     prediction made afterwards isn't one. -->
     I predicted that the trained model would do better then the baseline model especially in the showcase where alot of the posts share a pattern in titling for showcasing clips and the like.

**What the gap actually means:**
<!-- If the baseline matched your trained model, your fine-tuning added
     nothing — and that is a real finding, not a failure. Say it plainly. -->
     The trained model did better, especially in the showcase label, slightly better in the discussion label. However the request label's F1 dropped significantly from 0.585 to 0.250. The trained model failed to identify the request posts roughly more then twice as much as the baseline.


---

## Run Log — Before

<!-- Five criteria across three seeds. The notebook's section 6 prints the
     spread table; the Target and Verdict columns are yours. -->


| Criterion | Target | Seed 42 | Seed 7 | Seed 2024 | Verdict |
|---|---:|---:|---:|---:|---|
| 1. Overall accuracy | ≥ 0.900 | 0.658 | 0.658 | 0.553 | MISSED |
| 2. Every label F1 | ≥ 0.850 | 0.250 | 0.154 | 0.154 | MISSED |
| 3. Largest label share | ≤ 35% | 36.8% | 36.8% | 36.8% | MISSED |
| 4. Agreement with another labeler | ≥ 90% | 96.7% | 96.7% | 96.7% | MET |
| 5. Most-confident third accuracy | ≥ 0.950 | 0.750 | 0.917 | 0.833 | MISSED |


### Confusion matrix

<!-- ⚠️ TYPED AS A MARKDOWN TABLE. The notebook prints one ready to paste.
     An image of a matrix earns nothing. -->

| true \ predicted | request | discussion | showcase |
|---|---:|---:|---:|
| **request** | 2 | 10 | 0 |
| **discussion** | 0 | 14 | 0 |
| **showcase** | 2 | 1 | 9 |

**My biggest off-diagonal number, and what it means: The biggest confusion was 10 real request posts being predicted as discussion, while 0 real discussion posts were predicted as request. This shows that the confusion is strongly onesided. The model learned the discussion class much more clearly than the request class and tends to absorb requests into discussion. I cannot tell yet whether this came from inconsistent labeling or from the model failing to learn the boundary.**
<!-- Not "the model made mistakes" — WHICH boundary it didn't learn, and which
     direction. "7 real analysis posts were called hot_take and only 3 went the
     other way" is a direction, not just an error rate. -->



---

## Verdicts and Diagnoses

<!-- MET or MISSED against LAST UNIT's target. The target has to hold across
     all three seeds, not turn up sometimes. -->


| # | Criterion | Target | Verdict | How I decided |
|---|---|---|---|---|
| 1 | Overall accuracy | ≥ 0.900 | MISSED | Accuracy was 0.658, 0.658, and 0.553. None of the three runs reached the target, and the 0.105 spread also shows that performance changes substantially depending on the split. |
| 2 | Every label F1 | ≥ 0.850 | MISSED | request was the weakest label in every run, with F1 scores of 0.250, 0.154, and 0.154. The confusion matrix for Seed 42 showed 10 of 12 real request posts being classified as discussion. |
| 3 | No label exceeds 35% of the dataset | ≤ 35% | MISSED | discussion contains 92 of 250 posts, or 36.8%, which is 1.8 percentage points above the target. |
| 4 | Agreement with another labeler | ≥ 90% | MET | I agreed with the staff labels on 29 of 30 posts, giving an agreement rate of about 96.7%. |
| 5 | Most-confident third accuracy | ≥ 0.950 | MISSED | The most-confident third was correct 75.0%, 91.7%, and 83.3% of the time across the three seeds. None reached 95%. |



**Diagnoses**

<!-- For each miss: the cause, and how you know. The four common causes are:
     too few examples for a label, a boundary you applied inconsistently, a
     genuinely hard label pair, and a task the model can't reach from this
     much data.

     ⚠️ Use your agreement report as evidence. It is the only instrument you
     have that can tell a LABELLING problem from a MODEL problem, and this
     section is graded on whether you used it that way. -->
     *Criterion 1 — Overall accuracy:**  
The biggest cause of the accuracy miss appears to be the model's failure to learn the request versus discussion boundary. In Seed 42, 10 of 12 real request posts were predicted as discussion, while none of the 14 real discussion posts were predicted as request. Accuracy also changed by 0.105 between seeds, which suggests the dataset is small enough for the particular train/test split to have a meaningful effect on performance.

**Criterion 2 — Every label F1:**  
request is the clearest failure. Its F1 stayed extremely low across all three seeds, so the Seed 42 result was not just an unlucky split. showcase also moved substantially, from 0.857 and 0.870 in the first two seeds to 0.615 in Seed 2024. My 97% staff-set agreement gives little evidence of a broad problem with my ability to consistently apply written labeling rules, although that agreement test used a different taxonomy and therefore cannot prove that every request/discussion label in my own dataset is correct. The evidence points more toward a difficult boundary combined with a relatively small training set.

**Criterion 3 — Dataset balance:**  
This criterion was missed narrowly: discussion makes up 36.8% of the dataset instead of at most 35%. The original reason for this target still refers to four labels, even though I merged the taxonomy to three labels before training. I am leaving the original target unchanged because it is still measurable; I simply missed it.


**Criterion 5 — Confidence:**  
The model's confidence was not reliable enough to meet the target. The most-confident predictions performed better than the least-confident predictions in Seeds 7 and 2024, but Seed 42 had identical 0.750 accuracy for both groups. Even the best seed only reached 0.917 for the most-confident third, so a high confidence score is not yet strong enough to treat a prediction as reliably correct.



---

## Agreement Report

<!-- Your rate against the staff set, and every disagreement adjudicated.

     Remember you labelled these 30 under the STAFF taxonomy in
     data/staff_taxonomy.md, not your own — so every argument below is made
     from those definitions and those decision rules. -->

**Agreement rate:** _29 / 30 = 97_%

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
> *The post:“Three of us ran the same session on the same day, different shoes, within 10 seconds of each other over 5 miles. I'm not saying shoes do nothing, but whatever they do was smaller than the noise between three people.”*
>
> *Staff said / I said: analysis / hot_take*
>
> *My call, and why: I think the staff is correct. The post gives a comparison between 3 people, same session, different shoes, and finishing within 10 seconds of eachtoher. Since it is using fact based off observation and testing, its not a hot_take but rather a analysis.*
>
> *Which pile: (a) the rule covered it and I applied it loosely*


**What the pattern in my disagreements tells me:**

I agreed with the staff on 29 of 30 posts, or 97%. The only disagreement came from applying the analysis rule too narrowly rather than from a missing or ambiguous definition. That suggests I can apply a written taxonomy consistently, but that the difference in complete factual bearing posts and speculative can be strengthened.
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
