# Please download the model from https://drive.google.com/file/d/1oySAMZsQewBDTlUDbZz7RnhuS0P0VHAY/view?usp=sharing under ./checkpoints

This module generates question from facts or triples, which consists of Subject, Predicate and Object, and Direction, which is either forward or backward.

# For Training the model use the snippet below:

python run.py -epochs 20 -min 50 -datapath ./data/final -fold 1

# For Testing the model:

Run generateSuggestiveQuestion() function from question_generation.py which takes 4 inputs: Subject, Predicate, Object_List and Direction

# The Pretrained models should be saved in: 

./checkpoints


