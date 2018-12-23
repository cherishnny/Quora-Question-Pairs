### is that a duplicate quora question

all the code for the article https://www.linkedin.com/pulse/duplicate-quora-question-abhishek-thakur will be available here..

How To 
1. Install Required Libraries

```python
pip install pandas
pip install numpy
pip install scikit-learn
pip install nltk
pip install tqdm
pip install keras
pip install tensorflow
pip install pyemd
pip install fuzzywuzzy
pip install python-levenshtein
pip install --upgrade gensim
```
2. Download Required Language libraries

```python
mkdir data
cd data
wget http://www-nlp.stanford.edu/data/glove.840B.300d.zip
unzip glove.840B.300d.zip
rm glove.840B.300d.zip
wget http://qim.ec.quoracdn.net/quora_duplicate_questions.tsv
wget https://s3.amazonaws.com/dl4j-distribution/GoogleNews-vectors-negative300.bin.gz
sudo python -m nltk.downloader stopwords
cd ..
```

3. Run

```python
python feature_engineering.py
python deepnet.py
```
