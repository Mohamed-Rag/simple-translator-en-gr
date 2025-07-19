# Simple English-German Translator

## Overview
This project implements a simple machine translation model for translating text from German to English using Natural Language Processing (NLP) techniques. The project demonstrates fundamental concepts in neural machine translation and sequence-to-sequence modeling.

## Project Description
The Simple English-German Translator is an NLP application that focuses on basic translation capabilities between German and English languages. This project serves as an educational tool for understanding machine translation concepts and implementing them using Python.

## Features
- **German to English Translation**: Core functionality for translating German text to English
- **NLP Processing**: Text preprocessing and normalization techniques
- **Sequence Handling**: Implementation of sequence-to-sequence translation
- **Educational Focus**: Clear code structure for learning purposes

## Technology Stack
- **Python**: Primary programming language
- **Jupyter Notebook**: Development environment
- **Natural Language Processing Libraries**: 
  - `string` for text processing
  - `re` for regular expressions
  - `pickle` for data serialization
  - `unicodedata` for text normalization
  - `numpy` for numerical operations

## Installation and Setup

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook
- Required Python libraries

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Mohamed-Rag/simple-translator-en-gr.git
   cd simple-translator-en-gr
   ```

2. **Install required dependencies**:
   ```bash
   pip install numpy pickle-mixin unicodedata
   ```

3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

4. **Open the project notebook**:
   Open `project2.ipynb` in your Jupyter environment

## Usage

### Running the Translation Model
1. Open `project2.ipynb` in Jupyter Notebook
2. Execute the cells sequentially to:
   - Import necessary libraries
   - Load and preprocess the translation data
   - Train the translation model
   - Test translations with sample text

### Example Usage
The notebook contains examples of basic German-English translations such as:
- "go" → "geh"
- "hello" → "hallo"
- "help" → "hilfe"
- "stop" → "stopp"

## Project Structure
```
simple-translator-en-gr/
├── project2.ipynb          # Main Jupyter notebook with translation implementation
└── README.md              # This file
```

## Model Architecture
The translation model implements:
- **Text Preprocessing**: Normalization and cleaning of input text
- **Vocabulary Building**: Creation of word mappings between languages
- **Sequence Processing**: Handling of variable-length text sequences
- **Translation Logic**: Core translation algorithm implementation

## Data Processing
The model includes several preprocessing steps:
- Text normalization using Unicode standards
- Regular expression-based cleaning
- Vocabulary extraction and mapping
- Sequence padding and truncation

## Limitations
- **Limited Vocabulary**: The model works with a basic vocabulary set
- **Simple Translations**: Focuses on word-level and short phrase translations
- **Educational Purpose**: Designed for learning rather than production use
- **Unidirectional**: Primarily German to English translation

## Future Improvements
- Expand vocabulary coverage
- Implement bidirectional translation
- Add support for longer sentences
- Integrate more sophisticated NLP models
- Include evaluation metrics

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Educational Value
This project is ideal for:
- Learning basic NLP concepts
- Understanding machine translation fundamentals
- Exploring sequence-to-sequence models
- Practicing Python for NLP applications

## License
This project is open-source and available for educational use.

## Contact
For questions or suggestions, please contact Mohamed-Rag through GitHub.

## Acknowledgments
This project serves as an educational implementation of machine translation concepts and is intended for learning purposes in the field of Natural Language Processing.

