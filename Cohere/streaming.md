```bash
curl -X POST 'https://api.cohere.com/v2/chat' -H 'Authorization:Bearer $CO_API_KEY' -H 'accept:application/json' -H 'Content-Type:application/json' -d '{
  "stream": true,
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
{"id":"a8fc192e-4bb8-4e15-ae1f-a174e8b02ae8","type":"message-start","delta":{"message":{"role":"assistant","content":[],"tool_plan":"","tool_calls":[],"citations":[]}}}
{"type":"content-start","index":0,"delta":{"message":{"content":{"type":"text","text":""}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"C"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"oca"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"-"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"Cola"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" is"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" a"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" carbon"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"ated"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" soft"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" drink"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" sold"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" in"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" stores"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":","}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" restaurants"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":","}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" and"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" vending"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" machines"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" in"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" more"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" than"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" 2"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"0"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"0"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" countries"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"."}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" It"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" is"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" produced"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" by"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" The"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Coca"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"-"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"Cola"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Company"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":","}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" a"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" publicly"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" traded"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" company"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" which"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" began"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" in"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" 1"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"8"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"9"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"2"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" as"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" a"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" result"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" of"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" US"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" businessman"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Asa"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Grig"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"gs"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Cand"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"ler"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" purchasing"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" the"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Coca"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"-"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"Cola"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" brand"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" and"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" formula"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" from"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" John"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Pemberton"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"."}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" The"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Coca"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"-"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"Cola"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Company"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" today"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" offers"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" nearly"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" 4"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"0"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"0"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" brands"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" in"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" over"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" 2"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"0"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"0"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" countries"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" and"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" is"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" one"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" of"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" the"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" largest"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" beverage"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" companies"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" in"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" the"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" world"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"."}}}}
{"type":"content-end","index":0}
{"type":"message-end","delta":{"finish_reason":"COMPLETE","usage":{"billed_units":{"input_tokens":21,"output_tokens":105},"tokens":{"input_tokens":186,"output_tokens":105}}}}
```
