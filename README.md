# Sonam Bala’s website

The homepage is the HTML, CSS, JavaScript and embedded images served by sonambala.com. Work opens the portfolio in work.html. Stumble reads words.json, populated from the live page’s built-in list. Google Fonts and externally hosted videos and posts need an internet connection.

## Preview

In this folder run `python3 -m http.server 8000` and open http://localhost:8000/. Try Stumble, the original navigation, Work, and the Home link on the Work page.

## Publish on GitHub Pages

1. Extract the ZIP. Open the GitHub repository that should serve the site. For a new site, create a public repository. Naming it USERNAME.github.io serves it at the account root. Other names work at a project URL.
2. Choose **Add file → Upload files**. Upload index.html, work.html and words.json directly to the repository root. README.md is optional. If updating an existing site, keep its CNAME and existing domain configuration. Commit the changes to main.
3. In **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
4. After the Pages deployment succeeds in Actions, use **Visit site** in Settings → Pages. Try every navigation entry, play a round of Stumble, open Work and return Home. Open work.html directly, too.
5. For a new domain connection, verify ownership of sonambala.com in your GitHub account’s Pages settings. Add sonambala.com as the repository’s custom domain and follow GitHub’s apex-domain DNS instructions at your DNS provider. Preserve unrelated email and verification records. Enable Enforce HTTPS when available. If the existing repository already serves sonambala.com, its current Pages and DNS settings may already cover this step.

[GitHub Pages publishing sources](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

[Custom domains and DNS](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)
