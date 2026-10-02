# GitPaper

**Write LaTeX papers together by handing them back and forth.**

GitPaper is a desktop app for writing academic papers with collaborators. It isn't a Google-Docs-style editor where everyone types at once. It's built for the way papers are actually written: one person drafts a section, **hands it off**, a collaborator revises and comments, and it goes **back and forth** until it's done. GitHub keeps everything in sync in the background, so nobody emails `paper_v7_FINAL_reallyfinal.tex` around.

## How it works

Every paper is a GitHub repository that you own. You never need to learn Git.

1. **Write.** Edit your LaTeX in the built-in editor and press **Ctrl+S**. The PDF compiles and appears right beside your text.
2. **Hand off.** Press **Save & push**. Your changes go to GitHub, and a ping can let your collaborator know it's their turn.
3. **Review.** Your collaborator presses **Pull** to get your latest version. They revise the text, and they can leave **comments** on any passage, reply to each other, and resolve them. Comments travel with the paper.
4. **Hand back.** They **Save & push**, and you **Pull**. Repeat until the paper is finished.

If you both edit the same lines at the same time, GitPaper shows the two versions and helps you pick which to keep. Nothing is silently overwritten.

## What's in it

- A LaTeX editor with a live PDF preview and jump-to-source in both directions
- Inline comments with replies and resolve, saved as part of the paper
- Pull, push and merge-conflict resolution inside the app
- Invite collaborators by GitHub username
- A status on every paper (In Revision, Awaiting Response, Submitted, Published)
- Starter templates, including IEEE conference and journal
- Automatic LaTeX setup: it uses the LaTeX already on your computer, or installs a compact one for you
- Works offline for writing; GitHub is needed only to sync

## Install (Windows)

1. Download **GitPaper-Setup-x.y.z.exe** from the [latest release](../../releases/latest).
2. Run it. The installer isn't code-signed yet, so Windows may show a "Windows protected your PC" warning. Click **More info → Run anyway**.
3. Open GitPaper and sign in with GitHub. A short walkthrough covers the rest.

You need a free GitHub account. The app updates itself when a new version is released.

Only Windows is available so far. Mac and Linux are planned.

## Status

GitPaper is early software and changing quickly. This repository only hosts the installers and the update feed; the app's source code is not published here.
