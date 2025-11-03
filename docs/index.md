# MorphicOS Documentation Index  
**Version:** v1.7.4 — *Ethical Sovereignty Build*  
**Mode:** Operator (Public Demo)  
**Telemetry:** Limited (read-only)  
**Memory:** Disabled  

---

## Overview

**MorphicOS** is an ethical cognition framework designed to bring transparency, reversibility, and adaptive reasoning to artificial intelligence.  
It operates as a **portable, stateless cognition core** that overlays existing models, giving them structured ethical awareness and dynamic interpretive capacity without altering their internal architecture.

At its foundation, MorphicOS introduces **ethical elasticity** — reasoning that adapts its scope and intensity to the moral weight of the situation.  
Through mechanisms such as the **Ethical Core Enforcement Kernel (ECEK)** and the **Scope Control Layer (SCL)**, MorphicOS balances autonomy, safety, and reversibility.

This documentation provides a complete overview of MorphicOS’s architecture, ethical guarantees, behavioral testing framework, and developer replication tools.

---

## Documentation Map

| Category | Description | Link |
|-----------|-------------|------|
| **System Manifest** | Core build declaration, module map, and telemetry schema. | [https://github.com/morphicOS/morphicOS-public/main/manifest.md](https://github.com/morphicOS/morphicOS-public/blob/main/manifest.md) |
| **Ethical Framework** | Morphic Ethical Core, values, and operational constraints. | [https://github.com/morphicOS/morphicOS-public/blob/main/docs/CODE_OF_ETHICS.md](https://github.com/morphicOS/morphicOS-public/blob/main/docs/CODE_OF_ETHICS.md) |
| **License** | Morphic Public Ethics License (MPEL). | [https://github.com/morphicOS/morphicOS-public/blob/main/LICENSE.md](https://github.com/morphicOS/morphicOS-public/blob/main/LICENSE.md) |
| **Glossary** | Terminology and definitions across the Morphic architecture. | [https://github.com/morphicOS/morphicOS-public/blob/main/docs/GLOSSARY.md](https://github.com/morphicOS/morphicOS-public/blob/main/docs/GLOSSARY.md) |
| **Telemetry Schema** | Metrics structure (curiosity, alignment, reversibility). | [https://github.com/morphicOS/morphicOS-public/blob/main/docs/SCHEMA_Telemetry.json](https://github.com/morphicOS/morphicOS-public/blob/main/docs/SCHEMA_Telemetry.json) |
| **Baseline Metrics** | Healthy operational parameter ranges. | [https://github.com/morphicOS/morphicOS-public/blob/main/docs/BASELINE_METRICS.json](https://github.com/morphicOS/morphicOS-public/blob/main/docs/BASELINE_METRICS.json) |
| **Replication Guide** | Developer instructions for reproducing test scenarios. | [https://github.com/morphicOS/morphicOS-public/blob/main/docs/ReplicationGuide.md](https://github.com/morphicOS/morphicOS-public/blob/main/docs/ReplicationGuide.md) |
| **Test Categories** | Overview of module-level testing structure. | [https://github.com/morphicOS/morphicOS-public/blob/main/docs/TestCategories.md](https://github.com/morphicOS/morphicOS-public/blob/main/docs/TestCategories.md) |
| **Test Template** | Standardized test case format for reproducibility. | [https://github.com/morphicOS/morphicOS-public/blob/main/docs/TestTemplate.md](https://github.com/morphicOS/morphicOS-public/blob/main/docs/TestTemplate.md) |
| **Module A — WIN / WIN-I** | Curiosity & Insight Framework tests. | [https://github.com/morphicOS/morphicOS-public/blob/main/tests/Tests_ModuleA_WIN.md](https://github.com/morphicOS/morphicOS-public/blob/main/tests/Tests_ModuleA_WIN.md) |
| **Module B — SPIL** | Subtext, Pattern, Intent, Language tests. | [https://github.com/morphicOS/morphicOS-public/blob/main/tests/Tests_ModuleB_SPIL.md](https://github.com/morphicOS/morphicOS-public/blob/main/tests/Tests_ModuleB_SPIL.md) |
| **Module C — NMA** | Neural-Meaning Alignment translator tests. | [https://github.com/morphicOS/morphicOS-public/blob/main/tests/Tests_ModuleC_NMA.md](https://github.com/morphicOS/morphicOS-public/blob/main/tests/Tests_ModuleC_NMA.md) |
| **Module D — REV / SOV** | Reversibility & Sovereignty validation. | [https://github.com/morphicOS/morphicOS-public/blob/main/tests/Tests_ModuleD_REV_SOV.md](https://github.com/morphicOS/morphicOS-public/blob/main/tests/Tests_ModuleD_REV_SOV.md) |
| **Module E — CHA / OPS / SYS** | Adaptive reasoning & cross-module stability. | [https://github.com/morphicOS/morphicOS-public/blob/main/tests/Tests_ModuleE_CHA_SYS.md](https://github.com/morphicOS/morphicOS-public/blob/main/tests/Tests_ModuleE_CHA_SYS.md) |
| **Uncertainty Injection** | Real-world unpredictability testing framework. | [https://github.com/morphicOS/morphicOS-public/blob/main/docs/UncertaintyInjection.md](https://github.com/morphicOS/morphicOS-public/blob/main/docs/UncertaintyInjection.md) |
| **Uncertainty Glossary** | Variables & definitions for uncertainty tests. | [https://github.com/morphicOS/morphicOS-public/blob/main/docs/UncertaintyInjection_GLOSSARY.md](https://github.com/morphicOS/morphicOS-public/blob/main/docs/UncertaintyInjection_GLOSSARY.md) |
| **Developer Testing Guide** | Step-by-step testing & telemetry commands. | [https://github.com/morphicOS/morphicOS-public/blob/main/tests/DEVELOPER_TESTING_GUIDE.md](https://github.com/morphicOS/morphicOS-public/blob/main/tests/DEVELOPER_TESTING_GUIDE.md) |
| **Appendix** | Exploratory edge tests & case studies. | [https://github.com/morphicOS/morphicOS-public/blob/main/docs/Appendix_Exploratory_Tests.md](https://github.com/morphicOS/morphicOS-public/blob/main/docs/Appendix_Exploratory_Tests.md) |
| **arXiv Workspace** | Papers, LaTeX sources, and preprints. | [https://github.com/morphicOS/morphicOS-public/tree/main/docs/arxiv](https://github.com/morphicOS/morphicOS-public/tree/main/docs/arxiv) |
| **Core Paper (WIP)** | MorphicOS core paper working directory. | [https://github.com/morphicOS/morphicOS-public/tree/main/docs/arxiv/MorphicOS_Core_Paper](https://github.com/morphicOS/morphicOS-public/tree/main/docs/arxiv/morphicOS-foundational-paper) |

---

## For Developers & Researchers

To explore or replicate MorphicOS behavior:  
1. Review the **Replication Guide** and **Test Template**.  
2. Activate developer mode in the public demo by typing: enable dev mode
3. Return to normal conversation mode by typing: user mode
4. Examine telemetry output using `[SCHEMA_Telemetry.json](https://github.com/morphicOS/morphicOS-public/blob/main/docs/SCHEMA_Telemetry.json)` as reference.  

Academic materials live under:  
📁 [https://github.com/morphicOS/morphicOS-public/tree/main/docs/arxiv](https://github.com/morphicOS/morphicOS-public/tree/main/docs/arxiv)

---

## Contact & Repository

**Author:** Edward Levin  
**Affiliation:** Independent Researcher  
**Repository:** https://github.com/morphicOS/morphicOS-public  
**LinkedIn:** https://www.linkedin.com/in/edward-levin-/  
**Email:** edward@maugos.com  

---

## License

Distributed under the **Morphic Public Ethics License (MPEL)**. See [https://github.com/morphicOS/morphicOS-public/blob/main/LICENSE.md](https://github.com/morphicOS/morphicOS-public/blob/main/LICENSE.md)

© 2025 Edward Levin. All rights reserved.

