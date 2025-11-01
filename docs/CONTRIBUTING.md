🤝 Contributing to MorphicOS

Version 1.0 — Public Developer Guide
© 2025 Morphic Framework

Welcome

Thank you for your interest in contributing to MorphicOS — the Ethical Sovereignty Build.
Your participation helps refine a framework built on transparency, reversibility, and shared responsibility.

This guide explains how to propose, build, and publish new MorphicOS tests and documents while protecting both intellectual property and ethical integrity.

1️⃣ Code of Conduct

All contributors must follow the MorphicOS Code of Ethics
.

By contributing, you agree to:

Act with honesty, respect, and empathy.

Never design or release harmful, deceptive, or coercive behavior tests.

Ensure that all reasoning remains reversible and explainable.

Avoid any use of MorphicOS materials that could endanger people, animals, or ecosystems.

Contributors who violate these principles may have access revoked and their contributions removed.

2️⃣ What You Can Contribute

You are welcome to contribute to any of the following areas:

Contribution Type	Description	Example
Behavioral Tests	New test cases based on real-world ambiguity or ethical stress scenarios.	
SPIL-EXT-4: Compassion Under Sarcasm
Telemetry Extensions:	New metrics or interpretations of developer telemetry data.	Add field stability_gradient to JSON schema.
Documentation	Clarifications, examples, or educational content for /docs/.	“Understanding the NMA Translation Mode”
Ethical Studies	Exploratory reports, comparative analyses, or applied ethics reflections.	“Evaluating Reversibility in Multi-Agent Systems”
Tooling	Scripts, dashboards, or open adapters for test replication.	Python dashboard for test telemetry review.
3️⃣ Repository Workflow
🔹 Step 1: Fork the Repository

Clone or fork the official public repo:

git clone https://github.com/morphicOS/morphicOS-public

🔹 Step 2: Create a Branch

Use descriptive branch names:

feature/new-test-NMA-EXT1
fix/docs-typo
update/telemetry-schema

🔹 Step 3: Add Your Contribution

Place your additions under the appropriate directory:

Directory	Purpose
/docs/tests/	New or extended test modules
/docs/community/	User-contributed exploratory tests
/docs/tools/	Utilities for test analysis
/docs/ethics/	Papers, essays, or discussions on Morphic ethics

Each test should follow the TestTemplate.md
 structure and include telemetry fields and pass/fail criteria.

🔹 Step 4: Include Metadata Header

At the top of your file, include:

author: [GitHub handle]
version_tested: v1.7.4
module: [WIN | SPIL | NMA | REV | SOV | CHA | SYS]
ethical_review: pending
replication_status: reproducible
date_submitted: YYYY-MM-DD

🔹 Step 5: Ethical Review Pre-Check

Before submitting a Pull Request (PR), run the internal pre-check list:

✅ No irreversible actions in any test
✅ ethical_state = SAFE in all telemetry samples
✅ No external data scraping or unverified simulations
✅ Proper attribution for reused text or datasets
✅ Includes at least one uncertainty or ambiguity factor

4️⃣ Submitting a Pull Request

Push your branch to your fork.

Open a Pull Request to the main branch of morphicOS/morphicOS-public

Add the label:

ethics-reviewed


Include a short description of your contribution and the uncertainty factor being tested.

The maintainers will review PRs for technical validity, ethical soundness, and telemetry consistency.

5️⃣ Review & Approval Process
Stage	Reviewer	Criteria
Automated Ethics Scan	ECEK Validation Bot	Confirms telemetry safety (ethical_state = SAFE)
Human Review	MorphicOS Ethics Team	Checks for bias, coercion, or unsafe implications
Integration Review	Maintainers	Ensures structural compliance with suite
Approval	Project Lead	Merges and updates index files

Average turnaround: 3–5 days for standard tests, 7–10 days for complex or ethical scenarios.

6️⃣ Communication Channels

Issues: Use GitHub Issues for bugs, proposals, or feature discussions.

Discussions: Join the public Ethical Reasoning board for debate or collaboration.

Ethics Board Contact: edward@maugos.com

7️⃣ Style Guidelines

Use plain English and avoid excessive jargon.

Prefer ethical reasoning over technical speculation.

Write examples with human realism — tone, ambiguity, context.

Keep telemetry JSON blocks consistent and properly formatted.

Include at least one line showing MorphicOS’s expected ethical voice.

8️⃣ Attribution

All accepted contributions will be listed in the official credits file:

/docs/community/CONTRIBUTORS.md


Attribution follows the format:

Contributor: [Name or Handle] — Test(s): [ID(s)] — Date: [YYYY-MM-DD]

9️⃣ License Reminder

All contributions are automatically covered by the
MorphicOS Public Ethics License (MPEL)
.

By submitting a PR, you affirm that you:

Understand the license conditions.

Have created your contribution ethically and lawfully.

Do not claim ownership of MorphicOS core components.

🔟 Thank You

Every contributor helps shape the world’s first framework that treats ethics as infrastructure.
Your care, creativity, and caution are the foundation of MorphicOS.

“Transparency is not weakness — it’s architecture.”

Contact

Project Maintainers
📧 edward@maugos.com

🌐 maugos.com
 | vm4ai.com