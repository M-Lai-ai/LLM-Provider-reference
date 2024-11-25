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
  "stream": true
}'
```
```bash
data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"role":"assistant","content":"","refusal":null},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":"C"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":"oca"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":"-Cola"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" is"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" a"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" globally"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" recognized"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" beverage"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" company"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" best"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" known"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" for"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" its"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" flagship"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" product"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":","},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" Coca"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":"-Cola"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":","},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" a"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" carbon"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":"ated"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" soft"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{"content":" drink"},"logprobs":null,"finish_reason":null}]}

data: {"id":"chatcmpl-AXV7Gc2swQM4Svs0K8ISRSCqaeHu4","object":"chat.completion.chunk","created":1732547798,"model":"gpt-4o-2024-08-06","system_fingerprint":"fp_7f6be3efb0","choices":[{"index":0,"delta":{},"logprobs":null,"finish_reason":"stop"}]}

data: [DONE]
```
