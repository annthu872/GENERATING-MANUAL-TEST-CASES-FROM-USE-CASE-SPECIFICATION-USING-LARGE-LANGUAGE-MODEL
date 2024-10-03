# GENERATING-MANUAL-TEST-CASES-FROM-USE-CASE-SPECIFICATION-USING-LARGE-LANGUAGE-MODEL

2. Description:
   This project is to introducing a propose that aims to automately create natural language acceptance test cases based on natural language use case specification using GPT-4.

3. Contents:
   DATASET: Includes all of dataset we have used in this project.
   SOURCE: Includes source code and file needed for running the project.
   DOC: Includes thesis's contents.

4. How to run this project:

- Open the SOURCE folder.
- Put your OpenAI's key.
- Run source code inside propose.ipynb.
- If you want to change save directory or using a new dataset, change path in block 23.
- Final output should be an excel files.

5. How to use this project:
   Any modifications should be done in propose.ipynb, here is the detail about which block contains important information:

- Block 22 includes all of the prompts we have used in this project, if you want to try another prompting techniques or make edition to the prompt, change here.
- Block 26 introduces how we preprocess the use case specification and create test scenarios. There are comments to tell which prompt we have used.
- Block 27 introduces how we generate test cases based on test scenario and the inputted use case scenarios. There are comments to tell which prompt we have used.
