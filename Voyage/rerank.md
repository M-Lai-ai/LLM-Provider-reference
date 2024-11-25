```shell
curl --request POST \
     --url https://api.voyageai.com/v1/rerank \
     --header "Authorization: Bearer $VOYAGE_API_KEY" \
     --header "content-type: application/json" \
     --data '{
       "query": "Find the most relevant document",
       "documents": [
         "This is document A.",
         "This is document B."
       ],
       "model": "rerank-2",
       "top_k": 1,
       "return_documents": true
     }'
```

```shell
{"object":"list","data":[{"relevance_score":0.431640625,"index":1,"document":"This is document B."}],"model":"rerank-2","usage":{"total_tokens":14}}
```
