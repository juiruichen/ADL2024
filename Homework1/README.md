# Chinese Extractive Question Answering

### Data
Data can be downloaded on [Kaggle](https://www.kaggle.com/competitions/ntu-adl-2024-hw-1-chinese-extractive-qa#).

### Problems
- problem 1
    ```
    ImportError: This example requires a source install from HuggingFace Transformers (see `https://huggingface.co/docs/transformers/installation#install-from-source`), but the version found is 4.44.2.
    Check out https://github.com/huggingface/transformers/tree/main/examples#important-note for the examples corresponding to other versions of HuggingFace Transformers.
    ```
    solution:
    ```
    pip install git+https://github.com/huggingface/transformers.git
    ```