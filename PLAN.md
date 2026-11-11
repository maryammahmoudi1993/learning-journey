# Plan: 13 to 30 November 2026

Each day one old repository is improved on its own branch. Days that belong to the same repository are stacked: the next day branches from the previous day's branch and its pull request targets that branch.

| Day | Date | Repository | Scope for the day |
|---|---|---|---|
| 1 | Fri 13 Nov | KNN_IRIS_classification | `legacy/`, README skeleton; notebook 01: problem, KNN intuition, data; notebook 02: distance, choosing K, cross-validation |
| 2 | Sat 14 Nov | KNN_IRIS_classification, Classification_IRIS_KNN | Notebook 03: model comparison; notebook 04: SHAP or LIME; tests, CI; turn the duplicate into a README that points to the main repo (no deletion) |
| 3 | Sun 15 Nov | FashionNet | Structure, README; notebook 01: images as numbers, first CNN |
| 4 | Mon 16 Nov | FashionNet | Notebook 02: augmentation, curves, confusion matrix |
| 5 | Tue 17 Nov | FashionNet | Notebook 03: Grad-CAM or Captum; tests, CI; then vs now |
| 6 | Wed 18 Nov | LSTM_emotion_recognition | Structure, README; notebook 01: text to numbers, embeddings, LSTM baseline |
| 7 | Thu 19 Nov | LSTM_emotion_recognition | Notebook 02: compare with a small pretrained model on a fixed subset |
| 8 | Fri 20 Nov | LSTM_emotion_recognition | Notebook 03: word-level explanations; tests, CI |
| 9 | Sat 21 Nov | gan_Mnist | Structure, README; notebook 01: intuition and a minimal GAN |
| 10 | Sun 22 Nov | gan_Mnist | Notebook 02: samples across epochs, loss curves, instability, mode collapse; tests, CI |
| 11 | Mon 23 Nov | LSTM_passenges_prediction | Structure, README; notebook 01: shared split, ARIMA, Prophet |
| 12 | Tue 24 Nov | LSTM_passenges_prediction | Notebook 02: LSTM and a small Transformer on the same split; results table; tests, CI |
| 13 | Wed 25 Nov | Translation-spanish-english | Structure, README; notebook 01: the encoder-decoder LSTM explained |
| 14 | Thu 26 Nov | Translation-spanish-english | Notebook 02: attention and an attention heatmap |
| 15 | Fri 27 Nov | Translation-spanish-english | Notebook 03: compare with a pretrained model; honest metrics; tests, CI |
| 16 | Sat 28 Nov | Smile_detection_deep_VGG16 | Structure, README; transfer learning step by step; ethics note; dataset terms |
| 17 | Sun 29 Nov | Face-Expression | Structure, README; link or merge with the smile repo; Grad-CAM; tests, CI |
| 18 | Mon 30 Nov | Smile_detection_deep_VGG16 | Final polish, cross-links, learning-journey notes; final summary |

## Rules

- One repository per day. Do not merge pull requests without my review.
- Never delete, archive, rename or change the visibility of a repository. Never force-push.
- Original files stay in `legacy/` so the history of my progress stays visible.
- Never invent numbers. If a download or a run is blocked, say exactly what was blocked and finish the rest.
- Face datasets: write the dataset name, license and terms in the pull request before using them.
- Notebooks must run on a CPU in a few minutes, with a Colab badge for heavier runs.
- Git identity: Maryam Mahmoudi. No co-author trailers, no tool footers, no session links, anywhere.
- If something is unclear or irreversible, stop and ask.
