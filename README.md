# Fetching-emails-and-adding-to-elasticsearch
## Dependencies Installation
- Run `pip install elasticsearch` in your command prompt to install elasticsearch python package.
- Run `pip install python-imap` to install imaplib package.
- If you haven't installed Jupyter notebook yet, Run the following command : `pip install jupyter`.
- Go to this link https://www.elastic.co/downloads/elasticsearch to download and unzip elastic search.
### To run Elasticsearch:
- go to the unzipped file location and open commandprompt or powershell 
- Run `bin/elasticsearch` (or `bin\elasticsearch.bat` on Windows)
- Run curl http://localhost:9200/ (or Invoke-RestMethod http://localhost:9200 with PowerShell)
## How to Run the Code
- Open Command prompt at the location where you've unziped the code and type `jupyter notebook`
- Now select the `.ipynb` file and open it.
- Open the credentials.py and place your Email id and Password in the respective places.
- Now run the Kernels in order one by one.
