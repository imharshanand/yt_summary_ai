Commands to create the environment 'llm_env':
1. Create the conda environment:
   conda create -n llm_env python=3.8
2. Activate the conda environment:
   conda activate llm_env
3. Install conda packages:
   conda env update --file llm_env_environment.yml --prune
4. Install pip packages:
   pip install -r llm_env_requirements.txt
