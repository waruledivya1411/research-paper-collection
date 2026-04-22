# Summary insights — day 1 set (30 papers)

This note distills **cross-paper structure** in the set you assembled (dopamine / neurotransmitter **electrochemical and optical** sensing, plus a spread of **reviews**). It is a reading aid, not a replacement for the primary sources.

## What this literature cluster is “about”

- **Target chemistry:** catecholamine / biogenic amine redox and closely related “small-molecule” messengers, with **dopamine** as the most repeated exemplar. Several papers are explicitly **DA vs interferent** stories (e.g., ascorbate / uric acid), which is the classic head-to-head in extracellular electrochemistry.
- **Method families in tension:**
  - **In vivo, short timescale (subsecond)**: fast-scan cyclic voltammetry and carbon microelectrodes appear as a canonical backbone; added foundational entries highlight **FSCV readout, background subtraction, and multicomponent “resolving”** analysis, not just electrode recipes.
  - **Bench / biofluid, multi-analyte quantification:** chromatography- and mass-spectrometry-oriented bioanalysis papers emphasize that **sampling, separation, and authentic matrices** are where claims either survive or break.
  - **Optical circuit readouts (fiber photometry) and photonic/fiber device engineering** appear as parallel tracks that trade **chemical identity** and **invasiveness/artifact profiles** for cell-type- or network-level readouts in behaving animals.

## Recurring “engineering pressures” (useful as a checklist)

1. **Selectivity vs. identity:** electrochemical “detect dopamine nM in AA/UA” is one layer; in vivo, **multiple co-released redox-active species and drift** are the harder layer. Chemometric and waveform/instrumentation strategies address identity at the *data* level, not just coating chemistry.
2. **Stability and calibration:** **enzymatic** routes buy specificity, but introduce **activity loss, leaching, and calibration drift**; **nanocomposites** buy catalysis but raise **reproducibility and aging** questions.
3. **Translation language:** a subset frames sensors toward **depression and psychiatric** contexts (and broader “brain disorder diagnostics” framing), which is useful as a prompt to be explicit about **peripheral vs central** interpretation when reading claims.

## Suggested reading order (if you are building toward a project proposal)

1. A broad survey you already have: **Su et al. (2020)** or **Hussain et al. (2023)** to align vocabulary and analyte class expectations.
2. A modality comparison: **Niyonambaza et al. (2019)** to force a deliberate choice: electrochemistry vs sampling+MS vs photonics, given your animal model, timescale, and “identity vs proxy” needs.
3. A dopamine + interferent *material* anchor: **Oh et al. (2016)** (or similar CNT/functionalized carbon studies in your set).
4. The **FSCV triad (foundational)**: subsecond in vivo (Robinson et al. 2003) → **background handling** (Hermans et al. 2008) → **unmixing / resolving signals** (Heien et al. 2004), optionally **sensitivity** (Keithley et al. 2011) and the **CFME** primer (Huffman and Venton 2009).
5. A photonics / circuits complement: **Wang et al. (2021)** on fiber photometry, then **Zheng et al. (2026)** (deep multimodal fiber probes) if you are thinking about device integration, not a simple electrode.

## Gaps to flag for your own next notes

- **Standard reporting across papers** varies widely (LOQ vs LOD, matrix, chronic duration). When two papers “look” comparable, check **waveform, reference electrode placement, and whether data are background-subtracted and how**.
- **Clinical and wearable claims** in reviews often outrun the demonstrated evidence in a given matrix; use **Matys / Zhu**-style separations literature as a sanity check when you need **ground truth**.

## Quick “method → question it answers” map

| If your question is… | Start from… |
| --- | --- |
| “What is happening on millisecond to second scales in behaving animals?” | FSCV + carbon microelectrode lineage (e.g., Robinson 2003; Hermans 2008; Heien 2004) |
| “What is the *absolute* amount after extraction / microdialysis?” | Bioanalytical + separation/MS side (e.g., Matys 2020; Zhu 2023) |
| “How do I compare optical population signals to electrochemical ‘concentration-like’ readouts?” | Fiber photometry review (Wang 2021) + any electrochemical in vivo method chapter paper you adopt |

If you add new PDFs, keep **one `master_table.csv` row per DOI** to avoid the duplicate-citation problem that appeared in the raw paste.
