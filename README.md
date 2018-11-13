# Practical NLP

## SLIDES OF COURSES:

- [Introduction to NLP](http://www-connex.lip6.fr/~dias/nlp-intro.pdf)
- [NLP Deep Learning](http://www-connex.lip6.fr/~dias/nlp-deep.pdf)


## Instructions to get started (ON LINUX)

- Clone repository: `git clone git@github.com:cedias/practicalNLP.git`
- move in directory: `cd practicalNLP`
- download data: `cd dataset`then`chmod +x download.sh` and finally `./download.sh`
- start notebook: `cd ..` if you're still in the  `.../dataset` dir and `jupyter notebook`

## Instructions to get started (ON Windows)

- Clone or Download Repository
- Extract download file
- (Manually) download files listed in "dataset/source" file:

```
http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz
http://download.tensorflow.org/data/questions-words.txt
https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt
```

- Extract them if needed
- start notebook somehow

##  Install package directly within jupyter notebooks:

```python
import sys
!{sys.executable} -m pip install [--user] package
```
## Pre-trained embeddings:
can be found here -> https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing
