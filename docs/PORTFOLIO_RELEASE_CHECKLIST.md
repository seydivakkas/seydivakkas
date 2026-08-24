# Portfolio Release Checklist

This checklist tracks the remaining public-profile work after the GitHub flagship repository standardization sprint.

## Completed

- [x] Professional GitHub profile README
- [x] Canonical flagship project order
- [x] `merinpsVision` renamed to **WeaveVision**
- [x] Generic test repositories removed from the portfolio
- [x] Six flagship README hero sections standardized
- [x] Long technical README content preserved under `docs/README_FULL.md` where appropriate
- [x] DeepfakeULTRA claims aligned with current machine-readable evaluation artifacts
- [x] DeepfakeULTRA licensing inconsistency corrected
- [x] DeepfakeULTRA `CITATION.cff` added
- [x] WeaveVision and AI Carpet static test badges replaced with live CI status
- [x] Evidence / architecture / limitations structure added to AI flagship repositories
- [x] Initial security and portability audit completed
- [x] Personal absolute paths removed from public artifacts discovered during the audit
- [x] Minimum reproducible run documented across flagship repositories
- [x] Engineering brand canon created
- [x] GitHub metadata canon created
- [x] LinkedIn profile canon created
- [x] CV project canon created
- [x] Six social-preview designs prepared; corrected DeepfakeULTRA preview uses canonical metrics
- [x] TinyOLED `v1.0.0` readiness gate, CI workflow, limitations and release-notes draft created
- [x] ATS-friendly one-page English CV generated and visually verified

## Manual GitHub UI - blocking

### Default branch migration

Switch the following repositories from `master` to `main`:

- [ ] DeepfakeULTRA
- [ ] SİNAPTİC5G
- [ ] WeaveVision
- [ ] TinyOLED-Desktop

Do not delete `master` until Actions / Pages behavior is confirmed on `main`.

### Repository metadata

Apply the values from `docs/GITHUB_METADATA_CANON.md` to the GitHub **About** panel:

- [ ] DeepfakeULTRA
- [ ] SİNAPTİC5G
- [ ] WeaveVision
- [ ] Halı AI Carpet Design
- [ ] TinyOLED-Desktop
- [ ] MPI Parallel Matrix Multiplication

### Social preview

Upload the approved 1280x640 image to **Settings -> Social preview**:

- [ ] DeepfakeULTRA
- [ ] SİNAPTİC5G
- [ ] WeaveVision
- [ ] Halı AI Carpet Design
- [ ] TinyOLED-Desktop
- [ ] MPI Parallel Matrix Multiplication

## TinyOLED `v1.0.0`

After `main` becomes the default branch:

- [ ] Run `Actions -> CI -> Run workflow` on `main`
- [ ] Confirm CI is green
- [ ] Confirm GitHub Pages deployment is green
- [ ] Smoke-test `sudo bash install.sh` on Raspberry Pi
- [ ] Confirm SSD1306 / I2C startup and three-button interaction
- [ ] Compare browser simulator behavior with the hardware application catalog
- [ ] Record immutable release commit SHA in `RELEASE_READINESS.md`
- [ ] Publish `v1.0.0` only after every gate passes

## LinkedIn

Apply `docs/LINKEDIN_PROFILE_CANON.md`:

- [ ] Headline
- [ ] About
- [ ] Featured #1 - DeepfakeULTRA
- [ ] Featured #2 - SİNAPTİC5G
- [ ] Featured #3 - WeaveVision
- [ ] Featured #4 - Halı AI Carpet Design

## CV

- [x] One-page ATS-friendly English engineering CV
- [ ] Add preferred public email / phone only if intentionally published
- [ ] Optional two-page academic CV variant
- [ ] Optional role-targeted variants: AI/ML, Computer Vision, Edge AI, Industrial AI

## Next portfolio layer

- [ ] Personal portfolio website
- [ ] Stable project demo / evidence pages where appropriate
- [ ] Keep GitHub, LinkedIn and CV metrics synchronized with `BRAND_CANON.md`

## Canonical signal

**AI Research -> Edge AI -> Industrial AI -> Generative AI -> Embedded Systems -> HPC**
