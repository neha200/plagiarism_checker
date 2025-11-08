# Plagiarism Checker

A simple machine learning-based plagiarism detection app using Streamlit.

## Features
- Compares original and submission text files
- Calculates similarity
- Predicts plagiarism using a trained ML model

## Folder Structure
```
plagiarism_checker/
	 app.py                # Streamlit web app
	 data_prep.py          # Data preparation utilities
	 model.py              # Model training script
	 requirements.txt      # Python dependencies
	 utils.py              # Utility functions
	 plagiarism_model.pkl  # Trained ML model
	 plagiarism_dataset.csv # Training data
	 sample_data/
		  original.txt      # Original reference text
		  submission.txt    # Student submission text
```

## Getting Started
1. Install dependencies:
	```sh
	pip install -r requirements.txt
	```
2. Prepare your data in `plagiarism_dataset.csv`.
3. Train the model:
	```sh
	python model.py
	```
4. Run the app:
	```sh
	streamlit run app.py
	```

## Usage
- Place your reference text in `sample_data/original.txt`.
- Place the submission text in `sample_data/submission.txt`.
- The app will display similarity and plagiarism prediction.

## Outputs
<img width="468" height="272" alt="image" src="https://github.com/user-attachments/assets/834b3202-6d7c-49d4-8ab7-b83ae64c47da" />
<img width="468" height="272" alt="image" src="https://github.com/user-attachments/assets/1be03fea-0e59-4bd6-ac98-097e6e524f8a" />


