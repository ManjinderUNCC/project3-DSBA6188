# project3-DSBA6188

Write Up:
https://github.com/ManjinderUNCC/project3-DSBA6188/blob/main/Project%20Milestone%203-WriteUp.pdf

Terminal Code:
https://github.com/ManjinderUNCC/project3-DSBA6188/blob/main/Project3TerminalCode.txt

## First Step:
https://github.com/ManjinderUNCC/project3-DSBA6188/blob/main/firstStep-format.py
<br> After getting those 200 labels, I had to format them in a way that spaCy could read them. I want
spaCy to read my annotations so I can train my model. 

##### 200 trained dataset
https://github.com/ManjinderUNCC/project3-DSBA6188/blob/main/train200a.jsonl

## First Step Output:
https://github.com/ManjinderUNCC/project3-DSBA6188/blob/main/firstStep_file.jsonl

## Second Step:
https://github.com/ManjinderUNCC/project3-DSBA6188/blob/main/secondStep-score.py
<br> Trained a text classification model

## Second Step Output:
https://github.com/ManjinderUNCC/project3-DSBA6188/tree/main/my_trained_model

## Third Step:
https://github.com/ManjinderUNCC/project3-DSBA6188/blob/main/thirdStep-label.py
<br> Pre-trained classification model using spaCy and and through each JSONL line applying the model to predict the labels

## Third Step Output:
https://github.com/ManjinderUNCC/project3-DSBA6188/blob/main/thirdStep_file.jsonl

## Final Step:
Transform the classified data to another format based on the threshold.
 
## Final Step Output: (Weakly Label Data)
https://github.com/ManjinderUNCC/project3-DSBA6188/blob/main/finalStep-formatLabel.py

## Number 5 (Reproducible Inference Examples)
https://github.com/ManjinderUNCC/project3-DSBA6188/blob/main/five_examples_annotated.ipynb
<br> JSONL FIle: https://github.com/ManjinderUNCC/project3-DSBA6188/blob/main/five_examples_annotated5.jsonl

