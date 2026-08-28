# RightPickr — Privacy Policy

The privacy policy for the RightPickr iOS app, served as a static page so it
has a public URL that App Store Connect and the app itself can link to.

`index.html` is the whole site. No build step, no dependencies.

## Publishing

GitHub Pages serves this from the repository root on the `main` branch.
Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.

The live URL is then:

    https://<your-github-username>.github.io/rightpickr-privacy/

## Editing

Edit `index.html` and push. Pages redeploys in a minute or two.

Two things to keep true when you edit:

- **The date at the top.** It claims to be the last substantive change, so it
  should be one.
- **The visibility table.** Every row states a rule that the database actually
  enforces through row-level security. If a rule changes in the app, that table
  is wrong until it changes here too — a privacy policy that overstates its
  protections is worse than a vague one.
