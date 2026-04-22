# praccticeIF

https://rhoded-uwp.github.io/practice_if_else/

practice_if_else
 
A simple in-browser widget for practicing Python `if` / `elif` / `else` logic. Built for students in CS 1430 at UW-Platteville, but free for anyone to use, fork, remix, or learn from.
 
**Live widget:** https://rhoded-uwp.github.io/practice_if_else/
 
## What this is
 
A single HTML file that runs entirely in your browser. No install, no login, no server. You open the page, you practice, you close the tab. That is the whole thing.
 
It is designed to be embedded in Canvas as an iframe, but it works just as well as a standalone page.
 
## How to use it
 
Just click the link above and start practicing. If you are an instructor who wants to embed it in Canvas or another LMS, the URL works inside an iframe.
 
## How to run it locally
 
If you want to poke at the code on your own computer:
 
1. Clone or download this repo.
2. Open `index.html` by double-clicking it, or drag it into a browser window.
That is it. No `npm install`, no build step, no dependencies to fight with. One file, one browser, done.
 
If you are using VS Code, the Live Server extension is a nice upgrade because it auto-refreshes the page every time you save a change.
 
## How this widget was built
 
This project was built as part of a series of small educational tools for intro CS courses. The process looked roughly like this:
 
1. **Identify the skill gap.** Students were struggling with branching logic, so the goal was a low-stakes practice environment where they could try a lot of problems quickly.
2. **Sketch the requirements.** What should a question look like? What feedback should students get? What counts as a win?
3. **Generate the first draft with AI assistance.** See the disclosure section below.
4. **Test, revise, test again.** Run it in the browser, find the rough edges, fix them, repeat.
5. **Deploy to GitHub Pages.** Push to `main`, enable Pages in Settings, wait a minute, and the widget is live on the web.
Nothing here is magic. If you read the source of `index.html`, you will see plain HTML, CSS, and JavaScript that you could have written yourself once you learn those tools. That is part of the point.
 
## Full disclosure: Claude's role
 
This widget was co-developed with Claude, an AI assistant made by Anthropic. I want to be transparent about how AI was used because I ask the same transparency of my students.
 
**What Claude did:**
 
- Generated the initial HTML, CSS, and JavaScript based on my written specifications.
- Suggested improvements to the question-generation logic and feedback wording.
- Helped debug issues when something did not behave as expected.
**What I did:**
 
- Defined the learning objective and the user experience I wanted.
- Reviewed every line of code before it went into the repo.
- Tested the widget in a real browser and iterated on it.
- Made the final call on what shipped and what did not.
- Wrote this README.
**What this means for you as a student:** AI is a real tool in modern software work, and pretending otherwise would not help anyone. But the human still has to understand the code, test it, and take responsibility for it. If I merged code I did not understand, any bug would be my problem, not Claude's. The same standard applies to you in your coursework. Use the tools your instructor allows, be honest about using them, and make sure you actually understand what you are turning in.
 
## License
 
This project is released under the MIT License (see `LICENSE` file if present, or assume MIT if not). In plain English:
 
- You can use it.
- You can copy it.
- You can modify it.
- You can use it in your own projects, including for a grade or for money.
- You do not owe me anything, though a mention is always nice.
- There is no warranty. If it breaks your computer (it will not, it is just a web page), that is not my problem.
**Copying is encouraged.** If you are a student who wants to build something similar for your own learning, fork this repo and start hacking on it.
 
## How to fork and contribute
 
If you are new to GitHub, here is the short version:
 
1. Click the **Fork** button at the top right of this repo page.
2. That gives you your own copy under your own GitHub account.
3. Clone your fork to your computer, make changes, commit, and push.
4. If you want your changes to come back into this repo, open a **Pull Request** from your fork.
Pull requests are welcome, especially from students. Typos, new question types, better styling, accessibility improvements, anything. If you are not sure whether an idea is worth a PR, open an issue and ask.
 
## Questions
 
If you are a current UW-Platteville student, ask in class or office hours. If you are from elsewhere on the internet, open an issue on this repo and I will try to get back to you.
 
Happy practicing.
