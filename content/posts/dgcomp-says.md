---
title: "DGCOMP says"
date: 2026-05-23
draft: false
summary: "A bot watches the European Commission's competition vocabulary grow, one first-time word at a time."
---

A bot reads every English-language European Commission competition decision and flags any word the Commission has never used in a decision before. Mergers, antitrust, state aid, the Digital Markets Act, foreign subsidies.

The corpus goes back to 1990. Most words are repeats. A few are firsts.

Some are invented for the case. Some are misreads of scanned PDFs. Some are real words the Commission simply hadn't needed yet. Telling them apart is the texture, not the bug.

A handful: *[gatekeeper](https://competition-cases.ec.europa.eu/cases/M.890)* (1997), *[digitalisation](https://competition-cases.ec.europa.eu/cases/M.993)* (1998), *[ecosystem](https://competition-cases.ec.europa.eu/cases/M.4747)* (2008), *[machine-learning](https://competition-cases.ec.europa.eu/cases/SA.54806)* (2019), *[self-preferencing](https://competition-cases.ec.europa.eu/cases/M.10796)* (2023).

The bot reads every new decision the Commission publishes and splits each one into words. Fragments, all-caps acronyms, and names that are always capitalised get thrown out. Anything used in an earlier decision is skipped.

A small AI checks the survivors and decides if they look like real words. What's left becomes an email.

The only newsletter you can't put on a calendar. Some weeks nothing. Some weeks two.

Inspired by [@nyt_first_said](https://twitter.com/nyt_first_said). [Max Bittker drew its plumbing](https://maxbittker.github.io/clear-pipes/).

Subscribe at [buttondown.com/dgcomp-first-said](https://buttondown.com/dgcomp-first-said).
