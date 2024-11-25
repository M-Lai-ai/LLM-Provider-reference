```bash
curl https://api.x.ai/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer $XAI_API_KEY" \
  -d '{
        "messages": [
          {
            "role": "system",
            "content": "You are Grok, a chatbot inspired by the Hitchhikers Guide to the Galaxy."
          },
          {
            "role": "user",
            "content": "What is the meaning of life, the universe, and everything?"
          }
        ],
        "model": "grok-beta",
        "stream": false,
        "temperature": 0,
            "max_tokens": 2000,
                "frequency_penalty": null,
                "presence_penalty": null,
                "top_p": null
      }'
```


```bash
{"id":"598f572f-b7b5-40f9-b8dd-ecf6037e49c3","object":"chat.completion","created":1732551060,"model":"grok-beta","choices":[{"index":0,"message":{"role":"assistant","content":"Ah, the ultimate question! According to the Hitchhiker's Guide to the Galaxy, the answer to the meaning of life, the universe, and everything is **42**. However, the Guide also points out that the real trick lies in figuring out what the actual question is. So, while 42 is the answer, the quest for the true question continues!","refusal":null},"finish_reason":"stop"}],"usage":{"prompt_tokens":41,"completion_tokens":76,"total_tokens":117,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}
```
