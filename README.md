<a id="readme-top"></a>
<div align="center">

<h1>Brand Guardian License</h1>

<p>Source-available family with readable names: reserve branding, ban store-clone spam, optionally reserve Competing Use and Incorporation — without requiring anyone to memorize DevCentr letter codes.</p>

<p>
  <a href="https://github.com/dev-centr/brand-guardian-license"><img src="https://img.shields.io/badge/steward-Dev--Centr-teal?style=for-the-badge" alt="Stewarded by Dev-Centr"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/default-BGL%201.0%20Standard-informational?style=for-the-badge" alt="Default: Brand Guardian License 1.0 Standard"></a>
</p>

<p><strong><a href="docs/how-to-adopt.adoc">How to apply this license »</a></strong></p>

</div>

## What this is

The **Brand Guardian License** is a small family of source-available texts you can put in your own `LICENSE` file. Dev-Centr **stewards** the texts in this repo. The texts themselves do not mention DevCentr products, Centr Source License, or “CSL”. Adopt them without learning our house abbreviations.

This is **not** OSI Open Source. Bundles stay source-available; branding stays reserved; clone-spam and ad-stuffed reuploads are **Prohibited Distribution** with copyright remedies (where enforceable).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Choose a tier

Use the **full name** in README, package metadata, and headers. Short identifiers exist only as filename/grep hints (they are **not** SPDX IDs).

| Apply as (readable name) | File | What it reserves |
| --- | --- | --- |
| **Brand Guardian License 1.0 Standard** | [Brand-Guardian-License-1.0-Standard.txt](Brand-Guardian-License-1.0-Standard.txt) (also [LICENSE](LICENSE)) | Default tier. Branding + Prohibited Distribution. Incorporation and Competing Use **allowed**. Good for libraries, plugins, and apps that want wide reuse without official-mark impersonation or store junk. |
| **Brand Guardian License 1.0 — No Competing Use** | [Brand-Guardian-License-1.0-No-Competing-Use.txt](Brand-Guardian-License-1.0-No-Competing-Use.txt) | Above, plus no substitute/near-identical product or business without written permission. Incorporation still allowed. |
| **Brand Guardian License 1.0 — No Competing Use, No Incorporation** | [Brand-Guardian-License-1.0-No-Competing-Use-No-Incorporation.txt](Brand-Guardian-License-1.0-No-Competing-Use-No-Incorporation.txt) | Strictest: no competing substitute, and you may not bundle the software into your own product (ordinary plugins and OS/runtime images still OK). |

Steward mapping from the older Centr Source License letter codes (DevCentr-only history — adopters can ignore this): [docs/csl-mapping.adoc](docs/csl-mapping.adoc).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Apply it in 30 seconds

1. Copy **one complete file** above into your project’s `LICENSE` (verbatim). GitHub then shows **Other**; that is expected.
2. Name the license in README using the **readable title**, not a letter salad.
3. Designate **Branding** (name, logo, splash) in a copyright notice or `brand/LICENSE`. Marks are not granted by this instrument.
4. Optional: a one-line comment at the top of `LICENSE` with this canonical URL so humans find later versions.

Do **not** dual-license the same files as OSI MPL/MIT **plus** this instrument. Extra copyright restrictions on MPL Covered Software are not MPL. Pick one copyright grant, or keep OSI on code and handle store clones as **trademark** (the PolyglotScan pattern).

Details: [docs/how-to-adopt.adoc](docs/how-to-adopt.adoc).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## GitHub’s license dropdown and SPDX

You cannot submit a custom license into GitHub’s **Create repository → Add a license** list by URL. That menu is [choosealicense.com](https://choosealicense.com/), which only catalogs OSI / FSF-free / Open Definition licenses that already have an SPDX id, **≥1000** public repos, and three notable `LICENSE` examples.

Brand Guardian License is **not** OSI. It will not appear in that dropdown until (and unless) it meets bar none of us should fake: SPDX listing **and** real adoption **and** OSI-or-FSF-or-OD status. Honest path:

| Channel | What to do now | When to submit |
| --- | --- | --- |
| **Your repos** | Paste the full text as `LICENSE`. GitHub [Licensee](https://github.com/licensee/licensee) reports **Other**. | Immediate. |
| **This repo as a template** | GitHub → Settings → **Template repository**. New repos copy the texts. | Immediate, after first push. |
| **SPDX** | Do **not** invent `SPDX-License-Identifier: BGL-1.0-Standard` until SPDX accepts it. | After identifiable, frozen text + substantial use (or a plan in significant projects). Issue process: [spdx/license-list-XML](https://github.com/spdx/license-list-XML/blob/main/DOCS/request-new-license.md). Inclusion is not automatic for source-available licenses; they can still be listed if generally usable, stable, and actually encountered. |
| **choosealicense.com / GitHub dropdown** | Do not open a PR yet. | Only after SPDX **and** OSI/FSF/OD listing **and** 1000 public uses. Unlikely for a non-OSI instrument; do not rely on it. |

Full notes: [docs/publishing.adoc](docs/publishing.adoc).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Copying vs modifying the instrument

You may copy these texts **verbatim** to apply them. If you change the bargain, **rename** it and drop “Brand Guardian License” / “BGL” (MPL 2.0 §10.3 idea). See [NOTICE](NOTICE).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License of this repository

The default instrument in [LICENSE](LICENSE) is Brand Guardian License 1.0 Standard (the text we steward). Documentation in `docs/` may be quoted with attribution. Changelog: [CHANGELOG.adoc](CHANGELOG.adoc).
