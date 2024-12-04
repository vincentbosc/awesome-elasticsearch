# awesome-elasticsearch
Awesome Elasticsearch - A classified list of useful links to blog-articles/documentations.
Inspired by the great [awesome-search repo](https://github.com/frutik/awesome-search), but focused on Elasticsearch.

## Topics

* [Vector Search](#vector-search)
  * Quantization
* [NLP Tasks](#nlp-tasks)
  * NER
  * 

# Search

* [Search tutorial](https://www.elastic.co/search-labs/tutorials/search-tutorial/welcome) - app in Flask

## Retrievers
* [Retrievers Introduction](https://www.elastic.co/search-labs/blog/elasticsearch-retrievers-ga-8.16.0) - blog
* [Retrievers using semantic reranking](https://www.elastic.co/search-labs/blog/semantic-reranking-with-retrievers) - blog

## Vector Search

### HSNW
* [Multi HSNW Graph Vector Search](https://www.elastic.co/search-labs/blog/multi-graph-vector-search) - blog
* [Elastic Meetup - How HSNW works](https://www.youtube.com/watch?v=ly_COu_sHtI) - video (in French)

### Quantization
* [Scalar quantization](https://www.elastic.co/search-labs/blog/evaluating-scalar-quantization) - blog
* [RaBitQ binary quantization](https://www.elastic.co/search-labs/blog/rabitq-explainer-101) - blog
* [BBQ quantization vs Product Quantization](https://www.elastic.co/search-labs/blog/bit-vectors-elasticsearch-bbq-vs-pq) - blog

## ELSER

* [App which compares ELSER and BM25](https://github.com/elastic/elasticsearch-labs/tree/main/example-apps/relevance-workbench) - app in Flask and React (github)

## Rerankers

### Semantic rerankers
* [Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/semantic-reranking.html#semantic-reranking-in-es)
* [What is a semantic reranker?](https://www.elastic.co/search-labs/blog/elastic-semantic-reranker-part-1) - blog
* [How to - Use a reranker from Hugging Face](https://www.elastic.co/search-labs/blog/reranking-elasticsearch-hugging-face) - blog
 
### LTR
* [Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/learning-to-rank.html)
* [LTR Introduction](https://www.elastic.co/search-labs/blog/elasticsearch-learning-to-rank-introduction) - blog
* [Personalized search with LTR](https://www.elastic.co/search-labs/blog/personalized-search-elasticsearch-ltr) - blog

## RAG
* [Rag demo](https://esre-openai-sample-app.prod-3.eden.elastic.dev/) - eden demo (internal)
* [Elastic Chat RAG App](https://github.com/elastic/elasticsearch-labs/tree/main/example-apps/chatbot-rag-app) - app in Flask (github)
* [Rag using Graph](https://www.youtube.com/watch?v=_oQzsOu2ok4) - video (in French)

## NLP Tasks

