# David Tom

**Systems, Automation & Software**

[Portfolio](https://davidtomofficial.com/) · [Resume](https://davidtomofficial.com/resume/) · [david.tom@davidtomofficial.com](mailto:david.tom@davidtomofficial.com)

I build practical tools and document what I learn about systems, automation and software. My current focus is PowerShell for Windows observations, explicit uncertainty and reports that make evidence easier to review. Python supports the source packaging and validation work.

## Selected Work

These personal development previews share the [Windows-System-Administration repository](https://github.com/davidtomofficial/Windows-System-Administration). I keep their implemented scope, tests and remaining work alongside the source.

### Imaging & Provisioning

I'm developing tools to review workstation evidence before planning changes. The current preview collects selected workstation observations and bounded service and profile inventories, reviews local WIM metadata, optionally computes SHA-256 hashes, and produces an offline HTML report.

It also compares selected before/after workstation observations, preserving `Unknown` when evidence is incomplete. Profile age remains a review signal. Complete session coverage and removal eligibility are not established, and profile identifiers are omitted by default.

[Current source and scope](https://github.com/davidtomofficial/Windows-System-Administration/blob/main/Scripts/Imaging-Provisioning/README.md) · [Case study](https://davidtomofficial.com/windows-imaging-provisioning/#personal-development) · [Verified snapshot](https://github.com/davidtomofficial/Windows-System-Administration/blob/1284be142ce12f3ef6713f925b7a34df364b2478/Scripts/Imaging-Provisioning/README.md)

### DeviceCare

I'm building a compact way to review local OS, memory and system-drive observations. The preview evaluates memory and free-space thresholds, retains `Observed`, `Review` and `Unknown` findings, and creates an offline HTML report. Threshold findings support review; they do not certify overall device health.

[Current source and scope](https://github.com/davidtomofficial/Windows-System-Administration/blob/main/Scripts/DeviceCare/README.md) · [Case study](https://davidtomofficial.com/devicecare/) · [Verified snapshot](https://github.com/davidtomofficial/Windows-System-Administration/blob/1284be142ce12f3ef6713f925b7a34df364b2478/Scripts/DeviceCare/README.md)

## How I Work

I set the project scope and use AI-assisted development with source review, explicit test cases and recorded validation results. The linked verified snapshot passed [Windows Server 2022 CI](https://github.com/davidtomofficial/Windows-System-Administration/actions/runs/42286981032). I distinguish those checks from operational acceptance: attended Windows 11 testing and full native desktop workflows remain open.

These previews do not deploy images, repair devices or remove profiles. I document incomplete evidence and implementation limits so readers can assess what each increment actually demonstrates.

## Coursework & Early Projects

I retain [SQL](https://github.com/davidtomofficial/SQL), [C++ examples](https://github.com/davidtomofficial/cpp-Examples), [Python experiments](https://github.com/davidtomofficial/Python) and [web and app development](https://github.com/davidtomofficial/Web-App-Development) as historical learning work. Their compatibility with current environments has not been revalidated.

## Rights and Permission

The Windows previews are published for portfolio inspection. Covered original material requires explicit written permission unless an applicable existing license, separate written agreement or law permits the activity. See the [rights and permission notice](https://github.com/davidtomofficial/Windows-System-Administration/blob/main/LICENSE.md). Existing third-party and file-specific licenses remain applicable.
