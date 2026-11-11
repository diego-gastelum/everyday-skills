# article-quiz

Tests whether you understood what you just read. It asks questions first and grades your answers against the article.

[![Download article-quiz](https://img.shields.io/badge/Download-article--quiz-2ea44f?style=for-the-badge)](https://github.com/diego-gastelum/everyday-skills/raw/main/downloads/article-quiz.zip)

1. Click Download.
2. In Claude, go to Customize > Skills, click +, then Upload a skill, and pick the file you downloaded. On some accounts it's under Settings > Capabilities > Skills.
3. Start the quiz:
   - **In the Claude in Chrome side panel:** open the article, open Claude, and say "quiz me" or type /article-quiz.
   - **Anywhere else in Claude:** say "quiz me on" and paste the link or the article text.

Works on Mac and Windows, in Claude on the web, desktop, mobile, and the Chrome side panel. Only the side panel can see the page you have open; everywhere else, give it the link or the text.

## What it does

It has you sum up the piece in two or three sentences, then asks three open questions, one at a time. Each answer gets graded right, partly right, or wrong, with a quote from the article showing what it actually says. Miss one and you get a hint and a second try. At the end you explain the idea in your own words and it marks what's wrong or missing. It doesn't rewrite it for you.

Say "deep" for five to seven questions instead of three.

The idea comes from the Feynman Technique. Explaining something in plain words shows you where you don't understand it yet.

## Other ways to use it

**ChatGPT, Gemini, or any other chatbot.** Open [`prompt.md`](prompt.md), click the copy icon at the top right, paste it into your chatbot, then paste the article.

**Claude Code.** Unzip the download into `~/.claude/skills/`, or on a Mac paste this into your terminal:

```bash
curl -sL https://github.com/diego-gastelum/everyday-skills/raw/main/downloads/article-quiz.zip -o /tmp/article-quiz.zip && unzip -o /tmp/article-quiz.zip -d ~/.claude/skills/
```

## License

[CC BY 4.0](../LICENSE). Use and change it however you like. If you share it, credit Diego Gastelum.
