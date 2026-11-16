# Partha Sarathi Pal — Academic Website

A responsive, single-file academic website ready to deploy to GitHub Pages.

## Publish the website on GitHub Pages

1. Sign in to https://github.com.
2. Create a **public** repository named `<your-github-username>.github.io` (replace the placeholder with your exact GitHub username).
3. Upload `index.html` to the **root** of your repository (not inside a folder). Commit it to the `main` branch.
4. Go to **Settings → Pages**, and under **Build and deployment**, select **Deploy from a branch**. Choose branch `main` and folder `/(root)`, then save.
5. Open `https://<your-github-username>.github.io`. Publishing may take a few minutes.

If Pages already deploys automatically, you may not need to change the settings.

## Customize before publication

- **Your email**: Edit the `Email: Add your academic email...` text in `index.html` to your real academic email. You can add a clickable mailto link, e.g. `<a href="mailto:you@university.edu">you@university.edu</a>`.
- **Publications**: Add complete author lists, volumes, DOIs and publication links only after verifying them.
- **CV**: Upload a file named `cv.pdf` to the repository root, then add a link `<a href="cv.pdf">Download CV</a>` to your site.
- **Profile photo**: Replace the `<div class="portrait">PP</div>` element with `<img src="profile.jpg" alt="Portrait of Partha Sarathi Pal" class="portrait" style="object-fit:cover" />` and upload `profile.jpg` to the root of your repository.
- **Google Scholar, ORCID, LinkedIn**: Add your real URLs in the Contact section.
- **Publication status and degree status**: Update when your academic record changes.

## Preview locally

Open `index.html` in any browser. No frameworks or installation are required.

## Notes

- The website is static: no server, database or cost for standard public GitHub Pages hosting.
- It uses a system font stack and no third-party CSS/JavaScript dependencies.
- Keep private information and unapproved manuscripts out of a public repository.
