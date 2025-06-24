/opt/homebrew/bin/python3.12 -m venv .acm

source .acm/bin/activate

pip install -r requirements.txt


Create the llama stack server set up from instructions here - https://github.com/opendatahub-io/llama-stack-k8s-operator


streamlit run src/policy_interface.py