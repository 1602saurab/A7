Step-1 
We will create a virtual environment because we want to install different-different packages or dependencies that will isolate from local system . 

step-2 
We will create a file 'requirements.txt' in which we will store our all packages that is install for run our application . 
streamlit ----> for ui 
google-generativeai ---> for google models 
python-dotenv  ---> for secure api keys 


open the terminal and write 
pip install -r Requirements.txt 

using this command , we will install all the packages that is present in this Requirements.txt file . 


step-3 
We will create a file '.env' in which we will store our all api keys.
We will create this .env file because we donot want that our personal credentials will go or expose in the production . 

step-4 
We will create a file 'app.py' in which  we will create a function that will take our query as an argument and then it will send it to google-generative-model and then our google-generative-model using our gemini-api-key and send response to the user . 
Here we will use streamlit for showing result and where user will put their inputs . 

Open the terminal and write 

streamlit run app.py 


Everythinh is ok 