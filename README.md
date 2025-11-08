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
