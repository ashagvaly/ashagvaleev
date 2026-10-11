# Profile and portfolio setup

## Display the README on the GitHub profile

1. Merge the profile and portfolio pull request into `main`.
2. Open this repository's **Settings → General → Repository name**.
3. Rename `ashagvaleev` to **`ashagvaly`**. Keep the repository public.
4. Open <https://github.com/ashagvaly> and check that the root `README.md` appears.

GitHub requires a public repository whose name exactly matches the account's username, with a nonempty `README.md` at the root. `ashagvaleev` does not match the username `ashagvaly`.

Reference: [GitHub profile README requirements](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme).

## Publish the portfolio with GitHub Pages

The pull request supplies a standalone static page in `docs/index.html`. It needs no package installation or build step.

After merging and renaming:

1. Open **Settings → Pages**.
2. Select **Deploy from a branch**.
3. Select **main** and **/docs**, then **Save**.
4. Wait for GitHub to confirm deployment; use the URL shown in Pages settings.
5. Add that verified URL to the README and the profile's Website field.

With the repository named `ashagvaly`, the default project site address is `https://ashagvaly.github.io/ashagvaly/`. Before renaming, it would be `https://ashagvaly.github.io/ashagvaleev/`. These are expected addresses, not confirmation of a live deployment.

For the shorter user-site address `https://ashagvaly.github.io/`, use a separate public repository named **`ashagvaly.github.io`** and put the contents of `docs/` at its root. The profile repository should still be named `ashagvaly`.

Reference: [Pages publishing settings](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) and [user versus project sites](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages).

## Content maintenance

Professional background, work technologies, education, and professional contact details are drawn from the user's current resume in Google Drive, updated on 11 October 2026. Project descriptions and additional project tools are based on the linked public repositories' source files, notebooks, and dependencies. The banking project is identified as a test assignment, and public ML research is described as exploratory. Production ML deployment ownership and business impact figures are not claimed.

Keep the README and portfolio consistent when updating career details. Add a CV or LinkedIn link once a suitable public URL has been confirmed. LightGBM is omitted because it is not supported by the current resume or inspected project code. The Drive resume's sharing permissions have not been changed, and its URL is not published here.
