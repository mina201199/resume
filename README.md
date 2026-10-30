# Mina Li — AI Application & Software Engineering Portfolio

Personal portfolio site for Mina Li (李奕儒), targeting AI application and software engineering roles.
The site is written in Traditional Chinese and published with GitHub Pages from the `main` branch.

Live site: <https://mina201199.github.io/resume/>

## Featured projects

1. **PredictFix AI** — smart maintenance assistant (solo project, local MVP): local Gemma with
   manual and case RAG, qualification-based dispatch, supervisor approval, and verified close-out
   in one traceable workflow; 161 automated tests and 45/45 AI/API security checks.
   [Source](https://github.com/mina201199/predictfix-ai-factory) ·
   [Demo and walkthrough video](https://predictfix-mobile-demo.ruru0109lee.chatgpt.site) ·
   [Validation record](https://github.com/mina201199/predictfix-ai-factory/blob/main/docs/release-validation-20261020.md)
2. **PowerQuery TW** — Text2SQL over Taipower open data with SQL and semantic guards; unknown
   questions are refused or clarified, and OpenAI is optional. Evaluated on a fixed offline
   benchmark. Team project forked from
   [lee851104/text2sql_project](https://github.com/lee851104/text2sql_project).
   [Source](https://github.com/mina201199/text2sql_project) ·
   [Offline evaluation report](https://github.com/mina201199/text2sql_project/blob/main/reports/eval_latest.json)
3. **Labor-rights RAG** — Q&A over official Taiwanese labor sources using BM25 + vector hybrid
   retrieval with RRF, citation-ID checks, and refusal when the evidence is insufficient.
   Private repository; demo available on request.
4. **Life House** — 3-person team project (Top 10 of 160 teams at a hackathon) mapping
   walking-distance risk from 230k Taoyuan accident records, with my continued development:
   location A/B comparison, share links, favorites, and Playwright E2E.
   [Source](https://github.com/mina201199/life_house) ·
   [My contribution (PR #3)](https://github.com/lee851104/life_house/pull/3) ·
   [Map demo](https://p215-2203-nb01.tail177cc6.ts.net) (open daily 08:00–20:00 Taipei time)

The site also covers professional training (AI LLM Engineer Program, 486 hours, III), skills,
work experience, education, and contact details, and links the PDF résumé:
<https://mina201199.github.io/resume/mina-lee-resume.pdf>.

## Editing

The site is a single static `index.html` with inline CSS and a small script for the interactive
flow demo; there is no build step. Changes go live after they are pushed to `main`.
