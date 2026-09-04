# Why this method works

This quiz is built around a few well-studied learning ideas: **retrieve an answer**, get **clear feedback right away**, then **practice weak areas sooner** and **space out** what you already handle well. The interactive **Quiz logic** panel in `index.html` shows the same flow in diagram form.

## Immediate feedback, then Next

As soon as you choose an option, the quiz locks your answer, marks correct/incorrect, and shows a short reason. You decide when to click **Next**.

Why that helps:

- After an error, **feedback is essential** so the wrong choice does not linger uncorrected. Research on fact learning finds that unsuccessful attempts are not inherently harmful when feedback follows; the attempt can even prepare you to encode the right answer (Kornell, Hays, & Bjork, 2009; Pashler et al., 2003).
- Explanatory feedback (not just a grade) supports better understanding than bare right/wrong labels—aligned with broader feedback research emphasizing information value (Wisniewski, Zierer, & Hattie, 2020).

You still control pacing with **Next**, so you can read the reason before the next retrieval.

## Short return after incorrect answers

If you miss a structure (for example, Causal), the quiz gives that structure **priority** and **no long cooldown**. Similar questions tend to return sooner.

Why short, not long, after a miss:

- **Expanding retrieval** schedules start with relatively short intervals when memory is fragile, then stretch gaps after success (Landauer & Bjork, 1978). A long cooldown right after a failure would bury the item while the correction is freshest to reinforce.
- Spaced practice still matters overall, but optimal spacing depends on how well an item is already learned. Meta-analytic work on distributed practice shows that inter-study interval and retention goals interact; weaker learning generally needs closer follow-up than mastered material (Cepeda, Pashler, Vul, Wixted, & Rohrer, 2006).
- Effortful retrieval that **succeeds** strengthens memory more; if retrieval keeps failing, you need corrective feedback and another chance soon—not a long vacation from the concept (see desirable-difficulty discussions in Bjork’s work and related spacing reviews).

In plain terms: **do not punish a miss with a long wait.** Correct it, then practice it again before the session ends.

## Longer cooldown after correct streaks

If you keep answering a structure correctly, the quiz **cools it down** for several upcoming questions and spends time elsewhere.

Why longer spacing after success:

- The **spacing / lag effect**: distributing practice over time improves later retention compared with massing easy successes back-to-back (Cepeda et al., 2006; Cepeda et al., 2008 summary page linked below).
- **Desirable difficulties**: making practice slightly harder (including spacing and interleaving different structures) often improves long-term learning even when it feels less fluent in the moment (Bjork, desirable difficulties overview).
- Adaptive tutors and expanding schedules both treat “I got this” as a signal to **increase the gap**, not to drill the same pattern again immediately.

## Tracking misses and a live score

The live **Score: correct / answered** line and **Needs practice** list make your gaps visible while you work. That supports self-regulated study: you know what to reopen in the glossary and what the adaptive picker is prioritizing.

## What this quiz is not claiming

- It is a single-session adaptive order over a fixed question bank, not a multi-day spaced-repetition system with calendar intervals.
- Equal spacing can also be effective; expanding schedules are a practical heuristic, not the only valid design (see critical reviews of expanded retrieval).
- Research findings are based mainly on verbal/fact learning tasks; speech-structure classification is a close applied cousin (concept discrimination with feedback), not an identical lab paradigm.

## Citations (working links)

1. Cepeda, N. J., Pashler, H., Vul, E., Wixted, J. T., & Rohrer, D. (2006). Distributed practice in verbal recall tasks: A review and quantitative synthesis. *Psychological Bulletin*, 132(3), 354–380.  
   - Author page (PDF): https://www.yorku.ca/ncepeda/publications/CPVWR2006.html  
   - PubMed: https://pubmed.ncbi.nlm.nih.gov/16719566/

2. Landauer, T. K., & Bjork, R. A. (1978). Optimum rehearsal patterns and name learning. In M. M. Gruneberg, P. E. Morris, & R. N. Sykes (Eds.), *Practical aspects of memory*.  
   - UCLA Bjork Lab PDF: https://bjorklab.psych.ucla.edu/wp-content/uploads/sites/13/2016/07/Landauer_RBjork_1978.pdf

3. Bjork, R. A. Desirable difficulties perspective on learning (overview chapter PDF).  
   - https://bjorklab.psych.ucla.edu/wp-content/uploads/sites/13/2016/07/RBjork_inpress.pdf

4. Kornell, N., Hays, M. J., & Bjork, R. A. (2009). Unsuccessful retrieval attempts enhance subsequent learning. *Journal of Experimental Psychology: Learning, Memory, and Cognition*.  
   - PDF: https://web.williams.edu/Psychology/Faculty/Kornell/Publications/Kornell.Hays.Bjork.2009.pdf

5. Pashler, H., Zarow, G., & Triplett, B. (2003). Is temporal spacing of tests helpful even when it inflates error rates? *Journal of Experimental Psychology: Learning, Memory, and Cognition*.  
   - PDF mirror: https://gwern.net/doc/psychology/spaced-repetition/2003-pashler.pdf

6. Spacing and desirable difficulty (open access discussion):  
   - https://pmc.ncbi.nlm.nih.gov/articles/PMC6289840/

7. Retrieval practice, spacing, and desirable difficulty (open access):  
   - https://pmc.ncbi.nlm.nih.gov/articles/PMC4480221/

8. Wisniewski, B., Zierer, K., & Hattie, J. (2020). The power of feedback revisited: A meta-analysis of educational feedback research. *Frontiers in Psychology*.  
   - https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2019.03087/full

9. Cepeda lab page collecting related spacing papers (including the 2008 “temporal ridgeline” work):  
   - https://www.yorku.ca/ncepeda/publications/CPVWR2006.html

---

Last updated: 2026-09-04
