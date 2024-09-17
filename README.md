# TF-IDF and Cosine Similarity Analysis on University Journal Abstracts

This repository implements Term Frequency-Inverse Document Frequency (TF-IDF) and Cosine Similarity analysis on a collection of university journal abstracts. It provides tools for parsing abstracts, calculating term frequencies, visualizing term distributions, and measuring the similarity between documents using Cosine Similarity.

## Features

- **Term Frequency Calculation**: Parse abstracts and calculate the frequency of terms across all documents.
- **TF-IDF Analysis**: Compute TF-IDF values to evaluate the importance of terms in relation to all documents.
- **Cosine Similarity**: Measure the similarity between abstracts.
- **Visualization**: Generate heatmaps to visualize term frequency distribution.

## Requirements

- Python 3.x
- Libraries: Install required dependencies by running:

  ```bash
  pip install -r requirements.txt
  ```

## Usage

### Step 1: Prepare the Data
Place your abstract text files (e.g., `abstrak1.txt`, `abstrak2.txt`, etc.) in the root directory of the repository. These should contain the journal abstracts you want to analyze.

### Step 2: Run the Analysis
To run the analysis, simply execute the main script:

```bash
python main.py
```

### Step 3: View the Results
The script will output the following information:
- **Term Frequency**: Displays the frequency of each term across all abstracts.
- **TF-IDF Values**: Outputs the calculated TF-IDF values for the terms.
- **Cosine Similarity**: Shows the similarity percentage between each pair of abstracts.
- **Heatmap**: A heatmap visualization of the most frequent terms is generated, helping to visualize the term distribution across abstracts.

### Example Output
Upon execution, the output will look like this:

```
Successfully read: abstrak1.txt
Successfully read: abstrak2.txt
...

Term Frequencies:
-------------------
term1: 10
term2: 7
...

Cosine Similarity Results:
----------------------------
Abstract 1 and Abstract 2: 27.60% (Low similarity)
Abstract 1 and Abstract 3: 23.38% (Low similarity)
...
```

### Visualization
A heatmap will be generated to visualize the top frequent terms across the abstracts.

## Contribution
Feel free to submit pull requests or open issues for improvements and bug fixes.

