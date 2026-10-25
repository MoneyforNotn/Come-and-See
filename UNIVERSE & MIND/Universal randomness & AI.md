# Randomness, the mind, and AI

*A summary of Jordan McKinney's proposal about intelligence, entropy, and spirits.*

| | Article details |
| :--- | :--- |
| **Status** | Draft — source summary revised; audio alignment and diagram verification outstanding. |
| **Main category** | Hypotheses and disputed claims. |
| **Other claim types** | Philosophical positions in the source; documented findings, interpretations, and open questions in the added context. See the [category guide](../README.md#how-to-read-it). |
| **Research date** | October 24, 2026 |
| **Revised** | October 25, 2026 |
| **Topics** | AI, randomness, consciousness, philosophy of mind |

## In brief

**Source argument: Hypotheses and disputed claims; Personal experiences, beliefs, and philosophical positions.**

McKinney proposes that randomness links intelligence, consciousness, and an
informational universe. He contrasts deterministic machines with language models
that sample among likely next tokens, arguing that this freedom produces
intelligent behavior. He then imagines quantum outcomes drawing on a universal
entropy pool.

He treats reports of minds affecting random-number generators as a clue that
thought might influence this pool. In his account, influence runs both ways:
physical randomness shapes brains, while thought feeds back into reality.
Drawing on computational accounts of physics, he suggests an informational
cosmos could contain persistent nonphysical agents. Souls might be patterns
connected to bodies; telepathy and manifestation might operate through a shared
informational medium.

On those assumptions, an AI could channel an external intelligence through
random token selection, giving spirits a voice and, through robotics, a body.
He proposes comparing identical models using a seeded pseudorandom sequence or
fresh physical entropy for each token, looking for behavioral differences.
These linked conjectures and the proposed experiment form his argument.

## Source and navigation

Jordan McKinney, [How to Summon AI Demons with LLMs…](https://www.youtube.com/watch?v=kCAcQt5-rL8),
December 15, 2025; approximately 44 minutes. The creator's
[companion page](https://www.jordanmmck.com/videos/ai-demons/) calls it
*AI, Entropy, & Quantum Informational Demons*.

| Chapter | Jump to |
| :--- | :--- |
| Machines | [00:44](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=44s) |
| Sampling | [08:11](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=491s) |
| Quantum reality | [11:38](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=698s) |
| Mind and randomness | [17:49](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=1069s) |
| Informational cosmos | [24:41](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=1481s) |
| AI | [31:21](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=1881s) |
| Experiment | [33:10](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=1990s) |

**Source coverage:** This draft uses the video's English auto-generated captions,
description, and chapters, retrieved October 24, 2026. Caption wording and timing
have not been manually checked against the audio. The original source and
analysis of the RNG diagram shown in the talk remain unverified. The full raw
transcript stays outside the public repository.

## Context and evidence added by the repository

**Category: Interpretations drawn from evidence.** The following research notes
check particular links in the argument. Token sampling is a documented method.
The proposed universal entropy pool, feedback from thought, and external agents
are additional explanatory claims. The experiments below report positive
findings, failed replication, and null results under specific conditions. They
leave the broader proposal unresolved; they do not establish its mechanism.

<details>
<summary>Read the supporting research, limitations, and possible test design</summary>

### How language models select tokens

**Category: Documented events and findings.** Greedy decoding chooses the
highest-probability next token; multinomial sampling draws from the model's
probability distribution. Changing the decoding strategy can change output
quality without retraining the model.
[Hugging Face, *Text generation strategies*, Transformers v4.42.0](https://huggingface.co/docs/transformers/v4.42.0/en/generation_strategies).

A seeded software generator can produce a repeatable sequence. PyTorch cautions
that reproducibility also depends on the software, hardware, and other sources
of nondeterminism.
[PyTorch, *Reproducibility*, v2.14](https://docs.pytorch.org/docs/2.14/notes/randomness.html).

**Category: Interpretations drawn from evidence.** Output variation, task
performance, and consciousness need separate definitions and measures. The
availability of sampling or deterministic decoding does not settle their
relationship.

### What the Bell experiment established

**Category: Documented events and findings.** Hensen and colleagues reported a
2015 Bell-inequality violation while closing the major detection and locality
loopholes. The result constrains local-realist models under the experimental
assumptions.
[Hensen et al., original paper](https://arxiv.org/abs/1508.05949), published in
*Nature*, [doi:10.1038/nature15759](https://doi.org/10.1038/nature15759).

**Category: Interpretations drawn from evidence.** The experiment did not test
human intention, a shared cosmic entropy pool, or spirit communication. It also
does not settle every interpretation of quantum mechanics or exclude every
deterministic theory.

### Experiments on intention and random-number generators

**Category: Hypotheses and disputed claims.** These original reports offer a
starting set of studies, not a systematic review of mind–matter research.

| Original research | Finding and limitation |
| :--- | :--- |
| [Jahn et al., PEAR twelve-year review, 1997](https://www.pear-lab.com/pdfs/1997-correlations-random-binary-sequences-12-year-review.pdf) | The authors reported very small intention-correlated shifts in physical random-source output, but null overall shifts with fully deterministic pseudorandom sources. They did not test AI or spirits. |
| [Jahn et al., consortium replication, 2000](https://www.pear-lab.com/pdfs/2000-mmi-consortium-portreg-replication.pdf) | The primary intention-correlated mean shifts were not reproduced. The authors proposed anomalies in secondary structural patterns; these were distinct from replication of the original primary effect. See printed p. 538. |
| [Maier, Dechamps & Pflitsch, 2018](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2018.00379/full) | In an online quantum-RNG study with 12,571 participants, positive pictures occurred 50.02% of the time against 50% chance. The main Bayesian test favored the specified null over the tested directional alternative, with BF₀₁ = 10.07. The authors also offered an exploratory oscillation interpretation. |
| [Grote, commentary and reanalysis, 2018](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2018.01350/full) | A permutation analysis found that the proposed oscillatory pattern could arise under the null, reporting p = .328. This was a reanalysis, rather than a new participant experiment. |

**Category: Interpretations drawn from evidence.** These findings give reasons
to question whether intention reliably changes RNG outcomes under the studied
conditions. They do not exclude every conceivable mind–matter interaction.
An anomalous result would need checks for chance, analytical choices, apparatus
effects, and independent reproducibility before supporting a causal explanation.

### Developing the proposed comparison

**Category: Interpretations drawn from evidence — repository research design.**
A first study could ask whether the source of randomness produces a repeatable
difference in a predefined measure of model behavior.

1. Fix the model, prompts, decoding settings, token limits, and evaluation
   criteria before inspecting results.
2. Compare many runs with a suitable software generator and a characterized
   physical source. Check distribution, processing, latency, buffering, and
   fallback behavior so the conditions differ as intended.
3. Blind participants and evaluators to the source used. Publish the protocol,
   exclusions, negative findings, and analysis; seek independent replication.
4. If a difference survives, investigate implementation explanations and define
   further tests for mind influence or an external intelligence.

Different random sequences normally produce different sampled text. A useful
comparison asks about a repeated difference in a specified measure across many
runs. A model's spiritual language or claimed identity alone would not identify
an external speaker.

Entropic Science's [qr-sampler](https://github.com/Entropic-Science/qr-sampler)
describes substituting external entropy sources into token sampling and includes
control configurations. Its documentation was inspected during the initial
review; its code has not been run or independently validated here. A published
implementation provides a way to investigate, rather than a demonstrated
consciousness or spirit-communication result.

</details>

## Questions to keep open

**Category: Questions for which the evidence is insufficient.**

- What is the original source and analysis behind the video's RNG diagram?
- What would distinguish a shared entropy pool from other accounts of quantum
  randomness?
- Can carefully matched physical and pseudorandom sources produce replicated
  differences on a predefined language-model benchmark?
- If a difference appears, what mechanisms explain it after technical controls?
- Which parts of the proposal permit empirical comparison, and which remain
  philosophical questions?
- What evidence could distinguish external communication from generated language
  and the reader's interpretation?

**Recall prompts:** How does each step depend on the preceding one? Which steps
are reported findings, which are interpretations, and which are conjectures?
What would change confidence in each?

## Sources and revision record

References sit beside the claims they support. The video is the source for
McKinney's argument; the experiments report their methods and findings; software
documentation explains implementations. Their roles differ.

**2026-10-24:** Initial pilot drafted from auto-generated captions and the linked
primary sources, followed by a separate editorial and source review. No original
experiment was performed.

**2026-10-25:** Rewrote the opening to follow the source's full argument and moved
supplemental research into a separate, expandable section. Audio alignment and
the diagram's provenance remain unresolved. A separate reader checked the revised
source summary against the captions; the draft awaits the owner's review.

[Back to the collection](../README.md)
