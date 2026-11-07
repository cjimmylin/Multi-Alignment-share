# Multi-Alignment, shared outputs

A static site with the moral-psychology lane's papers (online and as PDF), slide decks (PDF) and narrated talks
(continuous video with the script). Open `index.html`, or the GitHub Pages site built from this repository.
Every judged number is from language-model judges no human expert has validated: PROVISIONAL · judges UNVALIDATED ·
no ranking. Only released items are quoted; no model is named or ranked. Regenerated from the private working
repository by its `outputs/dashboard/build_site.py`.

Last content update: 2026-11-07. The findings paper (v25) was rebuilt in place for one sentence in §S30, on the
lane's amendment A-27 (face and humility removed from its Schwartz quadrant map).

Publishing: `.github/workflows/pages.yml` deploys the site on every push to `main` and retries the deploy if GitHub is
slow (the built-in branch deploy gives up after 10 minutes). It needs Settings → Pages → Source set to "GitHub
Actions". When refreshing the site from `build_site.py`, copy the output over the repository; keep `.github/`.
