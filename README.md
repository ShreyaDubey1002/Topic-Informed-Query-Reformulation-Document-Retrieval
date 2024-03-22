# Topic-Informed-Query-Reformulation-Document-Retrieval

We have developed two models, one where the query paraphrasing is done by performing topic-modeling for query reformulation and the other uses a pre-trained Sentence BERT model. Both the models are learning to rank models where few documents are retrieved from a large collection using the BM25 retrieval model and then the retrieved documents are passed to a BERT model which is trained using the topic-based and paraphrased queries respectively. We evaluate and compare both models on different metrics including MAP and NDCG.
