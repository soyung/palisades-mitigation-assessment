# Wildfire mitigation milestones — 10–20 ft High Exposure pathway

Interactive feasibility assessment of wildfire mitigation measures for Pacific Palisades,
organized to match the IBHS 10–20 ft High Exposure pathway
(Ember Defense → Spread Defense → Structure Defense → Neighborhood Resilience).

Palisades Recovery Coalition · Community Recovery Labs — discussion draft.

## Contents

- `index.html` — the assessment. A single self-contained page: all styles, scripts, and data
  are inline, no external requests, no build step.
- `vercel.json` — static hosting config (clean URLs, no-cache on the page so viewers always
  get the current version).

## Deploying

Static site, zero build configuration.

1. Push this directory to a GitHub repository.
2. On [vercel.com/new](https://vercel.com/new), import the repository.
3. Leave Framework Preset as **Other** and both the build command and output directory blank.
4. Deploy. Every later push to `main` redeploys automatically.

## Updating the page

`index.html` is a copy of `CRL_Mitigation_Assessment_10ft_Milestones_RESTART.html` in the
parent directory. Re-copy it over `index.html`, then commit and push.
