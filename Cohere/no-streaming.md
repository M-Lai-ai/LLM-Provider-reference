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
{"id":"146f3a92-6b5d-46df-b369-59001cca307d","type":"message-start","delta":{"message":{"role":"assistant","content":[],"tool_plan":"","tool_calls":[],"citations":[]}}}
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
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":","}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" typically"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" served"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" cold"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"."}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" It"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" is"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" one"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" of"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" the"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" most"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" popular"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" and"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" widely"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" recognized"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" beverages"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" in"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" the"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" world"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":","}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" known"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" for"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" its"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" distinct"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" taste"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" and"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" branding"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"."}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" The"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" drink"}}}}
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
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" multinational"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" beverage"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" corporation"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" headquartered"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" in"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Atlanta"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":","}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Georgia"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"."}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Coca"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"-"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"Cola"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" was"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" originally"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" created"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" in"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" 1"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"8"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"8"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"6"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" by"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" pharmacist"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" John"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" St"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"ith"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Pemberton"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" in"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Columbus"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":","}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Georgia"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":","}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" and"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" was"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" bought"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" out"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" by"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" businessman"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Asa"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Grig"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"gs"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Cand"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"ler"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":","}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" whose"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" marketing"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" tactics"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" led"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Coca"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"-"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"Cola"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" to"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" its"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" dominance"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" in"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" the"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" world"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" market"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"."}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"\n\nWould"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" you"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" like"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" to"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" know"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" about"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" the"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" history"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" of"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":" Coca"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"-"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"Cola"}}}}
{"type":"content-delta","index":0,"delta":{"message":{"content":{"text":"?"}}}}
{"type":"content-end","index":0}
{"type":"message-end","delta":{"finish_reason":"COMPLETE","usage":{"billed_units":{"input_tokens":21,"output_tokens":124},"tokens":{"input_tokens":186,"output_tokens":124}}}}
```
