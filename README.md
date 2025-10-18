# -datasci-team-name
# Aldar Kose Storyboard (ML Track)
This project creates a 6-8 images story about Aldar Kose based on 4-6 sentences

## Quickstart
1) Open `main.ipynb` in Colab.
2) Run all cells – generates `/outputs` and `index.json`.

## Deliverables
- Colab + repo, weights, PNG/JPG + index.json, slides

## Reproducibility
- Python: 3.10
- Colab: https://colab.research.google.com/drive/1ZaPs1Rb1sv0koTjTuiHH4mV7zHIm7Wfo?hl=ru#scrollTo=G4y9zT2TIH9v
- Weights link: <to-be-added>

## Pipeline 
 1. Input 2-4 prompt sentences
 2. Feed into 2-4 prompt to gpt. Gpt divides story into slides and generates detailed prompt.
 3. Train a model to generate consistent characters and preserving cultural identity.
 1. Gather 10-20 images of aldar kose from different perspectives.
 2. Kazakh cultural clothes from different perspectives.
 4. Check consistency of characters/background accross slides.

## Criteria
- Technical implementation & ML justification — 70%
- Character consistency & story coherence — 20%
- Story quality & reproducibility — 10%

## Structure
- Input 2-4 sentences
- Output 6-10 frame storyboard
