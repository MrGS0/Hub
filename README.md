Adding a project (every time, ~30 seconds)
	1.	Claude delivers the project as one self-contained .html file.
	2.	In the hub, tap the ghost row at the bottom of the list
(+ projects/your-next-idea.html). It opens GitHub’s new-file editor
already inside the projects/ folder.
	3.	Type a filename like merge-lab.html (lowercase, dashes — the hub turns
it into the display name “Merge Lab”).
	4.	Paste the code, Commit changes.
	5.	Back in the hub, tap refresh. Done.
Notes
	•	Privacy — GitHub Pages on the free plan only serves public
repositories. If the projects must be private, deploy the same files with
Netlify or Cloudflare Pages (both free, both support private repos);
then fill in owner and repo in the CONFIG block.
	•	CONFIG — open index.html and search for CONFIG to change the page
title, folder name, or to set the repository manually (needed for custom
domains, Netlify/Cloudflare, or local testing). On *.github.io everything
auto-detects.
	•	API limit — the hub uses GitHub’s anonymous API: 60 requests per hour
per network. The list is cached for 5 minutes per session, so normal use
never gets close. If you ever hit it, it resets within the hour.
	•	Backup — the repository is the backup. Every project has full version
history, and cloning the repo gives you every file.
