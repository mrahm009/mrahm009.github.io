# mrahm009.github.io — portfolio site

Full single-file site. Upload the CONTENTS of this folder to your repo root.

## What's here
- index.html          the site (your real Scholar/ORCID/GitHub/LinkedIn already in it)
- docs/               your 4 CV/résumé PDFs (already wired to the CV section)
- images/             put images here; placeholder.jpg keeps the folder alive

## Add images (optional but high-impact)
Drop these into images/ and they appear automatically — no HTML editing needed
for the ones marked auto:
- portrait.jpg                 your headshot (hero)                    [auto]
- signal-1.png … signal-12.png frames for the drag-to-scrub viewer     [auto]

For the four research-thread figures you DO edit one line each (find "figslot"
in index.html): replace the grey slot with, e.g.
  <figure><img src="images/fig-sensor.jpg" alt="..."><figcaption>Caption.</figcaption></figure>
Filenames the text already suggests: fig-sensor.jpg, fig-artifact.jpg,
fig-tfa.jpg, fig-clinical.jpg

## Optional overview video
Record a short clip, save as images/overview.webm, and in the Overview section
swap the placeholder div for the commented-out <video> tag that's right above it.

## Interactive features already working
- Clickable program-map timeline with lane filters
- Publication Journal/Conference filter
- BibTeX toggles
- Drag-to-scrub signal viewer (activates when signal-N.png exist)
