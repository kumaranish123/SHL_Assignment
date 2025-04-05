# SHL_Assignment
This project predicts grammar scores (0–5) for audio files. It uses Librosa to load WAV files, transcribes audio with facebook/wav2vec2-base-960h, extracts sentence embeddings via all-MiniLM-L6-v2, and applies a RandomForestRegressor for scoring. The predictions are saved in a CSV(submission.csv) for Kaggle.
