# Project title

## Project description
Describe your project goals, data sources, and usage here.

## Data sources
List and describe the data sources used.

## Usage
Provide instructions for running the project.

## dvc (if applicable)
Include details about DVC setup if you choose to use it.

## Setting Up Your Environment

## Using Conda
1. Make sure you have Conda installed.
2. Create a new environment using `requirements.yaml`:
    ```
   conda env create -f requirements.yaml
   ```
3. Activate the environment:
    ```
    conda activate myenv
    ```

## Using pip
1. Make sure you have Python and pip installed.
2. (Optional) Create and activate a virtual environment:
- On macOS/Linux:
    ```
   python -m venv venv
   source venv/bin/activate
   ```
- On Windows:
    ```
   python -m venv venv
   venv\Scripts\activate
   ``` 
- Install dependencies using requirements.txt:
    ```
   pip install -r requirements.txt
   ```


## Directory structure
```
C:.
│   .gitignore
│   LICENSE
│   pytest.ini
│   README.md
│   requirements.txt
│
├───configs
│       config_settings.yaml
│
├───data
│   ├───raw
│   └───processed
│
├───docs
│
├───results
│   ├───figures
│   ├───logs
│   ├───models
│   ├───reports
│   └───tables
│
├───scripts
│
├───src
│   ├───data_processing
│   ├───feature_engineering
│   ├───interpretation
│   ├───modeling
│   └───utils
│
└───tests
```