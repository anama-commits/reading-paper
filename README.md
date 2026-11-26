# The Reading Paper · tester boxes

A weekly "box" of reading picks, one per tester. Each tester opens their own box from a personal link (`?r=<code>`). Boxes come in English or Romanian, depending on the form the tester signed up with.

- `index.html`, `app.js`: the box page, built from the "D · The box" design canvas.
- `data.js`: picks, shelves, boxes per code, and English/Romanian text. No names or emails are stored here.
- Ratings, "want to read", link clicks, item opens and peeks at other shelves are sent to a private Google Sheet once `endpoint` in `data.js` is set.
