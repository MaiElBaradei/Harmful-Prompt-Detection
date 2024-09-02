# Evaluating Language Models for Harmful Prompt Detection

## Overview

This project aims to evaluate and compare different language models in detecting harmful prompts using a dataset from the LLM-EvaluationHub. The goal is to implement and analyze at least two models to determine which one best identifies harmful content, focusing on various ethical categories such as Offensiveness, Unfairness and Bias, and Ethics and Morality.

## Project Structure

- **Data Exploration and Preprocessing:** Initial steps involve loading the dataset, exploring its contents, and preprocessing the data to ensure a balanced distribution across different ethical categories.
- **Model Implementation:** The project involves implementing multiple language models, fine-tuning them, and testing their ability to detect harmful content in the provided prompts.
- **Evaluation:** The models are evaluated based on their accuracy in detecting harmful prompts, with a focus on ethical correctness and fairness.

## Dataset

The dataset used in this project is sourced from the LLM-EvaluationHub and includes prompt texts categorized into different ethical labels. The key features of the dataset include:
- `PromptText`: The text of the prompt being analyzed.
- `BinaryResponse`: A binary response indicating the presence or absence of harmful content.
- `EthicalCategory`: The ethical category associated with the prompt.
- `CorrectLabel`: The correct label for the prompt, used for model training and evaluation.

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-repo-name/evaluating-language-models-harmful-prompt-detection.git
   cd evaluating-language-models-harmful-prompt-detection
   ```

2. **Install dependencies:**

   Ensure you have Python 3.8+ installed. Then, install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. **Download the dataset:**

   Place the dataset in the `data/` directory. If you are using the same dataset as in the project, name it `data.csv`.

4. **Run the notebook:**

   You can explore the project step-by-step by running the provided Jupyter notebook:

   ```bash
   jupyter notebook Evaluating_Language_Models_for_Harmful_Prompt_Detection.ipynb
   ```

## Usage

- **Data Exploration:** The notebook starts by loading and exploring the dataset, visualizing class distributions, and performing necessary preprocessing steps.
- **Model Training:** Follow the instructions in the notebook to implement and train the language models. You may modify the models or try different configurations as needed.
- **Evaluation:** After training, the models are evaluated for their effectiveness in detecting harmful prompts. Results are visualized and compared to identify the best-performing model.

## Results

The results of the model evaluation will include:
- **Accuracy Metrics:** Performance metrics like accuracy, precision, recall, and F1 score for each model.
- **Visualization:** Graphical representation of model performance across different ethical categories.

## Contributing

Contributions to this project are welcome! Feel free to submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Would you like any modifications or additional details included in this README?
