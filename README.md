# Session Transcript Pipeline information site

Public description, privacy policy, and terms for the personal Session Transcript Pipeline application.

Published with GitHub Pages at https://brumaih.github.io/ using the default GitHub address. This public repository is the static publication target. Maintain the source under `site/` in the private `brumaih/session-transcript-pipeline` repository, at `D:/repos/session-transcript-pipeline`. The transcript archive is in personal Google Drive.

## Maintenance

- Edit the HTML pages and shared stylesheet in the pipeline's `site/` directory; no build dependencies are required.
- Keep the application description and data-handling statements aligned with the implemented pipeline as it develops.
- GitHub Pages publishes the repository's configured source branch from the root directory.
- Keep any Google Search Console verification file or HTML tag in place after verification.
- Current hosting uses GitHub Pages for a public repository; no paid domain or hosting subscription was purchased.

Commit changes in the pipeline repository, then publish only this subtree from its root:

```powershell
git subtree push --prefix=site https://github.com/brumaih/brumaih.github.io.git codex/project-site
```

The original public site history was imported as a Git subtree. This command publishes only website files, preserving the public history and existing Google authorization URLs. Do not push the pipeline branch directly to the public repository. No separate website checkout is needed.
