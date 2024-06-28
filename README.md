# DSPy

**Steps to run the code:**
1. Create a virtual environment with python 3.10.13
`conda create --name myenv python=3.10.13`
2. Activate in your new virtual environment
`conda activate myenv`
3. Install the required requirements
`pip install -r requirements.txt`
4. Create a folder called `/env` and add a file with the following:
    - var.env
    ```
    OPENAI_KEY=YOUR_OPENAI_KEY
    HF_TOKEN=YOUR_HF_TOKEN
    ```
5. Run in the notebook `dspy.ipynb` 

## Folder Structure:
------------

    ├── DSPY
    │
    ├──────── env                                        <- env files
    │
    │──────── dspy.ipynb                                 <- notebook
    │
    └──────── requirements.txt                           <- package versions
--------
