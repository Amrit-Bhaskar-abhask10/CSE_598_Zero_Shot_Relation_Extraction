# CSE_598_Zero_Shot_Relation_Extraction
Dwonload below files in the root directory:

'''https://drive.google.com/drive/folders/1dLA4B33LW9BfzWvUaoxpaLcb1syyx2Zr?usp=sharing'''


'''https://drive.google.com/drive/folders/1qJ4Z4rTEKdm3jgbm_K1ojMs03qVQ38Qm?usp=sharing'''

1. Set up the environment with the following command:
    conda env create -f environment.yml
2. To run the Zero shot relation extraction task, run the following command:
    python main.py
3. This will output the performance metric to the command line and store the best model in a new folder "saved_models" in the root directory.

Data preprocessing steps used:
1. Run 1_Find_existing_emerging_relation.ipynb to find the emerging and existing intents used in this task.
2. Run 2_Format_data.ipynb to format the data according to code input.
3. Run 3_Find_entity_pos.ipynb to find the positional index of each entity used in a sentence.