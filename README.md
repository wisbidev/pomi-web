# Pomi website

The public site of the Pomi app: the landing page (`index.html`, to come) and the privacy policy (`privacy/`), served by GitHub Pages.

`privacy/index.html` is generated in the private app repo from `docs/privacy-policy.md` with
`python3 scripts/build_privacy_page.py --out <this repo>`; edit the policy there, never here.
