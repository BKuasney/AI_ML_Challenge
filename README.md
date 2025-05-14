# AI_ML_Challenge

To execute the code you just need to download the file and put right on the data is.
Example:

- AI_TEST_FOLDER
    - DATA
        - SUB1
          - ADLS
          - FALSS
          - NEAR FALLS
    - CODE
 
All the packages and all you need are inside the jupyter notebook, including the install.

On a production environment the code would be more structured and not into a Jupyter Notebook (unless we are deploying AWS Sagemaker into production)
Also, on a production enviroment we would have the requirements.txt, docker, and all the functions separated to the main workflow.
And, of course, we would not train the model into production, we would only use the pickle file to predict the incoming information.
