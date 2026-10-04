# Song Aesthetics Evaluator

A machine learning project that predicts how musical a song is from acoustic features extracted from its audio.

Built for an AI course project (Oct–Dec 2025).

## Overview

The project asks whether audio features alone can predict how musical or aesthetically pleasing a song is. Several regression models are trained on the same feature set and compared on standard regression metrics.

## Features used

Acoustic features extracted from each track, including:

- Spectral centroid
- Spectral bandwidth
- Spectral flatness
- Richness
- : list the remaining features

## Models compared

- : e.g. Linear Regression, Random Forest, SVR, ...

Evaluated with : e.g. MAE, RMSE, R².

## Results

: add a small table with each model and its metrics, plus one line on the best model.

## Repository contents

| File | What it is |
|---|---|
| `AI Assignment 1 (code+report) (1).zip` | Assignment 1 code and report |
| `BaseLine_Model_ASGN2.zip` | Baseline model (Assignment 2) |
| `AI_FINAL_PROJECT.zip` | Final project code and report |

## How to run

```bash
git clone https://github.com/khadijaiftikhar7/AI-FINAL-PROJECT---SONG-AESTHETIC-EVALUATOR.git
cd AI-FINAL-PROJECT---SONG-AESTHETIC-EVALUATOR
pip install -r requirements.txt   # : add a requirements.txt
python main.py                    # : or open the notebook
```

## Dataset

: where the audio feature dataset came from and how it is loaded.

## License

MIT
