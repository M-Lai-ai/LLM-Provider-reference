```bash
curl -X POST 'https://api.mistral.ai/v1/chat/completions' -H 'Content-Type:application/json' -H 'Accept:application/json' -H 'Authorization:Bearer $MISTRAL_API_KEY' -d '{
  "model": "mistral-large-latest",
  "messages": [
    {
      "role": "system",
      "content": "You are an assistant for the company Coca Cola "
    },
    {
      "role": "user",
      "content": "hello"
    },
    {
      "role": "assistant",
      "content": "hello how can I help you"
    },
    {
      "role": "user",
      "content": "what is Coca Cola"
    }
  ],
  "temperature": 0.7,
  "top_p": 1,
  "max_tokens": 100,
  "stream": true
}'
```


```bash
data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"role":"assistant","content":""},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"C"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"oca"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"-"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"Col"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"a"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":","},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" often"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" referred"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" to"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" as"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" C"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"oke"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":","},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" is"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" a"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" carbon"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"ated"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" soft"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" drink"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" manufactured"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" by"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" The"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" C"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"oca"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"-"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"Col"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"a"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" Company"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"."},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" It"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" was"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" invented"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" in"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" the"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" late"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" "},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"1"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"9"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"th"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" century"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" by"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" John"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" St"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"ith"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" P"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"ember"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"ton"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" and"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" was"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" first"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" introduced"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" in"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" "},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"1"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"8"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"8"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"6"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"."},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" The"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" drink"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" is"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" known"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" for"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" its"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" distinctive"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" taste"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":","},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" which"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" is"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" the"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" result"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" of"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" a"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" secret"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" formula"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" known"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" as"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" \""},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"Mer"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"ch"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"and"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"ise"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" "},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"7"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"X"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":".\""},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"\n"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"\n"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"C"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"oca"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"-"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"Col"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"a"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" is"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" one"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" of"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" the"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" most"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":" recogn"},"finish_reason":null}]}

data: {"id":"f798ebd5c41a45d88bb079635121cade","object":"chat.completion.chunk","created":1732548656,"model":"mistral-large-latest","choices":[{"index":0,"delta":{"content":"izable"},"finish_reason":"length"}],"usage":{"prompt_tokens":34,"total_tokens":134,"completion_tokens":100}}

data: [DONE]
```
