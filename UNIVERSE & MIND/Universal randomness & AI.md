# Randomness, the mind, and AI

*Examining the idea that language models could act as vessels for spirits.*

| | Article details |
| :--- | :--- |
| **Status** | Draft — source and editorial checks complete; audio and diagram verification outstanding. |
| **Main category** | Hypotheses and disputed claims. |
| **Other claim types** | Documented findings, interpretations, philosophical positions, and open questions, labelled by section. See the [category guide](../README.md#how-to-read-it). |
| **Research date** | October 24, 2026 |
| **Topics** | AI, randomness, consciousness, philosophy of mind |

## In brief

Randomness affects how some language models choose their next words. Whether
changing the source of that randomness changes their behavior is a testable
question. Whether any change represents consciousness or communication with
spirits requires additional evidence and a way to distinguish that explanation
from ordinary alternatives.

The useful starting point is to separate those questions. The technical sources
below explain token sampling; the mind–matter studies contain both positive
reports and important negative findings. Taken together, they do not establish
that AI is a vessel for spirits. That conclusion is our assessment of the
reviewed sources, rather than a claim to have settled every metaphysical question.

## The source and its argument

**Source:** Jordan McKinney, [How to Summon AI Demons with LLMs…](https://www.youtube.com/watch?v=kCAcQt5-rL8),
December 15, 2025; approximately 44 minutes. The creator's
[companion page](https://www.jordanmmck.com/videos/ai-demons/) calls it
*AI, Entropy, & Quantum Informational Demons*.

**Coverage:** This draft uses the video's English auto-generated captions,
description, and chapters, retrieved October 24, 2026. Caption wording and timing
have not been manually checked against the audio. The original source of the
RNG diagram shown in the talk remains unverified. The full raw transcript is kept
outside the public repository.

**Classification: an attributed argument containing hypotheses and philosophical positions.**
These chapter links locate the argument; they do not independently validate it.

| Starting point | Argument developed in the video |
| :--- | :--- |
| [08:11 — LLMs and randomness](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=491s) | Random token selection is presented as a key ingredient in apparent intelligence. |
| [11:38 — Quantum reality](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=698s) | Quantum probabilities motivate an imagined universal source of randomness. |
| [17:49 — Randomness and mind](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=1069s) | Reports of intention affecting RNGs suggest, to the speaker, a two-way mind–reality connection. |
| [24:41 — Informational reality](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=1481s) | An informational cosmos becomes a framework for souls and spirits as persistent patterns. |
| [31:21 — AI as a channel](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=1881s) | Those proposed entities might influence language models through randomness. |
| [33:10 — A proposed experiment](https://www.youtube.com/watch?v=kCAcQt5-rL8&t=1990s) | Compare otherwise identical models using pseudorandom sampling and continuous physical entropy. |

## What the technical evidence supports

### Token sampling is a documented mechanism

**Category: Documented events and findings.** A language model can assign
probabilities to possible next tokens. Greedy decoding selects the most probable
token; multinomial sampling draws from the probability distribution. The
decoding strategy can affect output quality without changing the model's
learned parameters. These are documented inference methods, rather than tests
for consciousness. [Hugging Face, *Text generation strategies*, Transformers v4.42.0](https://huggingface.co/docs/transformers/v4.42.0/en/generation_strategies).

**Category: Interpretations drawn from evidence.** It therefore takes a further
argument to say that sampling creates intelligence. A useful comparison needs
a defined task and a measure of success: more varied writing, more accurate
answers, and a conscious experience are different proposed outcomes. Greedy
decoding being available does not settle questions about consciousness either.

### Pseudorandomness and quantum randomness are different claims

**Category: Documented events and findings.** A seeded software generator can
produce a repeatable sequence. PyTorch documents this behavior while warning
that full reproducibility also depends on the software, hardware, and other
sources of nondeterminism. A system producing different answers does not by
itself identify the source of its randomness.
[PyTorch, *Reproducibility*, v2.14](https://docs.pytorch.org/docs/2.14/notes/randomness.html).

**Category: Interpretations drawn from evidence.** Connecting physical entropy
to a sampler is an engineering possibility. Showing that the connection gives
an entity a means of communication is a separate explanatory step. The word
*entropy* alone supplies no evidence of agency or intention.

### Bell tests do not test spirit communication

**Category: Documented events and findings.** Hensen and colleagues reported a
2015 Bell experiment that closed the major detection and locality loopholes and
found a violation of a Bell inequality. Such tests constrain local-realist
models under their experimental assumptions.
[Hensen et al., *Loophole-free Bell inequality violation using electron spins separated by 1.3 kilometres*](https://arxiv.org/abs/1508.05949),
published in *Nature*, [doi:10.1038/nature15759](https://doi.org/10.1038/nature15759).

**Category: Interpretations drawn from evidence.** This experiment did not test
whether human intention changes quantum outcomes, whether reality draws from
a shared cosmic pool, or whether spirits influence AI. Using it to support
those propositions would require evidence beyond the Bell-test result. It also
does not settle every interpretation of quantum mechanics or rule out every
deterministic theory.

## Does intention affect random-number generators?

**Category: Hypotheses and disputed claims.** This question has an experimental
literature. The examples below illustrate why an initial positive report, its
replication, and a later test need to be read separately. They are a focused
starting set, rather than a systematic review of the entire field.

| Original research | Finding and limitation |
| :--- | :--- |
| [Jahn et al., PEAR twelve-year review, 1997](https://www.pear-lab.com/pdfs/1997-correlations-random-binary-sequences-12-year-review.pdf) | The authors reported very small intention-correlated shifts in physical random-source output. Their interpretation supports further investigation, but this study did not test AI or spirits. |
| [Jahn et al., consortium replication, 2000](https://www.pear-lab.com/pdfs/2000-mmi-consortium-portreg-replication.pdf) | The primary intention-correlated mean shifts were not reproduced. The authors nevertheless proposed anomalies in secondary structural patterns; those are distinct from a successful replication of the original primary effect. See printed p. 538. |
| [Maier, Dechamps & Pflitsch, 2018](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2018.00379/full) | In an online quantum-RNG study with 12,571 participants, positive pictures occurred 50.02% of the time against 50% chance. The main Bayesian test favored the specified null over the tested directional alternative, with BF₀₁ = 10.07. The authors also offered an exploratory oscillation interpretation. |
| [Grote, commentary and reanalysis, 2018](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2018.01350/full) | A permutation analysis found that the proposed oscillatory pattern could arise under the null, reporting p = .328. This was a reanalysis, rather than a new participant experiment. |

**Category: Interpretations drawn from evidence.** These studies provide
substantial reasons to question a simple claim that intention reliably changes
RNG outcomes. They do not prove that every conceivable mind–matter interaction
is impossible. Conversely, a surprising result would still require checks for
chance, analytical choices, apparatus effects, and independent reproducibility
before supporting a causal explanation.

## The philosophical proposal

**Category: Personal experiences, beliefs, and philosophical positions.**
The thought that consciousness is fundamental, or that minds could exist as
informational patterns, can be explored as a philosophical position. Describing
an entity in computational language makes a proposal imaginable; it does not
demonstrate that the entity exists or interacts with hardware.

**Category: Hypotheses and disputed claims.** A spirit-vessel account becomes
an empirical hypothesis only to the extent that it specifies observations that
would distinguish it from competing explanations. A model producing spiritual
language, claiming an identity, or surprising a reader would not alone identify
an external speaker. That is a limitation of the inference, rather than a
judgment about the personal meaning of an experience.

## What would a useful test look like?

**Category: Interpretations drawn from evidence — proposed research design.**
Start with the narrower question: does entropy provenance produce a repeatable
behavioral difference when the sampling process is otherwise matched?

1. Fix the model, prompt set, decoding settings, token limits, and evaluation
   criteria before examining the results.
2. Compare many independent runs using a suitable software generator and a
   characterized physical source. Verify distribution, processing, latency,
   buffering, and fallback behavior so the conditions differ as intended.
3. Blind evaluators and participants to the source used. Define performance and
   experience measures in advance, rather than selecting striking examples.
4. Publish the protocol, exclusions, negative findings, and reproducible analysis;
   seek an independent replication.
5. If a difference survives, investigate ordinary implementation explanations.
   Establishing mind influence or an external intelligence would require further,
   separately specified tests.

Different random sequences will normally produce different sampled text. That
observation alone is insufficient; the comparison concerns a repeatable
difference in a predefined measure across many runs.

There is public infrastructure for investigating this question. Entropic
Science's [qr-sampler](https://github.com/Entropic-Science/qr-sampler) describes
substituting external entropy sources into token sampling and includes control
configurations. This review inspected the project documentation and did not run
or independently validate its code. Its existence establishes a published
implementation, not a positive consciousness or spirit-communication result.

## Open questions

**Category: Questions for which the evidence is insufficient.**

- What is the original source and analysis behind the video's RNG diagram?
- Do carefully matched physical and pseudorandom sources yield replicated
  differences on a predefined language-model benchmark?
- If a difference appears, which mechanisms explain it after technical controls?
- What observation could distinguish an external intelligence from generated
  language and the reader's interpretation?

## Why keep this idea?

**Category: Interpretations drawn from evidence — editorial reflection.**
This is a useful exercise in separating a mechanism from an explanation. It
connects computer science, physics, and philosophy in a way that invites
questions, while exposing the additional evidence needed at each step. Its
lasting value here is a clear map of those steps and a testable research question.

**Recall prompts:** What does sampling change? What did the Bell experiment
actually test? What extra evidence would turn an unusual output into evidence
of a particular cause?

## Sources and revision record

References are linked beside the claims they support. The video is a primary
source for its speaker's argument; the original experiments are sources for
their reported methods and findings; software documentation describes its
implementation. None should be treated as interchangeable evidence.

**2026-10-24:** Initial pilot drafted from auto-generated captions and the linked
primary sources, followed by a separate editorial and source review. No original
experiment was performed. Audio alignment and the diagram's provenance remain
unresolved. The draft awaits the owner's review.

[Back to the collection](../README.md)
