Information Extraction: Resume Analysis 📑💼
===
Abstract: This project highlights the development and evaluation of a resume analysis system, particularly in information extraction. The resume analysis system utilizes one of the Natural Language Processing (NLP) tasks, which is Named Entity Recognition (NER), to automatically extract and categorize information from resumes, such as personal information, educational background, work experience, and skills. The aim is to facilitate human resources processes by automatically analyzing different sections of resumes. 

## Project Information
- Title:  `Resume Analysis: Information Extraction `
- Authors:  `Rasha Ashawa`,`Salwa Shamma`,`Sana Shamma`, `Nafisah Shams`

## Dependence
- python
- spacy
- PyMuPDF

## Dataset Preparation
| Dataset | Download |
| ---     | ---   |
| train dataset | [download](https://github.com/laxmimerit/CV-Parsing-using-Spacy-3) |

## Installation
1. Clone the repository
```
git clone https://github.com/SalwaSh/AI312-Resume-Analysis-Information-Extraction.git
```
2. Install the required dependencies from requirements.txt

## Directory Hierarchy
```
|—— .ipynb_checkpoints
|    |—— NLP Resume Parsing-checkpoint.ipynb
|—— data
|    |—— test data
|        |—— Alice Clark CV.pdf
|        |—— Rajesh Kumar CV ByChatGPT.pdf
|        |—— Smith Resume.pdf
|    |—— train data
|        |—— train_data.pkl
|—— NLP Resume Parsing.ipynb
|—— nlp_model
|    |—— meta.json
|    |—— ner
|        |—— cfg
|        |—— model
|        |—— moves
|    |—— tokenizer
|    |—— vocab
|        |—— key2row
|        |—— lookups.bin
|        |—— strings.json
|        |—— vectors
|—— README.md
```

## Usage

To analyze a resume using the resume analysis module, follow these steps:

1. Prepare your resume or CV document in a supported format (e.g., PDF).
2. Pass the document through the resume analysis module.
3. View the generated analysis report, which includes keyword highlights, identified skills, educational background, work experience, and others.

## ScreenShots 📷

some of the expected output from our model:

![image](https://github.com/SalwaSh/AI312-Resume-Analysis-Information-Extraction/assets/97047182/87cc7ead-8f1d-4d26-8c3a-6b08e85e70dd)

![image](https://github.com/SalwaSh/AI312-Resume-Analysis-Information-Extraction/assets/97047182/f6e46afc-9f04-49a9-baa0-7da277749f6b)


## Code Details
### Tested Platform
- software
  ```
  OS: Windows 11 64-bit 
  Python: 3.9.12 (anaconda)
  ```
- hardware
  ```
  CPU: Intel 7-10750H
  ```

## References
- [source code](https://github.com/laxmimerit/CV-Parsing-using-Spacy-3)

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. When contributing to this project, please follow the code of conduct.

