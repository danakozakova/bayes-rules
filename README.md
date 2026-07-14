# Bayesovská analýza — riešenia z Bayes Rules! 🎲

> 🇬🇧 *Bayesian statistics coursework (Masaryk University), built around the book [Bayes Rules!](https://www.bayesrulesbook.com/) (Johnson, Ott & Dogucu): conjugate models (Beta-Binomial, Gamma-Poisson, Normal-Normal, Beta-Geometric), a hand-coded Metropolis-Hastings MCMC on my own data, and Bayesian regression with rstanarm. In R (bayesrules, rstanarm). Write-ups in Slovak/Czech.*

Riešenia úloh z predmetu Bayesiánska analýza (MPE_BAAN, Masarykova univerzita), postavené na knihe **[Bayes Rules!](https://www.bayesrulesbook.com/)** (Johnson, Ott & Dogucu). 
Zadania cvičení sú preložené — pri každom riešení je odkaz na príslušnú kapitolu knihy, ktorá je voľne dostupná online.

## [01 — Konjugované modely](01-conjugate-models/)

Sedem cvičení z kapitol 2–5: Bayesova veta a aktualizácia presvedčení, interpretácia a voľba apriórnych rozdelení, **Beta-Binomial**, **Gamma-Poisson** a **Normal-Normal** konjugované rodiny, sekvenčná aktualizácia posterioru a **Beta-Geometrický model** (odvodený mimo štandardných konjugovaných dvojíc knihy).

*Samostatná práca.*

## [02 — Metropolis-Hastings MCMC](02-metropolis-hastings-mcmc/)

**Vlastnoručná implementácia Metropolis-Hastingsovho algoritmu** (bez rstan) pre Beta-Binomial a Normal-Normal model — na vlastných dátach, nie učebnicových. Simulácia reťazca z rôznych štartovacích bodov, porovnanie s analytickým posteriorom, diagnostika konvergencie. Druhá časť: posteriórna inferencia a testovanie hypotéz (kapitola 8) — kredibilné intervaly, posteriórne pravdepodobnosti hypotéz.

*Samostatná práca.*

## [03 — Bayesovská regresia](03-bayesian-regression/)

Tímová úloha (skupina 13): **D. N., R. V., M. H.** a **Dana Kozáková**.

- **P1 — Jednoduchá normálna regresia** (tučniaky, cv. 9.16–9.20): apriórne modely, simulácia posterioru cez `rstanarm`, posteriórna predikcia - *moja práca*
- **P2 — Viacnásobná regresia s interakciami** (cv. 11.10–11.14)
- **P3 — Otvorená úloha: AirBnB** (cv. 12.10)
- **P4 — Otvorená úloha: bezpečnosť vakcín** (cv. 14.11, Naive Bayes klasifikácia)

> **Môj podiel:** celý **P1** (jednoduchá normálna regresia, tučniaky) vrátane samostatnej rozšírenej verzie s teoretickým výkladom kapitoly 9 (`chapter9_theory_notes.Rmd`). Pri P2–P4 príprava štruktúry dokumentov, kontrola a finalizácia; hlavnú analytickú prácu odviedli spolužiaci.

## Technológie

`R` · `bayesrules` · `rstanarm` · `tidyverse` · RMarkdown

## Referencia

Johnson, A. A., Ott, M. Q., & Dogucu, M. (2022). *Bayes Rules! An Introduction to Applied Bayesian Modeling.* CRC Press. Voľne dostupná na https://www.bayesrulesbook.com/

