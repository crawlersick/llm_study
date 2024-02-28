python -m venv llm_venv
source llm_venv/bin/activate

pip install ipykernel
jupyter kernelspec uninstall llm_venv
python -m ipykernel install --user --name=llm_venv

pip install transformers torch

i can run jupyter-lab now...
