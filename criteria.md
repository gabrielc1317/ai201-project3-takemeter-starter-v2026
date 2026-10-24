# Acceptance criteria — TakeMeter

Five criteria that say what "working" means for this classifier, written in
unit 5 **before** anything was trained.

**All five are yours this time.** None are given. You've had two projects of
practice.

An acceptance criterion names a number. *"The model is accurate"* is an
opinion. *"Every label has an F1 of at least 0.60 on the held-out set"* is a
criterion.

Under each, write a sentence or two on **why that number**. A reason that says
something about your data or your taxonomy earns credit — *"I picked 0.60 F1
for `reaction` because it's my smallest label and I only have about 50
examples of it"*. A reason that could be attached to any project does not.

> Missing your own targets next unit costs you nothing. Setting a target so
> easy you can't miss it does.

---

## Pick numbers you can defend

Not numbers that sound impressive. Three labels means a coin-flip guesser gets
about 33%, so a target of 0.40 is barely a target. Your number should sit
somewhere you'd honestly call useful.

**Cover at least three of these five areas.** They're here as prompts, not as a
form to fill in — a criterion that fits none of them is fine if it names a
number.

| Area | A question it could answer |
|---|---|
| Overall accuracy | How often does it need to be right to be worth using? |
| Per-label performance | Is one label allowed to be much worse than the others? |
| Balance | How lopsided can your label counts get before it's a problem? |
| Consistency | If someone else labelled the same posts, how often should you agree? |
| Confidence | Should a confident prediction be right more often than an unsure one? |

Two things worth knowing before you pick numbers, because both will affect
whether you hit them:

- **Your smallest label will have the jumpiest score.** If a label has 50
  examples, about 8 land in the test split. An F1 computed on 8 examples moves
  a lot between seeds. A target for that label should be looser than one for
  your biggest label, and saying so is a good reason.
- **Unit 6 tests across three seeds, and the target has to hold across all
  three.** A target of 0.65 against results of 0.71, 0.62, 0.68 is a **miss**.
  Pick with that in mind — it is stricter than it first sounds.

---

## 1.

<!-- Atleast 90% of posts are classified correctly. -->



**Why this target: I chose 90% because I feel that 9/10 posts being classified correctly would make the tool pretty reliable. That way when someone is looking for a certain type of post, more then most of time they'll get accompanied posts that fall under that label.**


---

## 2.

<!-- Every label has an F1 of atleast 0.85. -->



**Why this target: An F1 target of 0.85 for every label ensures that overall accuracy cannot hide poor performance of one category. The classifier should be reliable across all 4 labels rather then carrying a high overall accuracy across easier categories and hiding the poor performance of another.**



---

## 3.

<!-- No label exceeds 35% of the dataset. -->



**Why this target: With 4 labels, there should be a good amount of balance, however due to the nature of the posts, some are alot more common then other, to ensure a balance while also keeping the natural variation, no label should exceed 35% of the dataset.**



---

## 4.

<!-- Agreement with another labeler is atleast 90%. -->



**Why this target: Most labels are easy to differentiate, however with the unsupported_opinion and analysis label, there can be alot of ambiguity, because of this i think another labeler should agree with my classifier about 90% of the time. I feel this is an achievable and reliable number to aim for.**




---

## 5.

<!-- The most confidence third of the model's predictions should be correct atleast 95% of the time.-->



**Why this target: Given our aforementioned targets for accuracy and precision, I feel that the most confident portion (third) of the model's predicitions should be correct atleast 95% of the time. When the model is more sure that a post is a certain label (confidence) it should be correct more often then a lower confidence post.**



---

<!-- ─────────────────────────────────────────────────────────────────────────
     UNIT 6 — read this before you change anything above.

     If a criterion turns out to be BROKEN rather than merely unmet, you can
     revise it, and that earns credit. But never delete or edit the original
     line. Add the revision underneath, like this:

         ## 2. Every label performs acceptably

         The model performs well on all labels.

         **Why this target:** ...

         > **Revised in unit 6:** Every label has an F1 of at least 0.60 on
         > the held-out set.
         >
         > **Why revised:** "performs well" gave me nothing to check. I
         > couldn't produce a verdict from it at all.

     That's a revision because the criterion couldn't be MEASURED.

     Lowering a target because you missed it is not a revision, and it costs
     you the point:

         ✗ "Overall accuracy of at least 0.65" → "at least 0.55", because
            0.65 turned out to be optimistic for 200 examples.

     A number you missed stays where it is, gets diagnosed, and gets a fix
     attempted. That's where the points are.
     ───────────────────────────────────────────────────────────────────────── -->
