# 🌟 Sentence Similarity Highlighter 🌟

This Jupyter Notebook provides a comprehensive overview of the Sentence Similarity Highlighter tool, which highlights similar sentences between two text files using advanced techniques.

## 📚 Overview

The **Sentence Similarity Highlighter** tool reads two text files, segments the content into sentences, computes the similarity between corresponding sentences, and highlights them in an HTML file based on their similarity scores.

### 🚀 Features

- **Advanced Similarity Measurement**: Uses sentence embeddings from the `sentence-transformers` library for precise similarity computation.
- **Dynamic Color Mapping**: Displays sentences with colors ranging from blue (low similarity) to red (high similarity), enhancing visual analysis.
- **Color Legend**: Includes a legend to interpret the color coding effectively.

## 🛠️ Requirements

Before running the code, ensure you have the following libraries installed:

## How It Works❓
- Read Text Files: Loads the content of two text files separately.
- Sentence Segmentation: Breaks down each text into individual sentences using NLTK.
- Sentence Embeddings: Computes sentence embeddings using the Sentence Transformers library.
- Similarity Calculation: Measures cosine similarity between sentences to determine how similar they are.
- Color Mapping: Maps similarity scores to a gradient of colors, allowing for visual differentiation.
- Highlight Sentences: Wraps sentences in HTML with corresponding colors based on similarity, with text displayed in white for better readability.
- Save HTML: Generates a single HTML file containing highlighted sentences from both files along with a color legend for easy reference.

## Color Legend 🎨

- Blue: Low Similarity (0.0 - 0.2)
- Light Blue: Medium-Low Similarity (0.2 - 0.4)
- Purple: Medium Similarity (0.4 - 0.6)
- Light Red: Medium-High Similarity (0.6 - 0.8)
- Red: High Similarity (0.8 - 1.0)
