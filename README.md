
### dependencies ###
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt

### start ###
uvicorn unilabs:app --host 0.0.0.0
