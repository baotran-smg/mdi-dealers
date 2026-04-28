# BMW Group MDI Mockup on GitHub Pages

This folder is ready to publish on GitHub Pages.

## Contents

- `index.html`: main mockup page
- `404.html`: fallback page for direct deep links
- `.github/workflows/pages.yml`: auto-deploy workflow for GitHub Pages

## Publish Steps

1. Create a new GitHub repository, for example `mdi-dealer-mockup`.
2. Upload the contents of this folder to the repository root.
3. Push to the `main` branch.
4. In GitHub, open:
   `Settings` -> `Pages`
5. Under `Build and deployment`, set `Source` to `GitHub Actions`.
6. The included workflow will deploy the site automatically after the push.

## Resulting URL

Your site URL will normally be:

`https://<org-or-username>.github.io/<repo-name>/`

Example:

`https://swissmarketplacegroup.github.io/mdi-dealer-mockup/`

## Notes

- The page is fully static.
- The detailed listing tabs currently use mock listing-grain data derived from the BMW account profile.
- If you later want private or authenticated access, GitHub Pages is not ideal; use Tableau External Site or another managed host with access control.
