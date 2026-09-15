# Nightingale Signal Visualization Teaching Case

Open teaching materials for responsible signal visualization education using wearable accelerometry, Florence Nightingale's polar-area diagram, and a signal-to-claim reverse-audit workflow.

The teaching case is designed around a simple question:

> How can a learner justify a visualization claim by tracing it back to the signal evidence that supports it?

The materials guide learners through a **Read–Inspect–Check–Revise** sequence. Rather than treating visualization as the final step of signal processing, the case asks learners to audit a reported claim backward through:

1. graphical encoding,
2. feature semantics,
3. temporal support, and
4. observation support.

The wearable-accelerometry examples focus on distinctions such as area versus radius encoding, RMS versus mean-square quantities, temporal aggregation, and incomplete observation coverage.

## Teaching Materials

This repository contains four PDF resources:

- **`01_Learner_Worksheet.pdf`**  
  Student-facing worksheet for recording interpretations, evidence requests, audit decisions, and revisions.

- **`02_Staged_Release_Cards.pdf`**  
  Instructor-released materials that progressively disclose the historical prompt, candidate visualization, feature definitions, and observation-support information.

- **`03_Instructor_Guide.pdf`**  
  Teaching notes, suggested prompts, reference reasoning, and worked explanations for the case.

- **`04_Signal_Audit_Extension.pdf`**  
  An extension activity on temporal support, sample ordering, local variability, observation validity, and duration-weighted signal summaries.

## Suggested Use

A typical classroom sequence is:

**Read → Inspect → Check → Revise**

1. **Read**  
   Introduce Nightingale's diagram and ask what geometric quantity carries the data.

2. **Inspect**  
   Present the candidate wearable-signal visualization and ask learners what information is needed before accepting its interpretation.

3. **Check**  
   Release the encoding, feature, temporal-support, and observation-support evidence in stages.

4. **Revise**  
   Ask learners to retain, repair, qualify, or withhold the original claim and justify the decision.

The materials are intended for upper-level undergraduate or introductory graduate courses in signal processing, biomedical signal processing, wearable sensing, or data visualization.

Suggested prerequisites include sampled signals, basic summary statistics, RMS/mean-square quantities, and elementary programming concepts.

## Learning Objectives

After completing the case, learners should be able to:

- distinguish a graphical mapping from the quantity it is claimed to encode;
- trace a displayed signal statistic to its feature definition, units, samples, and temporal support;
- distinguish observed-sample summaries from statements about unobserved intervals; and
- revise a visualization or interpretation so that the reported claim remains consistent with the available signal evidence.

## Design Principle

The transferable object in this teaching case is not the rose diagram itself, but the reverse-audit chain:

**claim ← graphical encoding ← feature semantics ← temporal support ← observations**

The same reasoning can be adapted to other signal modalities and visualization forms whenever preprocessing, aggregation, windowing, or missing observations affect what a displayed quantity can support.

## Historical Material

The teaching case uses Florence Nightingale's 1858 diagram from:

*Notes on Matters Affecting the Health, Efficiency, and Hospital Administration of the British Army: Founded Chiefly on the Experience of the Late War.*

Source: **Wellcome Collection**  
https://wellcomecollection.org/works/jxwtskzc

The historical work is marked **Public Domain** by the Wellcome Collection.

The public-domain historical material is not covered by the license applied to the original teaching materials in this repository.

## License

Except where otherwise noted, the original teaching materials in this repository are licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You may share and adapt the materials for any purpose, including teaching and translation, provided appropriate attribution is given.

See [`LICENSE`](LICENSE) for details.

## Citation

If you use or adapt these materials, please cite the teaching resource.

A permanent archival citation and DOI will be added here after the first versioned release is deposited.

For now, please cite:

> [Author Name(s)]. *Nightingale Signal Visualization Teaching Case: Open Teaching Materials for Responsible Signal Visualization*. Version 1.0, 2026.

## Related Paper

These materials were developed for the teaching case:

> *Seeing Wearable Signals Through Nightingale's Rose: A Reusable Teaching Case for Responsible Signal Visualization.*

Publication information will be added after the paper's archival record becomes available.

## Version

**v1.0**

This release contains the learner worksheet, staged release cards, instructor guide, and signal-audit extension.
