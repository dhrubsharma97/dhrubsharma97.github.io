Deploying your site to GitHub Pages (free, ~5 minutes)
Go to https://github.com/new and create a repository named `dhrub-sharma.github.io`
(replace `dhrub-sharma` with your actual GitHub username — this exact naming pattern
gives you a free URL at `https://<your-username>.github.io`).
On the new repo's page, click Add file → Upload files, and drag in `index.html`
from this folder.
Commit the upload directly to the `main` branch.
Go to Settings → Pages in the repo. Under "Build and deployment", make sure
Source is set to "Deploy from a branch" and Branch is `main` / `(root)`. Save.
Wait 1–2 minutes, then visit `https://<your-username>.github.io` — your site is live.
Optional: add your CV as a downloadable PDF
The "Download CV" button links to a file named `CV_Dhrubjyoti_Sharma.pdf`. Upload your
actual CV PDF to the same repo with that exact filename, and the button will work.
If you skip this, just remove or edit that button in `index.html`.
Editing later
Everything is in one file, `index.html` — text, layout, and styling. To change any
text, open the file in GitHub (or any editor), edit the relevant line, and commit —
the live site updates automatically within a minute.
Custom domain (optional)
If you own a domain, add a `CNAME` file with just the domain name in it, and point
your domain's DNS to GitHub's Pages IPs (instructions: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
