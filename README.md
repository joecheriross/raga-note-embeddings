- Note-embeddings learned for 144 Hindustani ragas with bidirectional LSTM based approach. Similarity between the note-embeddings gives the similarity between the corresponding ragas.  
- The embeddings stored as numpy arrays are saved into files using Python Pickle. Files are in Python pickle format. Embedding for a raga can be retrieved from the corresponding file using the following code 

~~~~ python
import cPickle
path= "<path to embedding file *.vec>"
emb = cPickle.load(fp)
~~~~
