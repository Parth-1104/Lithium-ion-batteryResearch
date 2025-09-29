conda create -n research_env python=3.11 -y

conda activate research_env


conda install jupyter -y
pip install jupyterlab notebook ipykernel



python -m ipykernel install --user --name=research_env --display-name "Python (research_env)"
