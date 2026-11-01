# Gelin Bian — Academic Homepage

An English-only academic homepage with education, research interests, and a GitHub contact link. Responsive on desktop and mobile. The page is a standalone HTML file with no build tools, JavaScript, external fonts, or image dependencies.

Target repository: https://github.com/gelinbian/gelinbian.github.io

Target URL after deployment: https://gelinbian.github.io/

Status: prepared locally; not deployed by this chat.

## Deploy to GitHub Pages

1. Sign in to GitHub as **gelinbian** and open https://github.com/new. Set the owner to `gelinbian`, name the repository `gelinbian.github.io`, choose **Public**, enable **Add README**, and create it. If this repository already exists, inspect its contents before making changes.
2. Extract the website ZIP. Select **Add file → Upload files** and upload `index.html`, `README.md`, and `.nojekyll` to the repository root on `main`. Do not upload the ZIP itself or nest the files in another folder. On macOS, press **Command + Shift + .** in Finder to show `.nojekyll`. This plain HTML page also works if that empty file is omitted.
3. Open **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, select **main** and **/(root)**, then save.
4. Check the **pages build and deployment** run under **Actions**. Once successful, use **Visit site** in Pages settings. Publication can take about 10 minutes. Check the education entries, navigation, mobile layout, and GitHub links.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Existing repository

The existing repository is `gelinbian/lin902.github.io`. This chat has not modified or deleted it.

If the only reason for replacing it is the username change, you can rename it to `gelinbian.github.io` under **Settings → General → Repository name**, upload the new files, and configure Pages. Choose either renaming or creating a new repository; the destination name must be available before renaming. Renaming preserves repository history.

Before changing the old site, you can save its current files through **Code → Download ZIP**. That ZIP does not include Git history.

You do not need to delete the old repository to create a new one. After the new site works, decide whether to retain the old site. If you choose to delete it, back it up first and follow GitHub's confirmation process under the old repository's **Settings → General → Danger Zone → Delete this repository**. Check the repository name carefully.

## Edit the content

Edit `index.html` directly. English comments identify the profile, education, and contact sections. Keep the biography and metadata consistent with changes to education. Commit updates to publish them again.

Current content is based on the previous public homepage:

- Name: Gelin Bian.
- 2023–2025: MSc in Artificial Intelligence, The Hong Kong University of Science and Technology (Guangzhou).
- 2019–2023: Bachelor's degree in Communication Engineering, Nanjing University of Posts and Telecommunications.
- Research interests: LLM explainability, latent spaces in LLM reasoning, and agent systems.
- Contact: https://github.com/gelinbian.

The old email link was `gelinbian666@gmail`, which has an incomplete domain. No email address was inferred or added. Add a `mailto:` link once the full address is confirmed. Time-sensitive statements about employment, a gap year, or PhD applications were not carried over. No unverified supervisors, publications, awards, grades, or employment details were added.

For an offline preview, open `index.html` in a browser. If an already-open tab still shows an older version, reload it.

## Repository, permissions, and template review

Checks performed on October 30, 2026:

- The old repository was public, with `main` as its default branch and README.md, index.html, and images/ at the root.
- The connected GitHub account was `labixiaoQ`, with `pull: true`, `push: false`, and `admin: false` on the old repository.
- The target repository returned 404 through that connection. This indicates that it was inaccessible to the connected account, not definitive proof that it did not exist.
- The local GitHub CLI was signed out, and the in-app browser redirected repository creation to the sign-in page.
- No remote writes, repository creation, renaming, deletion, or Pages deployment were performed. The site was not published to another hosting provider.

Reference template inspected: https://github.com/yangxinrui811/minimal-academic-homepage. Its README describes a minimal academic homepage and permits personal academic adaptation. Its current HTML contains the author's own research details and external resources. This version adapts the template’s visual styling into a single HTML file: light gray background, white rounded cards, soft shadows, blue links, topic pills, a profile section, and education entries. The source is credited in the HTML and page footer. The original author’s personal content and images are not included.

Personal information source: https://github.com/gelinbian/lin902.github.io/blob/main/index.html

Source blob SHA at inspection: `9585f55a620fe190e5051f5e9541f00daa562b1c`.

## November 1, 2026 update

All website content, metadata, accessibility labels, code comments, and this README are in English. The deployment method is unchanged. The design now follows Minimal Academic Homepage, with education immediately after the profile. Initials stand in for a profile photo. Project and publication layout classes are included for future use; no unverified entries are displayed.
