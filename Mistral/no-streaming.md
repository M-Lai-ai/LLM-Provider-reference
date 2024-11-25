
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
  "stream": false
}'
```


```bash
{"id":"b5899875951449e9a2997246a3a54d21","object":"chat.completion","created":1732548590,"model":"mistral-large-latest","choices":[{"index":0,"message":{"role":"assistant","content":"Coca-Cola, often referred to as Coke, is a carbonated soft drink produced by The Coca-Cola Company. It was invented in the late 19th century by John Stith Pemberton and was first introduced in 1886. Here are some key points about Coca-Cola:\n\n1. **Ingredients**: The exact formula for Coca-Cola is a closely guarded trade secret. However, it","tool_calls":null},"finish_reason":"length"}],"usage":{"prompt_tokens":34,"total_tokens":134,"completion_tokens":100}}
```
