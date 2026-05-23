---
title: "DGCOMP says"
date: 2026-05-23
draft: false
summary: "A bot watches the European Commission's competition vocabulary grow, one first-time word at a time."
---

A bot reads every published European Commission competition decision and flags any word the Commission has never used in a decision before. Mergers, antitrust, state aid, the Digital Markets Act, foreign subsidies.

The corpus goes back to 1990. Most words are repeats. A few are firsts.

Some are invented for the case. Some are misreads of scanned PDFs. Some are real words the Commission simply hadn't needed yet. Telling them apart is the texture, not the bug.

A handful: *[gatekeeper](https://competition-cases.ec.europa.eu/cases/M.890)* (1997), *[digitalisation](https://competition-cases.ec.europa.eu/cases/M.993)* (1998), *[ecosystem](https://competition-cases.ec.europa.eu/cases/M.4747)* (2008), *[machine-learning](https://competition-cases.ec.europa.eu/cases/SA.54806)* (2019), *[self-preferencing](https://competition-cases.ec.europa.eu/cases/M.10796)* (2023).

Every two hours the bot fetches the latest English decisions from the Commission's case portal, OCRs the scans, tokenises, and drops anything the corpus has seen before. What's left goes to a small model that decides if each survivor looks like a real word. What passes becomes an email.

The only newsletter you can't put on a calendar. Some weeks nothing. Some weeks two.

One word per email, no thread, no spam. Subscribe at [buttondown.com/dgcomp-first-said](https://buttondown.com/dgcomp-first-said).
