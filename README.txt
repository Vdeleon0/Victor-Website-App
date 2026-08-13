VICTOR'S WEBSITE — WHAT YOU STILL NEED TO ADD
================================================

1. professional/images/headshot.jpg
   -> A photo of you for the hero section on the professional homepage.

2. scratch/images/soccer.jpg
   -> A soccer/action photo of your choice for the "Why Soccer" section.
   I deliberately did NOT hotlink a random internet image here, since
   the assignment penalizes broken images, and I can't guarantee a
   third-party link stays live. Drop any photo you like into that folder.

HOW TO TEST LOCALLY
--------------------
Open professional/index.html directly in your browser. Click through to
the scratch page and the mini-game. The YouTube video and Tableau viz
will render as soon as you have internet access (they pull live content).

HOSTING ON GITHUB PAGES
------------------------
1. Create a new GitHub repo, push this whole "site" folder's contents
   to it (professional/, scratch/, and this README can be deleted).
2. In the repo settings -> Pages -> set source to your main branch, root.
3. Your professional homepage: https://yourusername.github.io/reponame/professional/
   Your scratch page: https://yourusername.github.io/reponame/scratch/

WHAT'S ALREADY DONE
---------------------
Professional site (Bootstrap 5, professional/index.html):
- Navbar, hero, about, experience (incl. your new BYU IT role), projects,
  skills, and contact sections
- Résumé content built directly in HTML (not a PDF)
- No social icon links included (per your prompt, these must not be
  broken — add your own real LinkedIn/GitHub links if you want them)

From-scratch page (scratch/index.html, scratch/styles.css):
- Ordered list (5 training skills) with a nested unordered list inside
  each item
- Image placeholder (soccer.jpg — add your own)
- Live embedded YouTube video
- On-page anchor (jump to top link)
- Custom background color + a subtle pitch-line background pattern
- Custom stylesheet with well over 4 style definitions, explicit font-family
  and color declarations, and 3 positioning divs (hero, content wrap, footer)
- Live, interactive embedded Tableau Public dashboard (World Cup match data)
- Nav link back to the professional site

Web app (scratch/app.html):
- Single-page Penalty Shootout game built in one file (HTML/CSS/JS together)
- Click a corner, the goalkeeper "guesses" randomly, animated ball + keeper
  movement, 5-round scoreboard, win/lose messaging, replay button
- Linked from the scratch page
