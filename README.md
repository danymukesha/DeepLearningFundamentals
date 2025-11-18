# Introduction to Deep Learning for Bioinformatics

[![CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains materials for the **"Introduction to Deep Learning"** course.

## Course Description

A two-day practical course covering deep learning fundamentals and their application to bioinformatics tasks. Learn to implement neural networks with Keras, preprocess biological data, and apply pre-trained models to real-world problems.

## Quick Start

### Prerequisites
- Basic bioinformatics knowledge
- Python 3.8+ and Linux/MacOS terminal
- (Optional) CUDA-compatible GPU for accelerated training

### Environment Setup

1. **Install Micromamba** (recommended package manager):
```bash
curl -L https://micro.mamba.pm/install.sh | bash
```

2. **Create and activate the course environment:**
```bash
micromamba create -n dl-course python=3.9 tensorflow keras jupyter matplotlib pandas scikit-learn
micromamba activate dl-course
```

3. **Launch Jupyter to run the tutorials:**
```bash
jupyter notebook
```

### Running the Code

All code examples are provided in the bookdown chapters. Start with:
1. `02-Keras-Basics.Rmd` - the first neural network
2. `03-Data-Preprocessing.Rmd` - handling biological data
3. `04-CNN-Genomics.Rmd` - DNA sequence analysis

## Course Structure

1. **Introduction to Deep Learning**
2. **Keras Basics** - Building and training neural networks
3. **Data Preprocessing** - Encoding biological sequences
4. **CNNs for Genomics** - Motif discovery and sequence analysis
5. **LLMs in Bioinformatics** - Pre-trained models and transfer learning
6. **Advanced Topics** - Regularization, hyperparameter tuning, interpretability

## Case Study: Transcription Factor Binding Prediction

See `case-study/` directory for a complete example predicting CTCF transcription factor binding from DNA sequences.

## View the Book

The complete course materials are available at:  
**https://danymukesha.github.io/DeepLearningFundamentals/**

## Getting Help

- Course issues: Open a GitHub Issue
- Keras questions: [Keras Documentation](https://keras.io/)

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

