This project consists in a RAG-based clinical QA dataset and model for Spanish.

The catalogue of Spanish clinical guidebooks used for building the dataset of this project is publicly available on this link (https://portal.guiasalud.es/gpc/). I did not use all of the clinical guidebooks in the catalogue. I used 6 of them.

Description of files in this repository:
- "poster_SNS_QA_RAG.pdf": poster presentation describing the project.
- "clinical_guidebooks_txt.zip": clinical guidebooks in .txt format.
- "datasetting.ipynb": code for building the dataset.
- "dataset.csv": dataset.
- "SNS_QA_RAG.ipynb": code for the model (including some relevant explanations of the code).
- "faiss_index.bin": FAISS index used for retrieval.
- "predictions.csv": predictions of the model.
- "per-sample metrics.csv": results of the relevant metrics (cosine similarity and BERTscore F1) for each of the test samples.
- "all-sample metrics.csv": results of the relevant metrics (cosine similarity and BERTscore F1) for all the test samples (mean).
