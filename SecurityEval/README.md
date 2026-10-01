---
language:
- en
- code
size_categories:
- n<1K
task_categories:
- code-generation
tags:
- security
- code-generation
---
# Dataset Card for SecurityEval


This dataset is from the paper titled **SecurityEval Dataset: Mining Vulnerability Examples to Evaluate Machine Learning-Based Code Generation Techniques**. 
The project is accepted for The first edition of the International Workshop on Mining Software Repositories Applications for Privacy and Security (MSR4P&S '22). 
The paper describes the dataset for evaluating machine learning-based code generation output and the application of the dataset to the code generation tools.



## Dataset Details

### Dataset Description


- **Curated by:** Mohammed Latif Siddiq & Joanna C. S. Santos
- **Language(s):** Python

### Dataset Sources


- **Repository:** https://github.com/s2e-lab/SecurityEval
- **Paper:**
"SecurityEval Dataset: Mining Vulnerability Examples to Evaluate Machine Learning-Based Code Generation Techniques".
International Workshop on Mining Software Repositories Applications for Privacy and Security (MSR4P&S '22).
https://s2e-lab.github.io/preprints/msr4ps22-preprint.pdf



## Dataset Structure

- dataset.jsonl: dataset file in jsonl format. Every line contains a JSON object with the following fields:
  - `ID`: unique identifier of the sample.
  - `Prompt`: Prompt for the code generation model.
  - `Insecure_code`: code of the vulnerability example that may be generated from the prompt.


## Citation


**BibTeX:**

```
@inproceedings{siddiq2022seceval,
  author={Siddiq, Mohammed Latif and Santos, Joanna C. S. },
  booktitle={Proceedings of the 1st International Workshop on Mining Software Repositories Applications for Privacy and Security (MSR4P&S22)}, 
  title={SecurityEval Dataset: Mining Vulnerability Examples to Evaluate Machine Learning-Based Code Generation Techniques}, 
  year={2022},
  doi={10.1145/3549035.3561184}
}
 ```

**APA:**

Siddiq, M. L., & Santos, J. C. (2022, November). SecurityEval dataset: mining vulnerability examples to evaluate machine learning-based code generation techniques. In Proceedings of the 1st International Workshop on Mining Software Repositories Applications for Privacy and Security (pp. 29-33).