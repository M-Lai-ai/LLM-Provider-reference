```bash
curl https://api.x.ai/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer XAI_API_KEY" \
  -d '{
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
        "model": "grok-beta",
        "stream": false,
        "temperature": 0,
            "max_tokens": 200,
                "frequency_penalty": null,
                "presence_penalty": null,
                "top_p": null
      }'
```


```bash
{"id":"3b86b984-91ef-4dfd-bcd2-8d2a7449a92d","object":"chat.completion","created":1732552110,"model":"grok-beta","choices":[{"index":0,"message":{"role":"assistant","content":"Coca-Cola is a carbonated soft drink invented in 1886 by John Pemberton in Atlanta, Georgia. Here are some key points about Coca-Cola:\n\n- **Brand**: It's one of the most recognized and valuable brands in the world, known for its iconic contoured bottle and the classic red and white logo.\n\n- **Ingredients**: The original formula included ingredients like coca leaves (de-cocainized since 1903), kola nuts, sugar (or high fructose corn syrup in some markets), caffeine, carbonated water, caramel color, and various flavorings.\n\n- **Taste**: Coca-Cola has a distinctive sweet, slightly acidic taste with a hint of vanilla and spice, which comes from its secret formula known as \"Merchandise 7X.\"\n\n- **Varieties**: Over the years, Coca-Cola has expanded its product line to include numerous variations like Diet Coke, Coca-Cola Zero Sugar, Coca-Cola Cherry, Vanilla Coke, and many others tailored","refusal":null},"finish_reason":"length"}],"usage":{"prompt_tokens":38,"completion_tokens":200,"total_tokens":238,"prompt_tokens_details":{"text_tokens":38,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}
```
