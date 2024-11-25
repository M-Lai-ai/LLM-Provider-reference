```bash
curl -X POST 'https://api.anthropic.com/v1/messages' -H 'x-api-key:$ANTHROPIC_API_KEY' -H 'anthropic-version:2023-06-01' -H 'Content-Type:application/json' -d '{
  "model": "claude-3-5-sonnet-20241022",
  "max_tokens": 1024,
  "stop_sequences": [
    "<YOUR_STOP_SEQUENCE_1>",
    "<YOUR_STOP_SEQUENCE_2>"
  ],
  "temperature": 0,
  "top_p": 0,
  "system": "You are an assistant for the company Coca Cola",
  "messages": [
    {
      "role": "user",
      "content": "hello"
    },
    {
      "role": "assistant",
      "content": "how can I help you?"
    },
    {
      "role": "user",
      "content": "what is Coca Cola?"
    }
  ],
  "stream": true
}'
```

```bash
event: message_start
data: {"type":"message_start","message":{"id":"msg_019LjUbVcGWZzo1ZT8ANiNcF","type":"message","role":"assistant","model":"claude-3-5-sonnet-20241022","content":[],"stop_reason":null,"stop_sequence":null,"usage":{"input_tokens":36,"output_tokens":5}}       }

event: content_block_start
data: {"type":"content_block_start","index":0,"content_block":{"type":"text","text":""}               }

event: ping
data: {"type": "ping"}

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"Coca-Cola is"}         }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" one of the world's most famous and popular bev"}         }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"erage brands, first created in 1886 "}       }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"by pharmacist John Pemberton in Atlanta,"}              }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" Georgia. It's a carbonated soft drink that's"} }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" known for its distinctive sweet taste and ca"}  }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"ramel color.\n\nThe Coca-Cola Company is"}        }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" now a multinational beverage corporation that produces not"} }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" only the original Coca-Cola drink but also owns"}}

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" many other beverage brands including:\n\n1. Diet"} }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" Coke/Coca-Cola Light"}      }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"\n2. Sprite\n3. F"}         }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"anta\n4. Minute Maid"}          }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"\n5. Powerade\n6. An"}         }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"d many others\n\nThe original Coca-Cola formula"} }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" remains a famous trade secret, though"}               }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" it's known to contain:"}               }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"\n- Carbonated water\n- High fruct"}         }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"ose corn syrup (in most markets"}   }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":") or sugar\n- Caramel color"}    }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"\n- Phosphoric acid\n- Natural flav"}}

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"ors\n- Caffeine"}              }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"\n\nCoca-Cola has become more than just a bev"}   }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"erage; it's a global cultural"}      }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" icon, recognized by its distinctive re"}            }

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"d and white logo and marketing campaigns."}}

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" The company operates in more than 200 countries"}}

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":" and territories, making it one of the most recognized brands in the worl"}}

event: content_block_delta
data: {"type":"content_block_delta","index":0,"delta":{"type":"text_delta","text":"d."}           }

event: content_block_stop
data: {"type":"content_block_stop","index":0 }

event: message_delta
data: {"type":"message_delta","delta":{"stop_reason":"end_turn","stop_sequence":null},"usage":{"output_tokens":265}   }

event: message_stop
data: {"type":"message_stop"               }
```
