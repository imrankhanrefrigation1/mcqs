# Study MCQs Practice System

A responsive, self-paced English grammar quiz based on the uploaded 32-page scanned grammar workbook PDF. It contains 75 MCQs, one mark per correct answer, no negative marking, progress tracking, question navigation, results, filters, and answer review.

## Run on Windows
1. Extract `study-mcqs-practice.zip`.
2. Open the extracted `study-mcqs-practice` folder.
3. Double-click `index.html` to open it in a modern browser (Chrome, Edge, or Firefox).
4. Press **Start Test**, answer questions, then press **Submit Test**.

No server, account, paid API, or installation is required. An internet connection is only used for the optional Google Fonts import; the quiz itself works without it.

## Files
- `index.html`: page structure
- `css/style.css`: responsive design
- `js/questions.js`: 75-question bank, answer key, explanations, topic and approximate PDF page reference
- `js/app.js`: quiz logic, navigation, scoring and review
- `SOURCE_NOTES.md`: source and OCR limitations

## Customize
Edit `js/questions.js`. Each question has `id`, `topic`, `sourcePage`, `question`, `options` (four strings), `answer` (zero-based option index 0–3), and `explanation`. Keep the `answer` index aligned with the option list.
