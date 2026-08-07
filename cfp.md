---
layout: default
title: Call for Papers
---

# Call for Papers

## AI Foundations for Power Grids: From Models to Deployment at Scale
### A NeurIPS 2026 Workshop

**Tagline.** *What would it take for AI models to enter a power grid control room? A workshop on benchmarks, model training, and real-world considerations.*

**Date & venue.** December 11 or 12, 2026 – co-located with NeurIPS 2026 in **Sydney, Australia**. In person.

**OpenReview.** [openreview.net/group?id=NeurIPS.cc/2026/Workshop/AI4PowerGrids](https://openreview.net/group?id=NeurIPS.cc/2026/Workshop/AI4PowerGrids)


## Scope

The power grid is one of the most consequential open problems in applied machine learning – hard physics constraints, real-time closed-loop operation, structural non-stationarity, and societal-scale consequence – yet it attracts a fraction of the methodological attention given to vision, language, or biology. This workshop brings power systems to the ML community as a first-class methodological challenge and focuses on the central bottleneck: **how to evaluate learning-based methods under realistic and evolving operating conditions.**

Themes we especially welcome:

- **Open, realistic datasets** as a first-class community deliverable, beyond legacy IEEE test cases.
- **Feasibility as a metric** – what it means for a stochastic model to "respect the physics", beyond aggregate error.
- **Structural, not just sample, shift** – real grids change topology hourly and generation mix yearly.
- **Foundation-model claims for grids** and the criteria by which to evaluate them.
- **Components vs. systems** – a 99% accurate surrogate can destabilise the loop it sits inside.
- **From eyes-on to eyes-off** – offline, advisory, and narrow-autonomy stages each demand different evidence.

## Submission tracks

Authors select one primary track at submission:

1. **Methods with rigorous evaluation** – new models evaluated beyond in-distribution error on a static test case.
2. **Benchmarks, datasets, and evaluation protocols** – contributions whose primary artifact is *how* we measure.
3. **Position and empirical-evaluation papers** – systematic studies, audits, or arguments about what good evaluation should look like.
4. **Negative results and failure modes** – short papers documenting where learned components break, especially under structural or distributional shift.

## Evaluation checklist

Submissions must include a short **domain checklist** at the end of the paper (outside the 4-page limit). For each item, state where it is addressed or justify "not applicable":

1. **Physics feasibility.** For methods producing grid quantities: is feasibility reported under the full **AC** power-flow equations, not only the linearised **DC** approximation? Include constraint-violation statistics, not just aggregate error.
2. **Out-of-distribution evaluation.** Is the method evaluated on at least one network topology, generation mix, or operating regime not seen in training?
3. **Failure modes.** Are failure cases reported alongside aggregate metrics – worst-case behaviour, tail statistics, or qualitative examples?
4. **System-level effect** (where applicable). For components inside a larger system, is the downstream effect reported, not only standalone accuracy?
5. **Data and code.** Will code and data be made available (anonymously at submission, or on acceptance)? A clear release plan is sufficient.

Reviewers score on standard NeurIPS criteria (novelty, technical quality, clarity, significance) **and** on how substantively the paper engages the checklist.

## Format & submission

- **Length:** up to **4 pages** of main content, unlimited references. Appendices are permitted but reviewers are not obligated to read beyond the main text. The domain checklist does not count toward the 4-page limit.
- **Language & file format:** submissions must be in **English** and uploaded as a **single PDF** through OpenReview.
- **Template:** use the [official NeurIPS 2026 style files](https://media.neurips.cc/Conferences/NeurIPS2026/Formatting_Instructions_For_NeurIPS_2026.zip) (LaTeX). Follow the same formatting as main-track submissions.
- **Anonymization:** double-blind. Remove author names, affiliations, acknowledgments, grant identifiers, repository usernames (e.g., GitHub, Hugging Face), personal or institutional project pages, and any other identifying information from the paper and supplementary material. Cite your own prior work in the third person. Any code, data, models, or demonstrations shared during review must be hosted at an anonymous link or repository.
- **Track selection:** authors select one **primary track** at submission via the OpenReview form.
- **Portal:** all submissions via **OpenReview** (link above).
- **OpenReview accounts:** new OpenReview profiles – particularly those created without an institutional email address – may require **up to two weeks** for approval. Please create or update all author profiles well before the submission deadline.
- **Reviews:** each paper receives **3 double-blind reviews**.
- **Camera-ready:** accepted authors will be invited to submit a revised, **de-anonymized** final version incorporating reviewer feedback, within the same 4-page main-text limit. Deadline: **October 15, 2026 (AoE)**.
- **LLM policy:** submissions must comply with the [NeurIPS 2026 Main Track Handbook](https://neurips.cc/Conferences/2026/MainTrackHandbook). Any reportable use of generative-AI or LLM tools in preparing the manuscript must be disclosed in an unnumbered statement immediately before the references. Use of LLMs *as part of the research method* must be described in the paper in sufficient detail for evaluation and reproducibility. Fabricated or hallucinated content is grounds for desk rejection. Reviewers may not use LLMs to write reviews.

## Key dates (all AoE)

| Milestone | Date |
|---|---|
| Submission deadline | **August 29, 2026** |
| Author notification | **September 29, 2026** (mandatory NeurIPS deadline) |
| Camera-ready (de-anonymized) version | **October 15, 2026** |
| Workshop date | December 11 or 12, 2026 (Sydney) |

## Eligibility

- Original work not previously published at an ML venue. Prior appearance in a **power-systems venue** (journal or conference) is acceptable provided this is **explicitly disclosed** and the paper offers new value to an ML audience.
- Work in progress, position papers, and negative results are welcome.
- A paper **currently under review at the NeurIPS 2026 main track** may be submitted, but if it is accepted to the main track, the authors must promptly notify us and withdraw it from the workshop program.
- **Not eligible:** work already published (or accepted, or presented) at NeurIPS, ICML, ICLR, AAAI, or comparable ML venues; work appearing at the NeurIPS 2026 main track; papers outside scope.

## Archival status

**Non-archival** – no formal proceedings. Accepted papers may be posted publicly on OpenReview at the organizers' discretion; authors retain copyright and the right to submit extended versions elsewhere. Per NeurIPS policy, work presented here may later be submitted to a future NeurIPS main track only if **substantially extended**.

## Presentation

Contributed talks (15 min), lightning talks (5 min), and a poster session with all accepted papers.

**Location.** AI4PowerGrids takes place **in Sydney**. NeurIPS workshops are in-person events at their assigned location; there is no option to present at the Atlanta or Paris satellite locations instead.

**Presentation policies.**
- A co-author may present in place of the lead author.
- Remote presentation is **not** available for contributed and lightning talks.
- At least one author or designated presenter should attend the workshop to present an accepted poster. In exceptional cases, the organizers may permit another knowledgeable attendee to present the poster on the authors' behalf. Merely displaying an unattended poster does not constitute presentation.

## Conflicts of interest

**Organizers may not submit.** Authors with a personal COI (advisor/advisee or close collaborator) may not submit. Reviewers recuse on COI; submissions involving organizer-maintained benchmarks are routed to a disjoint PC subset.

## Diversity and inclusion

We encourage submissions from authors of all backgrounds, career stages, institution types, and geographies, and particularly welcome contributions from the power-systems community engaging ML as a methodological challenge.

## Contact

Questions: <ai4powergrids@gmail.com>

**Organizers:** Andrea Britto Mattos Lima (Microsoft Research), Thomas Brunschwiler (IBM Research), Baosen Zhang (University of Washington), Nicolas Christianson (Johns Hopkins University), Wenqi Cui (NYU), Rabab Haider (University of Michigan), Christopher Yeh (Harvard).
