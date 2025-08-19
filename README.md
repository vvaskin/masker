## Descrioption

### This is the repo for the web tool for labeling datasets with binary masks

## Installation
### Make Sure to use a chrome browser
    # create a new environment
    conda env create -f environment.yml

    # activate environment
    conda activate masker

    # run app
    python app.py

### you should see the following printed on the bash
    Using device: cpu
    Using device: cpu
    * Serving Flask app 'app'
    * Debug mode: on
    WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
    * Running on all addresses (0.0.0.0)
    * Running on http://127.0.0.1:8000
    * Running on http://10.68.152.106:8000
  
control clicking on the http://127.0.0.1:8000 should start a tab in the browser.<br>
You can change the port in the app.py


    

