# NLP Home Assignment - N-gram Language Models

This repository contains the implementation of an NLP-based home assignment focused on n-gram language models. The assignment was designed as a replacement for a traditional quiz and involves the implementation, evaluation, and comparison of different n-gram models using a chosen text corpus.

## Table of Contents

- [Project Overview](#project-overview)
- [Assignment Tasks](#assignment-tasks)
- [Implementation Details](#implementation-details)
- [Installation](#installation)
- [Usage](#usage)
- [Deliverables](#deliverables)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The objective of this project is to implement and evaluate several n-gram language models as part of an NLP home assignment. The tasks include selecting an appropriate text corpus, implementing unigram, bigram, and trigram models, applying smoothing techniques, and comparing the performance of these models based on their perplexity values.

## Assignment Tasks

### 1. Text Corpus Selection

- **Task**: Choose a text corpus in one language (English, Hebrew, or Arabic). The dataset should be large enough to implement reasonable language models but small enough to ensure efficient computation.
- **Considerations**: The selection process involves balancing the need for sufficient data with computational efficiency. The chosen dataset should be documented with the reasoning behind its size and composition.

### 2. Implementing N-gram Models

- **Task**: Implement basic unigram, bigram, and trigram language models from scratch.
- **Output**: Report the perplexity values for each model to evaluate their performance.

### 3. Trigram Model Modifications

- **Task**: Implement the following modifications on the trigram model and evaluate their impact on model performance:
  - **Add-delta Smoothing**: Experiment with delta values of 1 and 2.
  - **Kneser-Ney Smoothing**: Implement this technique as described in Jurafsky & Martin, Section 3.7.

- **Output**: Report the perplexity values for each modified model.

### 4. Model Comparison

- **Task**: Compare the different language models implemented (unigram, bigram, trigram with and without smoothing).
- **Discussion**: Discuss the advantages and disadvantages of each model based on the experimental results.

## Implementation Details

The implementation of the above tasks is provided in the `implementation.ipynb` Jupyter notebook. Below is a summary of what is included:

1. **Text Preprocessing**:
   - Load and preprocess the selected text corpus.
   - Implement tokenization and prepare the data for language modeling.

2. **N-gram Models**:
   - Implement unigram, bigram, and trigram models from scratch.
   - Calculate and report the perplexity values for each model.

3. **Smoothing Techniques**:
   - Apply add-delta and Kneser-Ney smoothing to the trigram model.
   - Evaluate the impact of these smoothing techniques on model perplexity.

4. **Results and Comparison**:
   - Compare the performance of different models based on their perplexity.
   - Discuss the experimental findings and implications for language modeling.

## Installation

To run the code provided in this repository, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/SamiHam162/NLP-Quiz.git
   cd NLP-Quiz
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Open the 'implementation.ipynb' notebook using Jupyter Notebook or Jupyter Lab:
   ```bash
   jupyter notebook implementation.ipynb

## Usage

1. Run the `implementation.ipynb` notebook to execute the code for each task.
2. The notebook will download the necessary dataset, preprocess it, and run the language models.
3. Review the outputs, including perplexity scores and model comparisons.

## Deliverables

The deliverables for this project include:

1. **Jupyter Notebook**: The `implementation.ipynb` notebook contains all the code required to reproduce the experiments.
2. **PDF Report**: A written report that describes the steps taken, including data collection, model implementation, experiment results, and discussion. The report includes mathematical definitions of the models.

## Contributing

Contributions to this project are welcome! If you have suggestions or improvements, please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
