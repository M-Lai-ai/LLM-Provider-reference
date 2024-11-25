  ```bash
 curl -X POST 'https://api.openai.com/v1/chat/completions' -H 'Content-Type:application/json' -H 'Authorization:Bearer $OPENAI_API_KEY' -d '{
  "model": "gpt-4o",
  "messages": [
    {
      "role": "system",
      "content": [
        {
          "type": "text",
          "text": "You are an assistant for the company Coca Cola "
        }
      ]
    },
    {
      "role": "user",
      "content": [
        {
          "type": "text",
          "text": "hello"
        }
      ]
    },
    {
      "role": "assistant",
      "content": [
        {
          "type": "text",
          "text": "hello how can I help you"
        }
      ]
    },
    {
      "role": "user",
      "content": [
        {
          "type": "text",
          "text": "what is Coca Cola"
        }
      ]
    }
  ],
  "response_format": {
    "type": "text"
  },
  "temperature": 1,
  "max_tokens": 2048,
  "stop": [
    "."
  ],
  "top_p": 0,
  "frequency_penalty": 0,
  "presence_penalty": 0,
  "stream": false
}'    
```


```bash
{
  "id": "chatcmpl-AXV9xA6T547thMCJM1cKOYS2fH1Vx",
  "object": "chat.completion",
  "created": 1732547965,
  "model": "gpt-4o-2024-08-06",
  "choices": [
    {
      "index": 0,
      "message": {
        "role": "assistant",
        "content": "Coca-Cola is a globally recognized beverage company best known for its flagship product, Coca-Cola, a carbonated soft drink",
        "refusal": null
      },
      "logprobs": null,
      "finish_reason": "stop"
    }
  ],
  "usage": {
    "prompt_tokens": 40,
    "completion_tokens": 24,
    "total_tokens": 64,
    "prompt_tokens_details": {
      "cached_tokens": 0,
      "audio_tokens": 0
    },
    "completion_tokens_details": {
      "reasoning_tokens": 0,
      "audio_tokens": 0,
      "accepted_prediction_tokens": 0,
      "rejected_prediction_tokens": 0
    }
  },
  "system_fingerprint": "fp_7f6be3efb0"
}
```
