# Indonesian News Information Retrieval

## Description

An Information Retrieval project for Indonesian news articles, focusing on keyword-based document retrieval, similarity analysis, document ranking, and query expansion to evaluate and compare search effectiveness.

## Requirements

- Python 3.10 or newer
- pip
- Internet access for installing dependencies (if required)

## Retrieval Method

This project using Cosine Similarity as retrieval method to retrieve and ranking similar documents from query.

## Datasets

This project using Indonesian News Article from Kompas.com. You can find more information about the dataset [here](https://www.kaggle.com/datasets/yogaarifin/indonesian-news-article-from-kompas-com).

## Setup

Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/Scripts/activate
```

On Windows PowerShell, you can use:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

Then install the project dependencies:

```bash
pip install -r requirements.txt
```

If the project uses additional libraries, install them as needed:

```bash
pip install numpy pandas scikit-learn
```

## Run the Project

After the environment is activated and dependencies are installed, run the notebook or script to start

```bash
python app.py
```

## Project Structure

```text
.
├── README.md
├── requirements.txt
├── .venv/
├── src/
│   ├── app/
│   └── data/
└── ...
```