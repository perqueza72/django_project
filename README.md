# Install virtual env
virtualenv venv --python=python3
python -m pip install --user virtualenv
source venv/bin/activate

#Para activar las variables de estado. 
source secret.env 

# Install requirenments
pip install -r requirements.txt 