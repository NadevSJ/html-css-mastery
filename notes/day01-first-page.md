First day in html-css-mastery
Date - 17/11/2026

The Topic - Your first HTML page

1. The commands I used today

   git add README.md
   git commit -m "docs: add README with my 41-day HTML and CSS plan"
   git add .gitignore
   git commit -m "chore: add .gitignore for node_modules and system files"
   git add days/day01-first-page/index.html
   git commit -m "feat(day01): add HTML skeleton for my first page"
   git add days/day01-first-page/index.html
   git commit -m "feat(day01): add heading, paragraphs and a comment"
   git add days/day01-first-page/about.html
   git commit -m "feat(day01): build about page typed without Emmet"
   git add days/day01-first-page/broken.html
   git commit -m "feat(day01): add broken page experiment with four mistakes"
   git add days/day01-first-page/nesting.html
   git commit -m "feat(day01): practise correct nesting with strong and em"
   git add challenges/day01-boilerplate.html
   git commit -m "feat(challenges): type the HTML boilerplate from memory"
   git add notes/day01-first-page.md
   git commit -m "docs(notes): add day 1 notes on first page"
   git add log.md
   git commit -m "docs(log): finish day 1 of 41"
   git push

2. The noticeable point/points I discovered from today's practice

   •Find the answer for - In 5 lines: what happens when you open a website?
   1. First, the browser acts as a client and sends a secure HTTPS request using the domain and path to a server.
      Second, the server responds with an HTML file, which the browser starts reading from top to bottom.
      Third, while parsing the HTML, the browser requests linked assets like CSS stylesheets, images, fonts, and scripts.
      Fourth, the browser combines the structure and styles into the DOM and layout tree.
      Fifth, it paints the finished page on screen and keeps updating when triggered.

   •Find the answer for - What is the difference between a tag and an element?
   2. A tag is just the markup label inside angle brackets—like <p> to open or </p> to close—whereas an element is the complete building block made up of the opening tag, the content inside it, and the closing tag (or just a single void tag for elements with no content).

   •Find the answer for - Why lowercase file names with no spaces?
   3. Lowercase names without spaces prevent broken links and path headaches across operating systems and web servers—especially since GitHub Pages is case-sensitive and treats uppercase and lowercase names as separate files, while spaces in URLs or shell commands easily cause escaping bugs.

   •Find the answer for - What did the browser do with each mistake in broken.html?
   4. Removing the closing </p> tag caused the browser to auto-close that paragraph when the next <p> began, leaving non-conforming markup even though the visible layout still looked separated.
      Changing the tag text without changing the actual tag name did not break behavior, showing how easy it is to overlook tiny typos if you skim code.
      Deleting <!doctype html> pushed the browser into quirks mode instead of standards mode, which risks older or inconsistent layout behavior.
      Moving <title> into <body> still set the browser tab text, while DevTools Elements showed it placed inside the body instead of the head.

   5. What still confuses me - Making sure I always close nested inline tags in exact reverse order on the first try without crossing them over, and remembering when to use semantic tags versus styling later in CSS.
      What I will practise tomorrow - Mentor HTML lessons 01–05 and Activity 1 in html-css-mastery, typing code by hand first and checking everything in Live Server and DevTools.
