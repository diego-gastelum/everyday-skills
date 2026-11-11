# article-quiz

Quizzes you on something you just read. You already read it, so it asks before it explains anything.

It has you sum up the piece in two or three sentences, then asks three open questions, one at a time. Each answer gets graded right, partly right, or wrong, with a quote from the article showing what it actually says. Miss one and you get a hint and a second try. At the end you explain the idea in your own words and it marks what's wrong or missing. It doesn't rewrite it for you.

Say "deep" for five to seven questions instead of three.

The idea comes from the Feynman Technique. Explaining something in plain words shows you where you don't understand it yet.

## Install

**Claude (web, desktop, mobile, and the Chrome side panel)**

1. Download [`article-quiz.zip`](../downloads/article-quiz.zip).
2. In Claude, go to Customize > Skills, click +, then Upload a skill, and pick the zip. On some accounts it's under Settings > Capabilities > Skills.
3. Open an article and say "quiz me." In the Claude in Chrome side panel it reads the page you have open.

**Claude Code**

Copy this `article-quiz` folder into `~/.claude/skills/`, then say "quiz me on" and the link.

**ChatGPT, Gemini, or any other chatbot**

Copy the text of [`prompt.md`](prompt.md), paste it in, then paste the article. A link works only if your chatbot can open web pages.

Works on Mac and Windows.

## License

[CC BY 4.0](../LICENSE). Use and change it however you like. If you share it, credit Diego Gastelum.
