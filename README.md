# Fitbit Analytics

Exploring Fitbit API for customized analytics

:open_file_folder: Repo Organization
--------------------------------

    ├── src                
    │   ├── plotutils.py                                     <-- plotting functions
    │   ├── generate_tokens.py                               <-- generates access and refresh tokens in data/   
    │   └── ...
    │     
    ├── notebooks          
    │   ├── hn-query-sleep-data.ipynb                        <-- demo of how to query sleep data   
    │   └── ...
    │    
    ├── data                                                 <-- directory for storing small data
    │   ├── access_token.txt                                 <-- generated by /src/generate_tokens.py      
    │   ├── refresh_token.txt                                <-- generated by /src/generate_tokens.py      
    │   └── ...                                          
    │
    ├── Makefile                                             <- un/install environment 
    ├── requirements.txt                                     <- List of python packages required     
    ├── README.md
    └── .gitignore  
