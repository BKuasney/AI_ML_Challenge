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

In a production environment, the code would be more structured and not written in a Jupyter Notebook (unless we're deploying to AWS SageMaker, which supports notebooks in production).
Additionally, a proper production setup would include a requirements.txt file, Docker configuration, and a clear separation of functions from the main workflow.
And of course, we wouldn't train the model in production — we would simply load the pre-trained model (e.g., from a .pkl file) and use it to make predictions on incoming data.

PS:
At the end of the file, you'll find my considerations, conclusions, and what I would have done with more time.
