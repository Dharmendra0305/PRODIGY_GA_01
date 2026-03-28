# Text Generation with GPT-2 

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📖 Overview
This project involves fine-tuning the pre-trained GPT-2 transformer model on a custom dataset to generate coherent, contextually relevant text. It includes a user-friendly web interface built with Gradio, allowing users to interact with the model and adjust generation parameters in real time. 

*Developed as part of my Generative AI Internship at SkillCraft Technology.*

* Here’s the main interface of the Text Generation with GPT-2:

![Main UI](https://github.com/Dharmendra0305/PRODIGY_GA_01/blob/70fff3931c31a7bc324622c8b6be6044e17b1973/1.png)

## ✨ Features
* **Custom Fine-Tuning:** Adapts OpenAI's base GPT-2 model to mimic the style and structure of specific training data.
* **Interactive UI:** A Gradio-based web app for seamless text generation.
* **Adjustable Parameters:** Granular control over output creativity (Temperature) and verbosity (Max Length).
* **GPU-Optimised:** Training scripts designed to leverage PyTorch and CUDA for efficient processing.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Machine Learning:** PyTorch, Hugging Face `transformers`, `datasets`
* **Interface:** Gradio
* **Environment:** Google Colab / Jupyter Notebook

## 🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Dharmendra0305/PRODIGY_GA_01.git](https://github.com/Dharmendra0305/PRODIGY_GA_01.git)

2. **Install required dependencies:**
   ```bash
   pip install transformers datasets torch gradio

## 💻 Usage

Since this project was developed in Google Colab, you can run it locally using Jupyter environments (like Jupyter Notebook, JupyterLab, or VS Code):

1. **Download Files:** Download the `Text_Generation_with_GPT_2.ipynb` notebook and your trained `custom-gpt2-final` model folder from Colab. 
2. **Organise Directory:** Place the unzipped `custom-gpt2-final` folder in the same local directory as your notebook.
3. **Open and Install:** Open the notebook. In the first cell, ensure your local environment has the required libraries:
   ```python
   !pip install transformers datasets torch gradio
4. Run the Application: Execute all cells in the notebook. The Gradio web interface will launch directly inside your notebook output, or you can click the    generated link to open it in your browser.

* Example of Text Generation:

![Conversion Example](https://github.com/Dharmendra0305/PRODIGY_GA_01/blob/70fff3931c31a7bc324622c8b6be6044e17b1973/2.png)

## 🤝 Contribution Guidelines
- Contributions are welcome! If you'd like to improve this project:
  1. Fork the repository.
  2. Create a new branch (git checkout -b feature/improvement).
  3. Commit your changes (git commit -m 'Add some feature').
  4. Push to the branch (git push origin feature/improvement).
  5. Open a Pull Request.

 ## 📄 License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
