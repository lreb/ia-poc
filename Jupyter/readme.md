python -m venv jupyter_env

jupyter_env\Scripts\activate

pip install jupyter

jupyter --version

jupyter notebook

---

pip install transformers torch

transformers: For loading pre-trained LLMs like GPT-2 or Mistral.
torch: PyTorch, required for running models efficiently.

If you want to use a specific model like LLaMA or GPT4All for local execution, you can also install:bash

pip install gpt4all llama-cpp-python

# Practical Notes

Files such as .csv, .h5, and .pkl are ignored because they are typically datasets or trained models, not source code.

The outputs/, results/, figures/, and plots/ folders are for artifacts generated during notebooks.