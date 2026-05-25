---
title: "Remote Work and the Restructuring of the Firm: Evidence from Collective Agreements"
collection: publications
category: manuscripts
permalink: /publication/2026-remote-work-firm-restructuring
excerpt: 'We study how the formal adoption of remote work reorganizes the cost structure of the firm, using the universe of French collective agreements matched to administrative balance sheets over 2018–2025.'
date: 2026-03-01
venue: 'Working Paper, LEMMA, Université Paris-Panthéon-Assas'
paperurl: 'http://andrewspp.github.io/files/andrews-2026-remote-work.pdf'
citation: 'Andrews, P. (2026). &quot;Remote Work and the Restructuring of the Firm: Evidence from Collective Agreements.&quot; Working Paper, LEMMA, Université Paris-Panthéon-Assas.'
---

## Abstract

We study how the formal adoption of remote work reorganizes the cost structure of the firm, using the universe of French collective agreements matched to administrative balance sheets over 2018–2025. A fine-tuned large language model classifies 400,000 agreements and extracts adoption timing and intensity for 20,000 firms in a staggered difference-in-differences design.

Treated firms reduce their stock of office equipment and fittings by **22 percent** at *t*+5 while sustaining production unchanged; in parallel, the wage bill falls through headcount reduction while average compensation per worker remains stable. Both adjustments unfold along the same contractual clock: France's triennial *baux 3-6-9* lease regime, and are absent among firms that formalized under COVID-19 emergency compulsion.

Total factor productivity rises by **3.8 percent** after five years, mechanically, because the same output is sustained with less capital. One to two days per week is the rationalization-maximizing intensity range; above three authorized days, coordination costs erode output and offset the real estate gain.

## Key Findings

- **Two-margin restructuring**: office capital −22% at *t*+5, headcount reduction, stable output
- **Lease clock mechanism**: adjustments governed by France's triennial *baux 3-6-9* regime
- **Intensity trade-off**: TFP gains peak at 2 days/week (+3.2 pp); full remote work generates significant TFP losses (−6.8 pp)
- **Size heterogeneity**: large firms achieve output-neutral capital shedding (+4.9 pp TFP); SMEs and mid-sized firms show weaker or negative profiles
- **LLM classification**: fine-tuned model achieves 98% sensitivity / 97% specificity on 400,000 legal documents

## Data & Methods

- **Data**: ACCO-DTD Légifrance collective agreements + INPI administrative balance sheets, 2018–2025
- **Classification**: LoRA fine-tuned large language model (20B parameters)
- **Identification**: Staggered DiD with cohort-robust estimators (Sun & Abraham 2021; Callaway & Sant'Anna 2021)
- **Sample**: ~20,000 firms, ~105,000 firm-year observations