## 50,000 IMDB movie reviews, collected by Andrew Maas from Stanford Univ.

Binary classification: reviews are classified into positive (1) and negative (0) groups. <br>
Being positive is defined by a rating score >= 6, otherwise it's negative.<br><br>

Both training text and test text are labeled, both are balanced data sets.<br>
25,000 in training data, ~50% positive.<br>
25,000 in test data, ~50% postive.<br><br>

**Note**:
labels and text are separated by special character '||', if you use pandas to read in the file, you can do:<br>
text_train = pd.read_csv('training_text', sep='\\|\\|', engine='python', names=['score','text'])
