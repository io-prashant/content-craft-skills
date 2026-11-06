---
name: learning-design
description: "Evidence-based learning design for anyone building study content, courses, or learning products: what the research actually supports (retrieval practice, spacing, worked examples, motivation), what is mixed (gamification), what is myth (learning styles, the 8-second attention span), and the ethics line on persuasive design. Every claim carries an evidence-strength tag and a cited source. Use when designing lessons, study systems, practice loops, or engagement mechanics."
---

# Learning Design, Evidence-First

Every technique in this skill carries an evidence tag: STRONG (meta-analyses and major reviews), MODERATE (promising but mixed or less stable), MYTH (no credible evidence), or FIELD DATA (real measurements, narrower than the headline). The full citation list lives in references/sources.md. Cite at the tagged strength; never upgrade a finding because it is convenient.

## What works (STRONG)

- **Practice testing / retrieval practice.** Testing beats rereading. Dunlosky et al. (2013) rate practice testing high utility; a systematic review of applied school research (about 2,000 abstracts screened, 50 experiments coded) finds retrieval practice consistently benefits learning. Design implication: every lesson should make the learner retrieve, not just review - quizzes, blank-page recall, teach-back.
- **Distributed practice / spacing.** Same study time spread over days beats massed cramming; high utility in Dunlosky et al. Combined with retrieval ("successive relearning", Rawson, Dunlosky & Sciartelli 2013), it improves real course-exam performance. A 2025 Educational Psychology Review meta-analysis on mathematics found a robust small-to-medium spacing effect (g = 0.28) but inconclusive evidence for a testing effect there - so for math, claim spacing confidently and retrieval more cautiously. Design implication: schedule revisits; do not let a topic be one-and-done.
- **Worked examples for novices.** Reviewed studies (Educational Psychology Review special issue, 2010; Sweller 2006) show novices learn more from studying worked examples than from solving equivalent problems unaided; prompting self-explanation adds a small positive effect. Design implication: show the worked path first, then fade support.
- **Rereading and highlighting are low-utility** as student study techniques (Dunlosky et al.). Note the scope: this is a verdict on them as the student's main technique, not on instructional explanations.
- **Motivation: competence first.** Self-determination theory meta-analyses (144 studies, N>79,000; a 2024 meta-analysis of SDT-based education interventions, N=9,433) find perceived competence is the strongest predictor of self-determined motivation, then autonomy, then relatedness; teacher autonomy support is the strongest provider behavior. Design implication: engineer early wins and real choices before social features.

## What is mixed (MODERATE)

- **Gamification.** Sailer & Homner (2019): medium cognitive effect (g=.49), smaller motivational (g=.36) and behavioral (g=.25) effects, less stable in higher-rigor studies. A 2023 meta-analysis (41 studies) shows a large average effect with high heterogeneity; Design implication: points and streaks can support a loop that already teaches; they do not replace one.
- **Desirable difficulties** (Bjork & Bjork 2011): making learning effortful in the right way (spacing, interleaving, testing) improves long-term retention. Key caveat: difficulties must be surmountable at the learner's current level, otherwise they are just difficulties.

## Myths to stop repeating (MYTH)

- **Learning styles.** Pashler, McDaniel, Rohrer & Bjork (2008): no credible evidence that matching instruction to supposed visual/auditory/kinesthetic styles improves learning.
- **The "8-second attention span".** The figure traces to a 2015 marketing report citing a defunct statistics site; journalists found no peer-reviewed source, and attention researchers say no published studies quantify attention span that way. Good for killing the myth - not proof attention is unchanged.

## What field data actually says (FIELD DATA)

- Gloria Mark's in-situ measurements: her tracking samples show average time on one screen before switching at about 47 seconds. That is screen-switching behavior in specific observed samples, not a universal attention limit.
- Media multitasking: heavy media multitaskers are more susceptible to interference on cognitive-control lab tasks (Ophir, Nass & Wagner 2009, PNAS).
- Product reference: Duolingo's published engineering and research posts describe a student model with forgetting curves and half-life regression scheduling, and a simpler-to-harder teaching method with optional hints and AI difficulty adaptation (references/sources.md).

## The ethics line

A CHI 2026 systematic review of dark-pattern experiments finds they can alter user behavior, with large variance in effect size, and that external mitigations mostly fail. So: use engagement mechanics to make the learner's OWN goals easier, never to manufacture time-on-app. Streaks that punish a sick day, guilt notifications, fake urgency, and loss-framed pressure are dark patterns even when they lift a metric. If a mechanic would embarrass you when explained to the learner, cut it.

## How to apply this to a design decision

1. State the learning outcome in one sentence.
2. Pick the mechanism the evidence supports for it (retrieval, spacing, worked example, competence-building).
3. Add engagement mechanics only on top of a working learning loop.
4. Tag every claim you make about the design with its evidence strength and source.
5. If your only support for a technique is a blog post or a vendor page, label it exactly that.
