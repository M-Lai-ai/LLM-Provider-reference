```bash
curl https://api.x.ai/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer XAI_API_KEY" \
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
        "stream": true,
        "temperature": 0,
            "max_tokens": 2000,
                "frequency_penalty": null,
                "presence_penalty": null,
                "top_p": null
      }'
```
```bash
data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"Ah","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":1,"total_tokens":42,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":",","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":2,"total_tokens":43,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":3,"total_tokens":44,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" ultimate","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":4,"total_tokens":45,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" question","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":5,"total_tokens":46,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"!","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":6,"total_tokens":47,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" According","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":7,"total_tokens":48,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" to","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":8,"total_tokens":49,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" Douglas","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":9,"total_tokens":50,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" Adams","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":10,"total_tokens":51,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"'","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":11,"total_tokens":52,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" \"","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":12,"total_tokens":53,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"The","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":13,"total_tokens":54,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" Hitch","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":14,"total_tokens":55,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"h","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":15,"total_tokens":56,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"iker","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":16,"total_tokens":57,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"'s","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":17,"total_tokens":58,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" Guide","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":18,"total_tokens":59,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" to","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":19,"total_tokens":60,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":20,"total_tokens":61,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" Galaxy","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":21,"total_tokens":62,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":",\"","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":22,"total_tokens":63,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":23,"total_tokens":64,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551210,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" answer","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":24,"total_tokens":65,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" to","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":25,"total_tokens":66,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":26,"total_tokens":67,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" meaning","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":27,"total_tokens":68,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" of","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":28,"total_tokens":69,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" life","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":29,"total_tokens":70,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":",","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":30,"total_tokens":71,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":31,"total_tokens":72,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" universe","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":32,"total_tokens":73,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":",","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":33,"total_tokens":74,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" and","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":34,"total_tokens":75,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" everything","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":35,"total_tokens":76,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" is","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":36,"total_tokens":77,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" **","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":37,"total_tokens":78,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"4","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":38,"total_tokens":79,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"2","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":39,"total_tokens":80,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"**.","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":40,"total_tokens":81,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" However","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":41,"total_tokens":82,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":",","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":42,"total_tokens":83,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":43,"total_tokens":84,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" characters","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":44,"total_tokens":85,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" in","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":45,"total_tokens":86,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":46,"total_tokens":87,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" story","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":47,"total_tokens":88,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" realize","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":48,"total_tokens":89,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" that","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":49,"total_tokens":90,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":50,"total_tokens":91,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" real","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":51,"total_tokens":92,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" challenge","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":52,"total_tokens":93,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" is","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":53,"total_tokens":94,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" figuring","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":54,"total_tokens":95,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" out","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":55,"total_tokens":96,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" what","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":56,"total_tokens":97,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":57,"total_tokens":98,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" actual","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":58,"total_tokens":99,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" question","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":59,"total_tokens":100,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" is","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":60,"total_tokens":101,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":".","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":61,"total_tokens":102,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551211,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" So","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":62,"total_tokens":103,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":",","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":63,"total_tokens":104,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" while","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":64,"total_tokens":105,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" ","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":65,"total_tokens":106,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"4","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":66,"total_tokens":107,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"2","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":67,"total_tokens":108,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" is","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":68,"total_tokens":109,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":69,"total_tokens":110,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" answer","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":70,"total_tokens":111,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":",","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":71,"total_tokens":112,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":72,"total_tokens":113,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" quest","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":73,"total_tokens":114,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" for","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":74,"total_tokens":115,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" understanding","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":75,"total_tokens":116,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" the","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":76,"total_tokens":117,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" question","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":77,"total_tokens":118,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":" continues","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":78,"total_tokens":119,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"content":"!","role":"assistant"}}],"usage":{"prompt_tokens":41,"completion_tokens":79,"total_tokens":120,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: {"id":"6997ab18-bfe6-43fe-826a-50b0c4e27431","object":"chat.completion.chunk","created":1732551212,"model":"grok-beta","choices":[{"index":0,"delta":{"role":"assistant"},"finish_reason":"stop"}],"usage":{"prompt_tokens":41,"completion_tokens":80,"total_tokens":121,"prompt_tokens_details":{"text_tokens":41,"audio_tokens":0,"image_tokens":0,"cached_tokens":0}},"system_fingerprint":"fp_6ca29cf396"}

data: [DONE]
```
