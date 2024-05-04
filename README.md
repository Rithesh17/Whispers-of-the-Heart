# Whispers of the Heart
## About the project

**_A daily reflection journalling app that revolutionizes therapy by seamlessly integrating AI analysis with professional therapy practices._**

Journaling serves as a vital tool for individuals to reflect on their thoughts, feelings, and experiences, fostering self-awareness and personal growth. Therapists often utilize journals as a means to gain deeper insights into their clients' inner worlds, leveraging the safe space created by journals for free expression. However, sharing journal entries can be daunting, and not all individuals feel comfortable doing so, even with their therapists.

Our app addresses this challenge by providing users with a safe and non-judgmental platform to express themselves openly. Unlike traditional therapy, our app does not aim to replace the therapeutic relationship but rather complements it by acting as a discreet observer. Respecting the expertise of therapists and psychoanalysts, the app functions as a "wallflower," refraining from directly interacting with the journal writer or altering the purpose of journaling. It does not make judgments or diagnoses but instead analyzes users' entries, including journal entries, poems, and artwork, using generative AI to interpret their thoughts, feelings, and moods.

Through this analysis, the app identifies and highlights key emotions and thought patterns present in the user's input, assigning confidence and intensity scores to each mental state. The app then tracks the user's emotions and thoughts over time, providing valuable observations that contribute to a comprehensive understanding of their mental well-being.

The analysis generated by the app comprises five main components:

1. **Emotions**: A curated list of at least three emotions observed in the user's input, offering insight into their emotional state.
2. **Possible Thought Patterns**: A collection of three to four prominent thought patterns identified in the input, accompanied by brief explanations to deepen understanding.
3. **Mental Well-being Scores**: A comprehensive table scoring 10 to 15 mental states based on the app's confidence in the user's feelings and the intensity of the emotions expressed. This table serves as a valuable tool for therapists to gauge the user's mental well-being.
4. **Summary of the Day**: A concise summary of the user's input, providing therapists with pertinent insights into the user's mental state and facilitating informed decision-making.
5. **Explanation**: An essential component of the analysis where the app articulates its reasoning process, breaking down its interpretation step by step. This includes providing specific examples, clarifying assumptions made during analysis, and offering insights into the model's decision-making process.

Overall, our app acts as a supportive companion in the journey of self-discovery and personal development, providing users with valuable insights while respecting their privacy and autonomy. By offering a nuanced analysis of users' input, the app empowers therapists to provide more personalized and effective therapeutic interventions.

## For the Google AI Hackathon

Our main submission for the Hackathon is the `src/Whispers_of_the_Heart_Google_AI_Hackathon.ipynb` notebook. You can run each cell in the notebook and see the output.
We recommend running the notebook in Google Colab.
Please make sure you have the Google API Key for the project. If using Google Colab, please add the API key as a Secret, with the name `GOOGLE_API_KEY` and the key as the value.

If you want the experience of the app, you can run the Python file `src/whispers_of_the_heart.py`. But in this case, you will have to add the API key as an input to the prompt that follows.

## Preparation

First, we will cover the tools we recommend you to run this project.
If you prefer other tools you may use them, but we may not be able to help you if you encounter difficulties.

### Supported Setups

Below are the supported setups for the project.
Other setups can work, but as we mentioned, we cannot guarantee its working.

### Python

Python 3.12  is recommended for this project.
If you do not have it, please find the installation of Python 3.12 [here](https://www.python.org/downloads/).
We also recommend you to use [pip](https://pip.pypa.io/en/stable/installation/) to install Python packages.

To check your already installed Python version, use:
```sh
python3 -V
```

### Requirements

We defined all the dependencies using the standard `requirements.txt` file. You will find this file in the same directory as this readme. You can install all the requirements at the same time using this file.

We recommend you use pip to install packages. 
To install the requirements in requirements.txt with pip, you can use:
```sh
pip3 install -r requirements.txt
```

## How to Use

1. **Clone This Repository**
    
    Clone this repository to your local system.

    ```sh
    git clone https://github.com/Rithesh17/Whispers-of-the-Heart.git
    ```

2. **Start your Virtual Environment (optional but recommended)**
    If you want to run this project in a virtual environment, thisis a good time to start it.

3. **Installing Requirements**
    We need to install the packages for this project.
    We defined all the dependencies in this course using the [standard `requirements.txt` file](https://pip.pypa.io/en/stable/reference/requirements-file-format/).
    You will find this file in the same directory as this readme.
    You can install all the requirements at the same time using this file.

    We recommend you use [pip](https://pip.pypa.io/en/stable/) to install packages.
    You are free to choose whatever system works best for you (like [Conda](https://docs.conda.io/en/latest/)).

    To install the requirements in `requirements.txt` with pip, you can use:
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the code**
    We have the code for the project in two formats: The `.py` format and the `.ipynb` format.
    
    Head inside the `src` directory:
    ```sh
    cd src
    ```

    - **To run the .py file:** 
        Run the command
        ```sh
        python .\whispers_of_the_heart.py
        ```
    
    - **To run the .ipynb file:** 
        We recommend you running the IPython notebook file in Google Colab.