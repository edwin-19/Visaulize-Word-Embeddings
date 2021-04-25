# Vis Word Embd
A repository to test out some code regarding how to visualize word embeddings of popular networks such as BERT and Word2Vec

NOTE: 
1) BERT Embeddings are best visualize in a 3D Space with all embeddings simultaneously, visualizing specifc ones is not enough
2) Probably need to write to tensorboard or maybe use plotly
3) Only word embedding and position embedding can be visualized with python but even that has its limits

Future Plans:
- If more time figure out how to probably visualize embeddings for transformers based model
- Probably need to look in to tensorboard for visualization, look for alternatives?

# TODO
- [x] Visualize bert position and token embeddings
- [x] Visualize bert sentence embeddings (Didnt really visualize that well probably need to use special embedding space, e.g 3D)
- [x] Using word2vec train a model with xgboost