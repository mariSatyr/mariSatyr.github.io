# Deep Time Explorer — which image goes where

The site (Deep_Time_Explorer_0_l7vv.html) has 6 stages. Each stage has a hero area with 3 clickable pins, and a Fossil & Specimen Gallery with 2–3 items. The current visuals are all inline SVG shapes — there are no photo files in the HTML to replace 1-to-1, so swapping means replacing each SVG with an `<img>` pointing at the file below.

24 unique images cover all 34 slots (pins + gallery items that repeat a subject share one file).

## 1. Hadean Eon (4.6 – 4.0 Ga)

Hero pins:
- Asteroid impact → `01-hadean/asteroid-impact.jpg`
- Lava crust → `01-hadean/lava-crust.jpg`
- Steam cloud → `01-hadean/steam-cloud.jpg`

Specimen gallery:
- Zircon crystal → `01-hadean/zircon-crystal.jpg`
- Meteorite → `01-hadean/meteorite.jpg`

Suggested hero background (the big top image): `01-hadean/asteroid-impact.jpg` or `01-hadean/lava-crust.jpg`

## 2. Archean Eon (4.0 – 2.5 Ga)

Hero pins:
- Stromatolites → `02-archean/stromatolites.jpg`
- Cyanobacteria mat → `02-archean/cyanobacteria-mat.jpg`
- Hazy orange sky → `02-archean/hazy-orange-sky.jpg`

Specimen gallery:
- Stromatolite → `02-archean/stromatolites.jpg` (same file as the pin)
- Microbial laminae → `02-archean/microbial-laminae.jpg`

Suggested hero background: `02-archean/stromatolites.jpg` or `02-archean/cyanobacteria-mat.jpg`

## 3. Proterozoic & Great Oxidation (2.5 Ga – 635 Ma)

Hero pins:
- Banded iron layers → `03-proterozoic/banded-iron-formation.jpg`
- Eukaryote cells → `03-proterozoic/eukaryote-cells.jpg`
- Snowball ice → `03-proterozoic/snowball-earth.jpg`

Specimen gallery:
- Banded Iron Formation → `03-proterozoic/banded-iron-formation.jpg` (same file as the pin)
- Eukaryote microfossil → `03-proterozoic/eukaryote-cells.jpg` (same file as the pin)
- Glacial dropstone → `03-proterozoic/glacial-dropstone.jpg`

Suggested hero background: `03-proterozoic/banded-iron-formation.jpg`

## 4. Ediacaran Period (635 – 541 Ma)

Hero pins:
- Dickinsonia → `04-ediacaran/dickinsonia.jpg`
- Charnia → `04-ediacaran/charnia.jpg`
- Spriggina → `04-ediacaran/spriggina.jpg`

Specimen gallery:
- Dickinsonia impression → `04-ediacaran/dickinsonia.jpg` (same file as the pin)
- Charnia frond → `04-ediacaran/charnia.jpg` (same file as the pin)
- Microbial mat texture → `04-ediacaran/microbial-mat-texture.jpg`

Suggested hero background: `04-ediacaran/dickinsonia.jpg`

## 5. Early Cambrian Explosion (541 – 525 Ma)

Hero pins:
- Vertical burrows → `05-early-cambrian/vertical-burrows.jpg`
- Small shelly fossils → `05-early-cambrian/small-shelly-fossils.jpg`
- Early arthropod → `05-early-cambrian/early-arthropod.jpg`

Specimen gallery:
- Small shelly fossil → `05-early-cambrian/small-shelly-fossils.jpg` (same file as the pin)
- Trace burrows → `05-early-cambrian/vertical-burrows.jpg` (same file as the pin)
- Early arthropod → `05-early-cambrian/early-arthropod.jpg` (same file as the pin)

Suggested hero background: `05-early-cambrian/early-arthropod.jpg`

## 6. Middle Cambrian: Burgess Shale (508 Ma)

Hero pins:
- Anomalocaris → `06-burgess-shale/anomalocaris.jpg`
- Trilobites → `06-burgess-shale/trilobites.jpg`
- Hallucigenia → `06-burgess-shale/hallucigenia.jpg`

Specimen gallery:
- Anomalocaris → `06-burgess-shale/anomalocaris.jpg` (same file as the pin)
- Trilobite exoskeleton → `06-burgess-shale/trilobites.jpg` (same file as the pin)
- Pikaia → `06-burgess-shale/pikaia.jpg`

Suggested hero background: `06-burgess-shale/anomalocaris.jpg`

## How to use

1. Unzip the folder and upload it to Google Drive (see note below).
2. In the HTML, replace each stage's SVG hero art with an `<img>` for its suggested hero background, replace each pin's SVG with the pin file, and replace each specimen-gallery SVG shape with the gallery file.
3. Add the credits from `SOURCES.md` — 9 of the 24 images are CC-BY / CC-BY-SA and must be credited; the other 15 are Public Domain / CC0.

## A note on "put in Google Docs"

Google Docs itself doesn't take a zip of images — a folder of photos belongs in **Google Drive**. Upload the unzipped folder (or the zip) to Drive, and from Drive you can insert individual images into a Google Doc, or share the folder. The zip in this delivery is the whole folder, ready to upload.
