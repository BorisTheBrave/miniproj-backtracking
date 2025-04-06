# Installation
Needs the custom transformer lens from here: https://github.com/AIRI-Institute/SAE-Reasoning/tree/main/TransformerLens

(download it, navigate to directory, then `pip install -e .`)

Then `pip install torch transformers scikit-learn` and run `main.ipynb`

Note that `get_actv_and_class_int` is quite slow. You are recommended to run it once, then re-use the 8GB activations that is saves.