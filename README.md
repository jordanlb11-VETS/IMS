IMS — Ops Command Planner

A programs & operations planner: tasks, programs, customer engagements, calendar,
Gantt chart with critical path, and team assignments — all in one page.

Publish this as a website (GitHub Pages)

I don't have a connected GitHub tool in this chat, so these last steps need to happen
on your end — it only takes a few minutes:





Go to https://github.com/new



Repository name: IMS



Set it to Public (GitHub Pages on a free account requires a public repo)



Click Create repository



On the new repo page, click Add file → Upload files



Upload the index.html file from this download



Commit the file (the default commit message is fine)



Go to Settings → Pages (left sidebar)



Under "Build and deployment" → Source, choose Deploy from a branch



Branch: main, folder: / (root) → Save



Wait about a minute, then refresh — GitHub will show your live URL, something like:

https://<your-username>.github.io/IMS/

Open that URL, then:





Bookmark it (Ctrl+D in Edge) and drag it into your Favorites bar



Share the same URL with your team



Important: this version does not share data between people yet

This file saves data to your browser's local storage. That means:





Your data will still be there every time you revisit the site — it survives closing the tab/browser.



If a teammate opens the same URL, they get their own separate copy — they won't see your tasks, and you won't see theirs.

To make it a truly shared, real-time tool where everyone sees the same live data,
it needs a small real backend (e.g. Firebase's free tier). Just say the word whenever
you're ready to add that — I can wire it in and it'll work on this same GitHub Pages URL.

Files in this folder





index.html — the entire app (upload this to the GitHub repo)
