# What is this repo about

This is a CNN based text classifier using spacy that can classify your Myers–Briggs personality type (e.g. INTJ, ENFP) based on text or post you have written.  

# How to use it 

You can train the model using the jupyter notebook provided or load from a pre-trained model. 

# Loading from pre-trained model

```
import spacy
text = <Ur text>
nlp = spacy.load("./mbti model")
doc = nlp(text)
print(doc.cats)
 ```

