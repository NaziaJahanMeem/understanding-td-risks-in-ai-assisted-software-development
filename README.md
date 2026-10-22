# Replication Package: Understanding Technical-Debt Risks in AI-Assisted Software Development: A Practitioner Study

This repository contains the replication package for the paper:

> **Understanding Technical-Debt Risks in AI-Assisted Software Development: A Practitioner Study**
>
> Nazia Jahan, Nafisa Alam, Sourov Debnath, Md Farhad Alam Bhuiyan,Mia Mohammad Imran
>
> ICSE 2027

We conduct a sequential mixed-methods study of how software professionals in Bangladesh perceive technical-debt risks in AI-assisted development. The study combines an online survey (137 valid responses) with 20 follow-up semi-structured interviews.

## Repository Structure

```
.
├── README.md
├── instruments/
│   ├── survey_questions.pdf
│   └── interview_questions.pdf
├── data/
│   ├── survey_responses.csv
│   └── interview_transcripts/
│       ├── P1.txt
│       ├── P2.txt
│       └── ...
└── annotation/
    └── annotation_guidelines.pdf
```

## Contents

### `instruments/`

- **survey_questions.pdf** contains the 35 survey questions in their original order, with answer options. Question IDs (Q1–Q35) match the column names in `survey_responses.csv` and the question numbers in the paper.
- **interview_questions.pdf** contains the interview questions. Question IDs (I-Q1, I-Q2, ...) match the question numbers in the paper.

### `data/`

- **survey_responses.csv** contains one row per valid respondent. Respondent IDs (S1–S137) match the IDs in the paper.
- **interview_transcripts/** contains one file per participant, named with the participant IDs from the paper (`P1` to `P20`).

### `annotation/`

- **annotation_guidelines.pdf** describes how we code the open-ended survey responses.
