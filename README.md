# Data Governance Framework for Digital Social Protection Systems

This repository contains the source files for the **Data Governance Framework for Digital Social Protection Systems**, a DCI/USP2030 publication. The content is published as a GitBook site and maintained here via GitBook's Git Sync.

## About the framework

The framework provides practical guidance for governments, development partners, and practitioners on governing data in digital social protection systems. It is organised around four pillars — Management, Quality, Access, and Security — each broken into building blocks and implementation mechanisms.

## Repository structure

This is a monorepo. Each folder corresponds to a separate GitBook Space, synced individually via GitBook's Git Sync settings.

```
start-implement/   "Start here" and 5-step implementation cycle
pillars/           Four pillar reference spaces (building blocks, RACI, mechanisms)
toolkit/           Implementation mechanisms library (templates, checklists, SOPs)
cases/             Country case studies (Uganda, Philippines, Türkiye, Chile)
print/             Print/PDF edition (linear narrative, assembled from core content)

shared/            Reusable content blocks (citation, disclaimer, acronyms)
assets/            Shared images and figures
scripts/           Optional automation scripts
```

## GitBook sync configuration

Each space is configured individually in the GitBook UI to sync with its folder:

| GitBook Space        | Folder            |
|----------------------|-------------------|
| Start & Implement    | `start-implement/` |
| Pillars (Reference)  | `pillars/`         |
| Toolkit              | `toolkit/`         |
| Country Cases        | `cases/`           |
| Print Edition        | `print/`           |

Each space folder contains a `README.md` (space landing page) and `SUMMARY.md` (table of contents).

## Publication details

- **Version:** v1.0 (draft)
- **Status:** Not yet an official DCI publication
- **Maintainer:** Tim Ohlenburg
- **Feedback:** [open an issue](../../issues)

## How to cite

See [shared/how-to-cite.md](shared/how-to-cite.md).

## Licence

To be confirmed.
