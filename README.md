# PP-1 MCQ Practice

305 MCQs for BCA Sem 1, C05BC3103 Programming Practices-1 (Unit 1: Introduction to Programming, Unit 2: Fundamentals of C).

- **Practice mode**: shows right or wrong as soon as you pick an answer. Filter by unit or topic.
- **Mock test**: 20 random questions, like the mid-sem exam, with a score and review at the end.
- Works on mobile. Keyboard: A–D to answer, ← → to move.

It is a single `index.html` file with no build step. Open it in a browser, or deploy it on GitHub Pages.

## Deploy on GitHub Pages

1. Create a new public repository on GitHub, for example `pp1-mcq-practice`.
2. Push this folder:

   ```bash
   git init
   git add .
   git commit -m "Add PP-1 MCQ practice page"
   git branch -M main
   git remote add origin https://github.com/<your-username>/pp1-mcq-practice.git
   git push -u origin main
   ```

3. On GitHub, open **Settings → Pages**. Under **Build and deployment**, pick **Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. After 1–2 minutes the site is live at `https://<your-username>.github.io/pp1-mcq-practice/`.
