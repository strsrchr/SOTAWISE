# Contributing to SOTAWISE

Welcome. We treat human performance and biological protocols with the same architectural rigor as open-source software. 

To maintain the integrity, safety, and scientific validity of this repository, we strictly govern how changes are made. This document outlines the process for contributing to both the **Documentation (The Protocol)** and the **Software (The Code)**.

## ⚖️ 1. The Dual-License Acknowledgment
Before contributing, understand our licensing architecture:
*   **Protocol Contributions:** Any text, schedules, or methodologies you contribute will be licensed under **CC BY-NC 4.0**.
*   **Code Contributions:** Any scripts, trackers, or software you contribute will be licensed under the **MIT License**.
*   By submitting a Pull Request, you explicitly agree to release your contributions under these respective licenses.

---

## 🛤️ 2. Contribution Pathways

We categorize contributions into three distinct tracks. Choose the appropriate path:

### Track A: Maintenance (Direct Pull Request)
For non-material changes that do not alter the protocol's biological mechanics.
*   Typographical errors or formatting fixes.
*   Fixing dead links to scientific papers.
*   Updating standard documentation (e.g., this file or the README).
*   **Action:** Submit a Pull Request directly.

### Track B: Code & Trackers (Direct Pull Request)
For improvements to the MIT-licensed tracking scripts, schemas, or data visualizers.
*   Bug fixes in Python/JS scripts.
*   Enhancements to the JSON data schema.
*   **Action:** Submit a Pull Request. Ensure any code changes are heavily commented and do not break the existing data schemas.

### Track C: Protocol Interventions (The RFC Process)
**STOP.** You cannot directly submit a Pull Request to change the protocol, add a supplement, alter a dosage, or modify a behavioral timing. 

Any material change to the biological protocol must go through the **Request for Comments (RFC)** process to ensure peer review.

---

## 🔬 3. The RFC (Request for Comments) Process

If you want to propose a change to the core protocol, you must prove its efficacy. 

### Step 1: Open an RFC Issue
Navigate to the "Issues" tab and select the **Protocol Enhancement (RFC)** template. You must provide:
1.  **The Proposed Intervention:** (e.g., "Shift Vitamin D intake from evening to morning.")
2.  **The Biological Mechanism:** Explain *how* it works (e.g., "Circadian alignment of cholecalciferol absorption...").
3.  **Scientific Backing:** You must provide at least two (2) peer-reviewed citations (DOI or PubMed links).

### Step 2: The Hierarchy of Evidence
The community will evaluate your RFC based on the strength of your evidence. We prioritize data in the following order:
1.  **Gold:** Systematic Reviews and Meta-Analyses of Human RCTs.
2.  **Silver:** Double-blind, placebo-controlled Human RCTs.
3.  **Bronze:** Human observational studies.
4.  **Rejected:** Rodent studies, *in vitro* studies, expert opinions, and personal anecdotes are **not** sufficient to alter the core protocol.

### Step 3: Peer Review & Consensus
Maintainers and the community will review the literature. We look for contraindications, dosage safety, and statistical significance. 

### Step 4: The Pull Request
If the RFC is approved by the maintainers, you (or another contributor) may open a Pull Request incorporating the change into the Markdown files and adding the citations to our `.bib` file.

---

## 🏛️ 4. Code of Conduct
We debate the data, not the individual.
*   **Be rigorous:** Attack the study design, sample size, or mechanism, never the contributor.
*   **Be precise:** Avoid "suitcase words" (e.g., "It boosts energy"). Use precise physiological terms (e.g., "It upregulates dopamine receptor density").
*   **Be objective:** Leave dogma and guru-worship at the door. If new data invalidates an existing protocol module, we remove the module.
