# Raw source material (not used by the app)

These files are reference/source material, not fetched by the app.

- `txt/` — raw exam text extracted from past model exams and study sheets.
- `images/` — scans of exam-model pages and related images.
- `pdf/` — prep book, oral-exam questions, QCM correction, and a 400-fact study sheet.
- `app1_policemaroc_data2_draft_366_UNVERIFIED.json` — 366 QCM questions extracted
  from the files above, in the same schema as `app1_policemaroc_data1.json`, but
  **every `answer` field is empty**. Do not use this for grading as-is.

## Verified content

`app1_policemaroc_data2.json` (repo root) contains 49 questions from
`نموذج-مباراة-حراس-الأمن-2022.txt`, with answers verified against
`raw-source/pdf/تصحيح-امتحان-qcm-حراس-الأمن-2022.pdf`. This is the only subset of
the draft that has been checked question-by-question and is safe to ship.

The remaining ~300 questions in the draft (2025 model exams, مفتشي الشرطة x4,
ضباط الشرطة الخارجية, استبيان حراس الأمن, and the French set) have no matching
answer key in this repo. Do not fill in answers for them without a verified
source — this is exam-prep content for a real government recruitment test.
