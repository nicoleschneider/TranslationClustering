# Cross Lingual Text Clustering in a Large System
Sample NewsStand data for the Cross Lingual Test Clustering in a Large System paper submission

# Instructions for use

Download the repo: 

    git clone https://anonymous.4open.science/r/cross_lingual_text_clustering_in_a_large_system-3A27.git
    
Navigate to the directory, then create a virtual environment: 

    python3 -m venv clingtext_env
  
Activate the environment

    source clingtext_env/bin/activate

Install required dependencies: 

    pip3 install -r requirements.txt
  
You can then load the CSV into a dataframe using some python code like: 

    import pandas as pd
    df = pd.read_csv('sample_newsstand_dataset.csv')
    print(df)
  
Or launch it in a jupyter notebook (recommended for exploring the dataframes) using: 

    jupyter-lab
  
And using the same code as above in seperate cells the notebook environment: 

    import pandas as pd
   
    df = pd.read_csv('sample_newsstand_dataset.csv')
   
    df
