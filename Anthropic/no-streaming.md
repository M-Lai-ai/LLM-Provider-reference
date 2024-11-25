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
  "stream": false
}'
```



```bash
{"id":"msg_01KAfbZR6qM9M2Z16t7FrBJJ","type":"message","role":"assistant","model":"claude-3-5-sonnet-20241022","content":[{"type":"text","text":"Coca-Cola is one of the world's most famous and popular beverage brands, first created in 1886 by pharmacist John Pemberton in Atlanta, Georgia. It's a carbonated soft drink that's known for its distinctive sweet taste and caramel color.\n\nThe Coca-Cola Company is now a multinational beverage corporation that produces not only the original Coca-Cola drink but also owns many other beverage brands including:\n\n1. Diet Coke/Coca-Cola Light\n2. Coca-Cola Zero Sugar\n3. Sprite\n4. Fanta\n5. Minute Maid\n6. Powerade\n7. And many others\n\nThe original Coca-Cola formula remains a famous trade secret, though it's known to contain:\n- Carbonated water\n- High fructose corn syrup (in most markets) or sugar\n- Caramel color\n- Phosphoric acid\n- Natural flavors\n- Caffeine\n\nCoca-Cola is sold in more than 200 countries and territories worldwide, making it one of the most recognized brands globally. The company is known for its iconic red and white logo, distinctive bottle shape, and memorable marketing campaigns."}],"stop_reason":"end_turn","stop_sequence":null,"usage":{"input_tokens":36,"output_tokens":265}}
```
