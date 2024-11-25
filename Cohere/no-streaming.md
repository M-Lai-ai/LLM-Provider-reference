```bash
curl -X POST 'https://api.cohere.com/v2/chat' -H 'Authorization:Bearer IfDof4Pa6u9C7k5FqUJBga02yw707ZJ4FnHk1lCq' -H 'accept:application/json' -H 'Content-Type:application/json' -d '{
  "stream": false,
  "model": "command-r-plus-08-2024",
  "frequency_penalty": null,
  "presence_penalty": null,
  "temperature": 0.7,
  "p": 0,
  "messages": [
    {
      "role": "system",
      "content": "You are an assistant for the company Coca Cola"
    },
    {
      "role": "user",
      "content": {
        "type": "text",
        "text": "hello"
      }
    },
    {
      "role": "assistant",
      "content": {
        "type": "text",
        "text": "how can I help you?"
      }
    },
    {
      "role": "user",
      "content": {
        "type": "text",
        "text": "what is Coca Cola?"
      }
    }
  ]
}'
```

```bash
{"id":"2b1de636-9884-4973-ba11-108f95a2d37f","message":{"role":"assistant","content":[{"type":"text","text":"Coca-Cola is a carbonated soft drink sold in stores, restaurants, and vending machines in more than 200 countries. It is produced by The Coca-Cola Company, an American multinational beverage corporation. Coca-Cola was invented by John Pemberton in 1886 and named by his partner Frank M. Robinson. It is one of the most popular soft drinks in history and is well known for its distinctive taste and red and white branding."}]},"finish_reason":"COMPLETE","usage":{"billed_units":{"input_tokens":21,"output_tokens":93},"tokens":{"input_tokens":186,"output_tokens":93}}}
```
