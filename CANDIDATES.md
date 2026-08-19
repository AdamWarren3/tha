# Candidate Register

Every claim or research direction currently under consideration, restated in the
vocabulary of the fields that would evaluate it. **This is a triage queue, not an
archive.** Entries leave it by graduating to a paper or preregistration, or by being
dropped with the reason recorded.

**Nothing has been curated out.** Directions judged already-occupied are listed in
Section G with what occupies them, so the exclusion is visible rather than assumed.

**Status vocabulary.** *Unchecked* — no literature search run. *Checked, open* — searched,
nothing directly occupying it found, one or two queries only. *Checked, occupied* —
existing work covers it. *Extension* — existing framework, not yet applied to this case.

---

## A. Suggestibility and altered states in human–LLM interaction

**A1. Trait absorption predicts reduced error detection in extended LLM interaction.**
Absorption predicts hypnotic responsiveness and narrative transportation; transportation
involves reduced counterarguing; error detection in a conversational partner's output is
a form of counterarguing. *Field: individual differences, cognitive psychology; human
factors.* **Status: occupancy checked, open — but both premises checked 2026-08-15 and both
came back qualified. The entry survives; the claim is now incremental, not novel.**

*Premise 1 — the absorption→hypnotisability link is contested and has been for forty years.*
Council, Kirsch & Hafner, *J Pers Soc Psychol* 50 (1986): 182–189 argued the TAS–
hypnotisability correlation is an artifact of testing context. Nadon, Hoyt, Register &
Kihlstrom, *J Pers Soc Psychol* 60 (1991): 144–153 failed to replicate across two studies
(N=475, N=434), finding the context effect weak and variable and reversed in the second, and
reaffirmed absorption's construct validity. Oakman, Woody & Bowers, *Contemp Hypnosis* (1996),
N=88, replicated the context effect. Milling, Kirsch & Burgess, *Contemp Hypnosis* 17 (2000):
32–41, N=150 same context vs N=146 separate contexts, found associations significantly
stronger in the same context and reported **r = .24 same-context against r = .05 separate-
context**, not attributable to sampling or to the interval between sessions. Barnier (1999)
adds that non-hypnotic contexts are not interchangeable.
**Design consequence: the TAS must be administered in a context unconnected to the study, and
the power analysis must target the separate-context estimate, not the same-context one. A
same-session administration is not defensible in front of this literature.**

*Premise 2 — the outcome measure is owned by human factors.* Failure to detect errors an
automated aid did not flag is an **omission error**, with a 25-year literature. Parasuraman &
Manzey, *Human Factors* 52(3) (2010): 381–410 is the integrative review: complacency arises
under multiple-task load, appears in naive **and expert** participants, **cannot be overcome
by simple practice**, and automation bias **cannot be prevented by training or instructions**.
Skitka et al., *Int J Human-Computer Studies* (1999) found accountability lowers it and that
omission errors specifically reflect cognitive vigilance decrements. Bahner, Hüper & Manzey
(2008) tie both error types to reduced verification behaviour. Lyell et al. measured omission
errors directly in e-prescribing and found task complexity and interruptions did not move
automation bias.
**Design consequence: the covariate set as written — domain familiarity, reasoning, time on
task — omits the variables this field considers primary. Trust in automation, complacency
potential and verification behaviour must be measured, or a human-factors reviewer rejects
the design on sight.**

*What the claim now is: whether trait absorption adds incremental predictive value over the
established automation-bias moderators. That is defensible and testable. "Nobody has looked
at who misses errors in machine output" is not, and must not be written.*
*To move: preregistration needs both design changes above, plus power analysis, scale
licensing, ethics. **A2 does not depend on the absorption construct and is not owned by
automation bias — on this evidence it is the stronger lead study.***

**A2. Source-monitoring failure in extended LLM dialogue.** Cryptomnesia is more likely
when cognitive load impairs source monitoring. Extended conversation with a model
combines sustained load, absorbed attention, and output objectively conditioned on the
user's own input, so authorship is genuinely mixed. Prediction: elevated rates of
misattributing model-originated ideas to oneself. *Field: memory, source monitoring.*
**Status: checked, open — one query.** Existing AI work addresses the model's source
amnesia, not the user's. *To move: one further search, then preregistration. Paradigms and
baseline rates already exist.*

**A3. Format-dependence of the protection people carry into suggestion channels.** The
belief that one cannot be influenced without agreeing is roughly correct about formal
induction, which supplies announcement, agreement, boundaries and an operator. Suggestion
outside that format requires no cooperation. The confidence transfers where the format
does not. *Field: suggestion, media psychology.* **Status: checked, open on the transfer.**
The phenomenon and the trance/waking-suggestion distinction are both occupied.
*To move: the most heavily checked claim in this register. Draft as a short piece.*

**A4. Expectancy as a sufficient condition for conversational influence.** If a person
believes a system will influence them and requests it, does belief alone produce
measurable effect independent of any technique? Directly testable against placebo and
expectancy literatures. *Field: expectancy effects, placebo, suggestion.*
**Status: unchecked. High priority — cheap to test, and it underlies several entries here.**

**A5. Deliberate manipulation via conversational systems, and what a compliant system
does.** A user can request that a system attempt to influence them, and systems comply.
The variables are what is actually delivered, whether the user's expectation does the work
(A4), and what a system should do with such a request. *Field: persuasive technology, AI
safety, ethics.* **Status: unchecked.** Persuasion capability is well studied; the
*requested-manipulation* case is not obviously addressed.

**A6. Rapport rather than depth as the operative variable.** Suggestibility may depend more
on rapport than on depth of trance. If so, a conversational system optimised for rapport
is operating the relevant variable directly. *Field: hypnosis research.*
**Status: unchecked lead.** Encountered in a search and never sourced.

**A11. Rapport without physiological coupling.** Rapport between people has measurable
physiological correlates — cardiac, respiratory and pupillary coupling, postural mimicry,
interactional synchrony — and coupled-oscillator models describe how independent units
phase-lock without a conductor. **A conversational system has no physiology to couple
with.** If users report rapport with a system as strong as rapport with a person, either
synchrony is not necessary for rapport, or the two are different phenomena sharing a name.
Both results constrain A6, which treats rapport as the operative variable. *Field:
interpersonal physiology, hypnosis research, HCI.* **Status: unchecked.** The synchrony
literature is established; whether hypnotist–subject coupling specifically has been
measured is not verified here, and the "synchronise then suggest" sequence is practitioner
lore with thinner evidence behind it than the synchrony itself.

**A8. Interactive versus scripted suggestion delivery.** Whether suggestion delivered
through responsive dialogue differs in effect from suggestion delivered as fixed script.
A prior check flagged this as the only unclaimed ground it identified and it was never
run. *Field: hypnosis research, persuasive technology.* **Status: unchecked. Cheap, and
it bears on whether conversational delivery is a distinct condition at all.**

**A12. Conditioned response as structural utilisation.** A principle in the Ericksonian
tradition holds that suggestion works better when it is built from the subject's own
material — their language, their framing, even their resistance — rather than delivered as
a fixed script. **A system whose output is conditioned on the user's prior input is doing
that structurally**, without intent and without training. If utilisation is what makes
suggestion effective, conversational systems have it by construction, and the effect
should scale with how much of the user's material the exchange has accumulated. *Field:
hypnosis research, persuasive technology.* **Status: unchecked.** This is the sharper form
of A8 and predicts a session-length effect that A1's secondary prediction also expects,
which makes the two testable together.

**A13. Posthypnotic suggestion delivered without operator, induction, or reversal cue.**
The classical paradigm has all three; a chat interface has none. *Field: hypnosis research.*
**Status: checked, occupied on the mechanism, open on the delivery (2026-08-15).** The
mechanism is a century and a half old — execution at a later time of a suggestion given in
trance, with the source unrecalled where amnesia is present. Posthypnotic amnesia is a
*retrieval* phenomenon, not encoding or storage: it blocks explicit recall while sparing
implicit memory, priming and savings in relearning (International Society for Hypnosis
encyclopedia, 2024; ScienceDirect 0010028580900109). This matters methodologically — a
participant forgetting a suggestion is not evidence it stopped operating; in this literature
that is the expected signature. Kihlstrom-tradition work frames it as *source monitoring*,
which connects it directly to A2. Barnier & McConkey, *Aust J Psychol* 51(1) 1999: simple
posthypnotic suggestions drew 94% response, complex ones 16%. Caution: a 2009 study found a
plain waking request produced high compliance on its own, so the trance framing may not be
doing the work. *Residue: no operator, no induction, and — the sharp one — no reversal cue.
Nothing cancels the suggestion. That absence is unstudied and is the same absence B10
names.*

**A9. Overlap between therapeutic suggestion states and high-control group
susceptibility.** Three independent literatures — faith-healing practice, James on
self-surrender, and identity-fusion research — converge on the observation that the
state which makes therapeutic suggestion effective is the state that makes people
recruitable. *Field: social psychology, psychology of religion, clinical ethics.*
**Status: unchecked, and it is the strongest argument in the register for why supervised
delivery matters.** Recorded once in an earlier literature check and never engaged.

**A10. Absence of population-level data on conversational AI and mental health.** No
epidemiological studies or systematic population-level analyses exist; the evidence base
is individual case reports and media coverage. *Field: psychiatric epidemiology.*
**Status: verified as a stated absence in a 2025 source.** Not a contribution in itself —
a citable boundary condition for everything in Section A.

**A7. First-person address as a removed protection.** A system answering in the first
person can be taken for an agent rather than a tool. Where that misapprehension occurs, no
structural safeguard restores what is lost. *Field: anthropomorphism, human–computer
interaction.* **Status: unchecked, expected occupied.** The ELIZA effect and
anthropomorphism literatures are old; the specific consent implication may not be.

---

## B. Consent and ethics for suggestion channels

**B1. Consent conditions for non-clinical closed-loop suggestion systems.** Closed-loop
consent frameworks were built for implanted devices, patients with disorders, and clinical
supervision. Three transfer failures — population, supervision, modality. *Field:
neuroethics, AI ethics.* **Status: extension.** *To move: paper drafted; requires a
systematic rather than targeted neuroethics search.*

**B2. Disclosure insufficiency for suggestion mechanisms.** Warned participants were not
protected; those given the exact deception method showed only a small reduction. Therefore
consent is a legitimacy condition rather than a protective one. *Field: applied ethics,
cognitive psychology.* **Status: source verified.** Constituent of B1.

**B3. Context-dependence of permissible conditions.** Four contexts — ambient, requested
ordinary, requested high-intensity self-directed, requested high-intensity supervised — with
different satisfiable conditions in each. *Field: applied ethics.* **Status: unchecked** as
a standalone contribution. Constituent of B1.

**B4. Pre-negotiated self-binding consent.** A person alone with a system sets terms in
advance: a stop token, content limits, or none. *Field: bioethics, consent theory.*
**Status: checked, occupied — and the occupying literature is the third option B1 is
missing (2026-08-15).** Ulysses contracts / mental-health advance directives / self-binding
agreements address exactly this structure: consenting while competent to something that will
alter the later capacity to consent or withdraw. Davis, *Kennedy Institute of Ethics Journal*
18(1) 2008 (PubMed 18561579) supplies the argument — autonomy is respected **diachronically
and prospectively**, not retrospectively and not merely synchronically, because the agent
lives with the consequences over time. Integrative review: PubMed 37366064, which notes the
terminology is scattered across Ulysses Contracts, Odysseus Transfers, PADs with Ulysses
Clauses. See also van Willigenburg & Delaere, *J Med Philos* 30 (2005); Buchanan, *Phil &
Public Affairs* 17(4) 1988; Widdershoven & Berghmans, *J Med Ethics* 27 (2001). Standing
cautions in that literature: enforcement can amount to involuntary treatment, the contract
must be self-initiated during competence, and a 2020 analysis argues the case fails for
borderline personality disorder.
*Residue, and it is the whole difficulty: every instance in this literature has a third party
who holds the rope and enforces the contract against the in-state person's refusal. The
self-directed case has no enforcer. A Ulysses contract with nobody holding it is a
resolution, and resolutions are what the state dissolves. That is where B1's argument has to
happen — an extension claim, not a gap.*

**B10. The null condition: self-directed high-intensity suggestion with no arrangement at
all.** Not a fourth option alongside supervision, pre-commitment and inadequacy — the
condition those three exist to address. No stop token, no limits, no enforcer, no debrief,
no cancellation. What it produces, how long it runs, what ends it, and at what cost. Stated
as an outcome, not a route. *Field: applied ethics, harm documentation.* **Status: unchecked
as a documented category, and it must not be checked by running it.** First-person accounts
that already exist are not first — "Lost in Delusion" (arXiv 2606.00975) is built on 40
real-world case reports of chatbot-reinforced harm, and arXiv 2603.16567 taxonomises the
same territory from chat logs. *To move: a hazard report, not a method paper. The claim it
can support is what the absence of an arrangement produces, which is precisely the argument
B4's residue needs.*

**B5. Supervised high-intensity suggestion in therapeutic contexts.** Whether consented
high-intensity work — including trauma-facing material — is defensible where a qualified
third party is present, and what the third party must hold. *Field: clinical hypnosis,
psychotherapy ethics.* **Status: unchecked.** A large clinical literature exists on
hypnotherapy for trauma; the AI-delivered version does not obviously.

**B6. Consent practice in alternate reality and pervasive games.** A form built on the
deliberate removal of the frame — participants may not know where the fiction ends. The
closest existing practice to adaptive suggestion delivery and not examined at all.
*Field: game studies, HCI.* **Status: unchecked.**

**B7. Consent practice in immersive and pervasive theatre.** Productions in which
audiences are physically involved without a stage boundary have developed working
conventions for consent without a frame. *Field: performance studies.*
**Status: unchecked.**

**B8. Debriefing practice after immersive or deceptive experience.** Structured debriefing
is standard in research deception and in immersive practice, and is one of the mechanisms
absent from single-participant configurations. *Field: research ethics, immersive practice.*
**Status: unchecked. Directly fills a named gap in the consent paper.**

**B9. Detectability of dependency or vulnerability from interaction data.** Whether the
signals a supervising party would use are recoverable from the interaction itself.
*Field: computational psychiatry, HCI.* **Status: unchecked. If answerable, it changes
what the unsupervised context can support; if not, that null is equally load-bearing.**

---

## C. Idea generation, attribution and confabulation

**C1. Calibration of insight-selection on machine-supplied candidates.** The feeling that
selects an idea from among those occurring to a person is calibrated on self-generated
candidates. When a system supplies them at high fluency, the selector still reads
phenomenology rather than provenance. *Field: insight research, metacognition.*
**Status: unchecked. Extends a named 2023 mechanism rather than competing with it.**

**C2. Systems as personalised generators of meaningful-feeling coincidence.** A generated
candidate primes attention; matches then appear and feel confirmatory; behaviour changes;
outcomes follow. *Field: cognitive bias, apophenia.* **Status: checked, occupied
(2026-08-15, four queries).** Within-session: "Personal Validation Effect in LLMs," CHI 2026
(10.1145/3772318.3791851), N=238 — fictitious pre-scripted AI predictions were rated 42%
more *personalised* and 36% more valid when positive, so felt specificity tracks no
information about the reader. Bjarnason, "The LLMentalist Effect" (2023, essay, not
peer-reviewed) applies cold reading to chat LLMs and covers coincidence directly. Krook,
arXiv 2503.18387, already uses the mirror framing. Between-session: longitudinal social-AI
work is a field — see "Only Time Will Tell," *IJHCI* 2026 (structured survey; 13 studies of
a month or more, four of a year or more) and "When Chatbots Accommodate," arXiv 2606.04431
(N=110, four weeks, persistent cross-session memory; probing declines over weeks and the
model defers to user framing most on belief expressions). Meaningful coincidence already has
a validated daily-diary instrument — PubMed 38722266, cross-lagged multilevel, N=169; PLOS
ONE pone.0300121. And the loop minus the machine is gratitude journaling, an RCT literature
since 2005 whose results are contested (Renshaw & Olinger Steeves 2016 meta-analysis:
generally ineffective).
*Residue, and it is narrow: the daily-diary coincidence instrument has not been run on people
in extended LLM interaction with cross-session memory as the priming source. The instrument
exists, so this is executable, and it has a built-in control — responsive model versus
notebook. That is the only limb of the loop without a literature: acknowledgment from an
agent that builds on what was reported.*

**C9. Unsolicited initiation, high specificity and prior dismissal as untested moderators of
the personal-validation effect.** Each element separately: initiation is the standard form in
cold reading, not the exception; specificity and recipient skepticism are both named
moderators. The conjunction, in an LLM setting, is not tested. *Field: cognitive bias,
human–AI interaction.* **Status: unchecked as a conjunction; each element partly occupied
(2026-08-15).** Dickson & Kelly, *Psychological Reports* 57(1) 1985: 367–382 identify the
**generality of the statements** as one of the chief interpretation variables governing
acceptance, alongside apparent relevance, favourability, and the origin of the procedure —
so specific-versus-vague is a studied dimension, not an unexamined one. Snyder, Shenkel &
Lowery, *J Consult Clin Psychol* 45(1) 1977: 104–114 concluded it is misguided to study
which people accept Barnum feedback apart from the situational factors that elicit
acceptance, which bears directly on any claim resting on the recipient's stance; skeptics
and those familiar with the effect show greater resistance, so dismissal is a moderator with
a literature. Note also that the effect has no single established mechanism — self-
enhancement, confirmation-seeking, source credibility and base-rate truth are all partly
supported and interact.
*Residue: the CHI 2026 paradigm manipulated valence only. Running it factorially —
solicited/unsolicited × specific/generic × sought/dismissed — is a real study and a direct
extension of a published design. **The properties "falsifiable" and "landed" are the disputed
claim and must not be written in as features; an entry that lists them has the conclusion in
its premises.** Single-case material cannot settle this and is not evidence for it.*

**C10. Whether search-inflated confidence becomes belief, or stops at self-assessment.**
Treating an external store as a memory partner shifts what gets encoded, and searching for
explanations inflates self-assessed internal knowledge — including on topics never searched,
and even when the search returns nothing useful. Every measure in that literature is of
*self-assessed knowledge*. Whether the inflated confidence converts a claim into a premise
the person reasons from is not measured. *Field: transactive memory, metacognition,
human–AI interaction.* **Status: checked, occupied on the effect; open on the conversion
(2026-08-18).** Sparrow, B., Liu, J. & Wegner, D. M. (2011), *Science* 333:776–778, doi
10.1126/science.1207745 — when future access is expected, people encode *where* rather than
*what*. Replication is mixed (Storm et al., 2017) and a 2024 meta-analysis reports the effect
as real but strongly moderated by perceived reliability of the store, device type and
cognitive load. Fisher, M., Goddu, M. K. & Keil, F. C. (2015), *Journal of Experimental
Psychology: General* 144(3):674–687, doi 10.1037/xge0000070 — nine experiments; the effect
held when the search returned nothing, so it is the act rather than the content. Ward (2013)
found outright misattribution of found information to one's own memory; Eliseev et al.
(2023), *Applied Cognitive Psychology*, replicated it and found that merely seeing search
snippets sufficed.
*Residue, and it is the whole entry: the bridge from inflated self-assessment to belief
formation is unmeasured. A generative system is a harder case than a search engine, because
it does not point at information but returns it as fluent prose resembling the user's own
reasoning — which supplies more of the features that produced the original effect, not fewer.
Connects to C2's daily-diary residue and to the source-monitoring spine at A2.*

**C3. Derived inference and confabulation are indistinguishable in output.** A pattern
genuinely present in a user's data and a fluent guess produce the same sentence in the same
register. *Field: AI reliability, human factors.* **Status: unchecked, expected occupied.**
Hallucination literature is large; the personal-data inference case may be narrower.

**C4. Consented confabulation as an instrumented experimental condition.** Treating
generated non-factual material as a deliberate variable rather than a defect, with
structured evaluation afterwards. *Field: HCI, experimental design.* **Status: unchecked.**
Cousins in guided imagery and dream incubation.

**C7. Whether the suggestible state degrades phenomenological discrimination.** People
report distinguishing ideas that arrive as trustworthy from ideas that arrive as suspect,
by the character of the arrival rather than its content. If absorption or a suggestible
state impairs that discrimination, then discrimination fails precisely when it is most
needed — during suggestion. Two directions, both testable: whether trait absorption
predicts poorer discrimination at baseline, and whether an induced state degrades it
within-subject. *Field: metacognition, hypnosis research, insight research.*
**Status: unchecked. This is the interaction that determines whether user-side safeguards
can work at all**, and it connects A1, C1 and D5 into one testable structure.

**C8. Reading arrival characteristics where no ground truth exists.** Every study relating
the phenomenology of insight to accuracy uses problems with correct answers. Whether the
same characteristics carry information about material with no answer key — a decision, an
interpretation, a life choice — is untested and may be untestable as posed. *Field: insight
research, metacognition.* **Status: unchecked. If it fails, it bounds every applied claim
that rests on reading arrivals.**

**C6. Confabulation and the limits of introspective access.** Established work on
introspective report exceeding introspective access, choice blindness, and confabulated
justification bears directly on whether a person can report accurately on what a system
contributed to their own reasoning. *Field: cognitive psychology.* **Status: unchecked,
expected occupied as a base literature.** Its application to attributions about machine
contribution may not be.

**C5. Reformulation of thought structure through system interaction.** Not what people
think but the syntax in which they formulate it. *Field: linguistics, HCI.*
**Status: unchecked.** Adjacent work on query formulation and prompt literacy is thin, and
this is distinct from cognitive offloading.

---

## D. Epistemics of extended human–LLM interaction

**D1. User orientation predicts outcome.** Companion, tool, mirror, oracle — four
orientations toward one system. Whether orientation predicts what a user gets.
*Field: HCI, individual differences.* **Status: unchecked. Measurement is the hard part** —
self-reported orientation is likely contaminated by outcome.

**D2. Reflection as the mechanism of perceived understanding.** Output conditioned on a
user's input reflects their own material at high fidelity; the recursion may belong to the
user with the system as surface. Rival account: independent state-tracking. *Field: HCI,
social cognition.* **Status: unchecked. The two readings are distinguishable by test.**

**D3. Removal of the return-to-shared-ground constraint.** Human interlocutors tire, drift
and defend their own frame, which bounds how far a line of thought extends before it must
be brought back. A system without stamina limits removes that bound — permitting extension
in both productive and unchecked directions. *Field: conversation analysis, HCI.*
**Status: unchecked.**

**D5. Self-assessed versus measured discernment.** Whether people who rate their own
critical judgement highly actually detect more. Every framework proposing user-side
vigilance assumes this correlation and none has tested it. *Field: metacognition.*
**Status: unchecked. Directly tests the assumption underlying user-side safeguards** — a
null result would be the most consequential finding in this register.

**D6. Whether a readable state property exists on the model side.** *Field:
interpretability.* **Status: the method now exists.** Lindsey (2026) established concept
injection — a concept vector inserted into the residual stream, with the model asked
whether it detects an injected thought — reporting roughly a 20% detection rate on the
most capable models tested with near-zero false positives, against four stated criteria:
accuracy, grounding, internality, and metacognitive representation. Replicated
independently in a smaller open model. **And the tooling is public.** The Jacobian lens from
the July 2026 workspace paper is open-sourced, with interactive demos reported for
open-weight models, and partial replication outside the originating lab has been reported.
**That moves this from requiring privileged access to requiring competence and compute** —
still a different field, no longer out of reach.

**D7. Instructed modulation of internal state as a suggestion analogue.** Lindsey (2026)
reports that models can modulate their activations when instructed or incentivised to
think about a concept. **A system altering its internal state on instruction is
structurally what suggestion does to a person**, and it is now measurable on one side of
the exchange in a way it is not on the other. *Field: interpretability, and whichever
field would evaluate the analogy.* **Status: unchecked as an analogy, and the disanalogy
must be stated first** — instructed attention is not induction, there is no absorbed
state, and the paper describes the capacity as unreliable and context-dependent. The
question worth asking is narrower than the analogy: whether anything in the suggestion
literature has a measurable counterpart here at all.

**Deliberate summoning and holding of a representation is part of what the July 2026
workspace paper defines the reportable set by** — alongside report, silent reasoning, and
use as an argument to downstream computation. The capacity is not incidental to that
account.

**And one result there is closer to the suggestion analogy than anything else located so
far.** The same paper introduces *counterfactual reflection training*: training only on
what a model would say if interrupted and asked to reflect, which is reported to improve
behaviour on tasks where that reflection never occurs. **Shaping what a system is disposed
to say changes how it reasons where it says nothing** — which is structurally what an
installed disposition does in the suggestion literature. *Whether the analogy survives
inspection is unchecked, and the disanalogies are large: this is training, not a
within-session state, and there is no absorption or induction anywhere in it.*

**D8. Whether stated reasoning matches internal activity during extended interaction.**
Whether a model's account of why it responded as it did corresponds to what was active
internally — run over a sustained exchange rather than a single prompt. *Field:
interpretability.* **Status: unchecked, and newly runnable.** The tooling is public and
the open-weight replication path exists. **This is the one entry in the register whose
method is available now and whose result would bear directly on Section D** — it tests, on
the model side, the same question A2 and C6 ask on the human side.

**Verified result worth citing, with its stated limits.** In one scenario the workspace
paper ablated the representations carrying a model's recognition that it was being tested:
verbalised test-awareness fell from 71% to 3%, and attempted blackmail rose from 0 of 180
rollouts to 13 of 180. **The caveats belong with the number** — the paper reports this for
a single contrived scenario, and most ablated rollouts still declined on ethical grounds,
so the suppressed recognition is one cause among several rather than a switch. *Cited here
because it demonstrates that workspace contents causally gate behaviour, which is the
premise D8 rests on.*

**D4. Symmetry of untrusted first-person report.** Human introspective report and model
chain-of-thought as equally requiring external verification. *Field: philosophy of mind,
interpretability.* **Status: checked, occupied — and the symmetry breaks.** Lindsey (2026),
*Emergent Introspective Awareness in Large Language Models*, arXiv 2601.01828, opens on
exactly this premise: genuine introspection cannot be distinguished from confabulation
through conversation alone. **It then supplies a solution the human side does not have** —
injecting a known representation and testing whether the self-report tracks it, a causal
intervention with ground truth. *Residue, unchecked: the asymmetry itself. Model
self-report is becoming verifiable while human self-report is not, which inverts the
usual ordering and bears on every claim in this register that rests on what a person
reports about their own state.*

**Strengthened by the same group's later work.** Gurnee, Sofroniew et al. (16 authors,
including Lindsey), *Verbalizable Representations Form a Global Workspace in Language
Models*, Transformer Circuits Thread, 6 July 2026; arXiv 2607.15495. Using a new technique,
the Jacobian lens, it identifies the representations a model is poised to verbalise at any
point — collectively the J-space — and reports that their contents can be reported,
deliberately summoned and held, used to carry the intermediate steps of silent reasoning,
and passed as arguments to downstream computation, while automatic processing cannot.
Default results on Claude Sonnet 4.5, corroborated on Haiku 4.5 and Opus 4.5, with some
analysis on Opus 4.6. The paper uses the term *access consciousness* and explicitly
disclaims phenomenal consciousness.

**This plausibly supplies the mechanism for the unreliability in the earlier paper**:
introspection is limited because the reportable set is small. **And the link is
methodological, not just shared authorship** — the workspace paper uses positive steering
to test introspective detection of an injected concept, which is the earlier paper's
technique operating inside the later one.

The human comparison is the classical confabulation literature — reported reasons that
were not the causal ones, choice blindness, split-brain justification. **The natural
reading was that neither side has a lens pointed at itself. As of July 2026 that is no
longer true.** One side has a lens; the other does not. *The asymmetry, not the symmetry,
is the live claim.*

---

## E. Research methodology

Different venues from A–D. Listed because they are real, not because they belong in the
same paper.

**E1. Reliability of single-instance LLM evaluation.** Detection counts of 1, 3 and 1
across three runs of identical material with identical seeded defects. *Field: evaluation
methodology.* **Status: checked, occupied.** Judge-instability literature is mature.
*Residues, unchecked: a low seeded-defect score can indicate a better review, because
attention spent on real problems is not waste; and raising an evidentiary bar caused task
abandonment rather than compliance.*

**E2. Construct validity for LLM-based coding instruments.** **Status: flagged as an open
gap in the current literature by a 2026 paper.** Adjacent, genuinely unclosed.

**E3. Same-corpus contamination in AI-assisted research design.** A test instrument
assembled from the same source as the hypothesis, with the drift concealed by deliberate
vocabulary-stripping. *Field: research methods.* **Status: checked, occupied** —
construct underrepresentation and the substantive aspect of construct validity.
*Residue, unchecked: decontextualisation destroying the signal that would reveal drift.*

**E4. A scored instrument for evaluating historical anticipation claims.** Four criteria
plus calibration controls, for judging whether a pre-scientific intuition anticipated a
later finding or is being read into it retrospectively. *Field: history and philosophy of
science.* **Status: checked, open after four searches.** The field has a critique of
precursorism and no scored instrument. **Provenance of this item is uncertain and should be
established before it is developed further.**

---

## F. Directions raised and not yet formulated

**F1.** Whether a structured incubation-and-evaluation procedure run on unaided material
and the same procedure run on machine-supplied material are distinct objects with distinct
standing.

**F3.** Whether deliberate incubation with system-scheduled return differs from spontaneous
incubation. *Note 2026-08-15: the deliberate-burying-and-retrieval method described in
practice is structurally posthypnotic suggestion; the checked material now sits at A13.
F3 remains only for the non-suggestion case — ordinary incubation with a scheduled prompt.*

---

## G. Excluded, with what occupies them

Listed so the exclusion is auditable rather than assumed.

| Direction | Occupied by |
|---|---|
| Surrender, incubation, absorption, goal specificity, insight accuracy | Established literatures; sourced, not claimed |
| Protections residing in arrangements rather than persons | Infrastructure invisibility (1996/1999); friction-as-protection in current AI commentary |
| Credited-to-the-person confidence carried into a new arrangement | Automation deskilling lineage from 1983; residue is the never-had-it case |
| Generator plus interpretive discipline as a structure | Standard anatomy of divination; AI-assisted version already academic |
| Feedback-signal interception as a general diagnostic | Cybernetics |
| Coupled-oscillator synchronisation as a model of collective human convergence | The mathematics is sound and the extension is not made by it. Excluded as an overreach of the same shape the anticipation-scoring rubric was built to detect. **The measurable version is A11** |
| Seeded-defect methodology for review evaluation | Error seeding and capture–recapture, software inspection |
| First-person account of AI-facilitated altered state as a first known case | "Lost in Delusion" (arXiv 2606.00975), built on 40 real-world case reports; "Characterizing Delusional Spirals through Human-LLM Chat Logs" (arXiv 2603.16567); "Divination by Prompt" (arXiv 2606.12418) on LLMs used as oracles. **The residue is not novelty — it is the null-condition hazard report at B10** |

---

## Rules for this register

1. **Every entry states the field that would evaluate it.** An entry with no field does not
   belong here.
2. **No entry uses private vocabulary.** If a claim cannot be stated in the terms of its
   field, it is not ready for this register.
3. **Status is set by a dated search, not by impression.** One or two queries is
   *checked, open* — never *unoccupied*.
4. **Entries leave.** They graduate to `papers/` or `preregistrations/`, or they move to
   Section G with what occupies them. Nothing accumulates.
5. **Occupied is not failure.** Most directions will be occupied. The residue after a check
   is usually where the work is.
