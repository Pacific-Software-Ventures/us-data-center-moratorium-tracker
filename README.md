# US Data Center Moratorium Tracker

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24325737.svg)](https://doi.org/10.5281/zenodo.24325737)

Snapshot 2026-11-11. Archived on Zenodo: https://doi.org/10.5281/zenodo.24325737

Publisher: Pacific Software Ventures (PSV), San Diego, CA.
Live version: https://pacificsoftwareventures.com/data-center-moratorium-tracker
License: CC BY 4.0. Credit "Pacific Software Ventures, US Data Center Moratorium Tracker".

## What it is

State and local actions that pause, restrict or condition new data center development in the United States: moratoriums, permit pauses, executive orders, and large-load power rules. Each row cites a primary source (the order, ordinance, filing or docket) where one is public.

This file is the snapshot published on the live page on November 11, 2026. The live page is updated as new actions are reported; later snapshots will be uploaded as new versions of this record.

## File

`data.csv`, UTF-8, comma-separated, one header row.

| Column | Meaning |
|---|---|
| type | `action` (31 rows: a moratorium, pause, order or rule) or `project` (15 rows: a large data center project, lease or site the tracker follows, with its size and money) |
| where_or_project | Jurisdiction (state, county, city) or project name |
| detail | What the action does, in one or two sentences |
| trigger_or_size | What it applies to (for example a megawatt threshold) |
| until_or_money | End date or duration, or the money involved |
| status_or_parties | Status (for example In effect, Proposed, Vetoed) or the parties involved |
| date | Date of the action (YYYY-MM-DD or YYYY-MM) |
| latest_update | Short note on the most recent development, if any (free text) |
| primary_source | URL of the primary document |
| psv_story | URL of the PSV newsroom story that covers it, if any |

## Method

Most rows come from a story in the Pacific Software Ventures newsroom that reads the underlying order, filing, docket or ordinance; the source link goes to that document where it is public. See "How we built this tracker" on the live page for scope and limits.

## Conflict of interest

PSV made this dataset. PSV sells AI consulting and engineering to commercial real estate firms. No outside funding.

## Cite

Pacific Software Ventures (2026). US Data Center Moratorium Tracker (snapshot 2026-11-11) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24325737
