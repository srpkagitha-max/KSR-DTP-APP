KSR DTP Question Paper Maker v2.1.5

Context-aware parser update:
- Matching-list sub-items a) b) c) under List-I / జాబితా-I stay inside the question stem.
- Correct-answer markers before options (•B, ●C, etc.) are detected correctly.
- Printed options remain normalized in A/B/C/D order.
- Numeric options with leading answer marks are supported.
- Source-number regressions/duplicates are shown as warnings before print while generated numbering remains continuous.
- Existing clean two-column A4 layout, first-page-only header, page numbering, answer brackets and PWA support are retained.

Changes in v2.1.5:
- Recognizes App Psychology / App Pie / App method / App Social and similar short App section labels as headings, so they never enter the previous question.
- Detects red-circle and additional emoji answer markers used in Telugu banks.
- Treats a source-number reset to 1 as an implicit new section, avoiding false numbering-break warnings when a subject heading is omitted.

V2.1.5 FIX
- Subject/App headings no longer use column-span:all. This prevents a heading from being visually inserted between the previous question stem and its A/B/C/D options during two-column PDF layout.
- Headings stay in normal two-column flow and remain attached to the next question.
- Service-worker cache bumped so installed PWA receives the corrected layout.
