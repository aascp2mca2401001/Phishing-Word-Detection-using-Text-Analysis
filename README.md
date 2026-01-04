# Phishing-Word-Detection-using-Text-Analysis
This project aims to develop a machine learning model capable of detecting phishing messages or emails based on textual patterns and word usage. Phishing attacks are among the most common cyber threats, where attackers use persuasive or deceptive language to trick users into revealing sensitive information.

## How to Run

### Local Execution (VS Code)

1.  **Prerequisites**: Ensure you have Python installed (recommended version 3.8+).
2.  **Install Dependencies**:
    Open a terminal in the project directory and run:
    ```bash
    pip install -r requirements.txt
    ```
    *Note: If `pip` is not recognized, try `python -m pip install -r requirements.txt`.*
3.  **Open Notebook**:
    Open `Phishing_Detection_in_Google_Colab.ipynb` in VS Code.
4.  **Select Kernel**:
    Click on "Select Kernel" at the top right and choose your Python environment.
5.  **Run**:
    Execute the cells. The `!pip install` commands in the notebook have been commented out to prevent errors in the local environment.

### Google Colab Execution

1.  **Upload**: Upload the `Phishing_Detection_in_Google_Colab.ipynb` file to your Google Drive or open it directly in [Google Colab](https://colab.research.google.com/).
2.  **Enable Dependencies**:
    The notebook is configured for local execution by default (with package installation commented out). **You must uncomment the installation lines in the first code cell**:
    ```python
    !pip install wordcloud
    !pip install seaborn
    ```
3.  **Run**:
    Execute the cells. Colab environment comes with most other dependencies pre-installed.
