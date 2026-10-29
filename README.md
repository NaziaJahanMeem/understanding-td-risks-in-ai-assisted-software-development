# Replication Package: Technical Debt Risks in AI-Assisted Software Development: Insights from Practitioners

This repository contains the replication package for our study of technical debt risks in AI-assisted software development. The study combines an online survey of 137 software professionals in Bangladesh with 20 follow-up semi-structured interviews.

## Repository Structure

```
.
├── analysis/
│   ├── interview_counts.xlsx
│   └── survey_coded_responses.xlsx
├── annotation/
│   ├── interview_annotation_guidelines.pdf
│   └── survey_annotation_guidelines.pdf
├── data/
│   ├── interview_transcripts.pdf
│   └── survey_responses.csv
├── instruments/
│   ├── interview_questions.pdf
│   └── survey_questions.pdf
└── README.md
```

## Contents

### `instruments/`

- **`survey_questions.pdf`:** The full survey questionnaire.
- **`interview_questions.pdf`:** The semi-structured interview protocol with 8 core questions (I-Q1–I-Q8) and their follow-up questions.

### `data/`

- **`survey_responses.csv`:** 137 anonymized survey responses. Each row is one respondent, and rows correspond to S1–S137 in order. Each column corresponds to one survey question. Multi-select answers are separated by commas.
- **`interview_transcripts.pdf`:** Anonymized English transcripts of the 20 interviews.

### `annotation/`

- **`survey_annotation_guidelines.pdf`:** How we coded the open-ended survey responses (Q33–Q35).
- **`interview_annotation_guidelines.pdf`:** How we prepared the transcripts and counted the participants who mentioned each finding.

### `analysis/`

- **`survey_coded_responses.xlsx`:** The coded responses to the open-ended questions Q33–Q35. Each row lists the question, the respondent (S1–S137), their answer exactly as submitted, and the themes assigned to it. Responses without themes (e.g., "N/A") were not coded.
- **`interview_counts.xlsx`:** One row per interview finding reported in the paper, with the research question, the finding, the count (with percentage), and the participants who mentioned it together with the interview question(s) where they did so.

## Anonymization

We removed names, email addresses, company names, and other identifying details from all survey responses and interview transcripts. Survey respondents are identified as S1–S137 and interview participants as P1–P20.
