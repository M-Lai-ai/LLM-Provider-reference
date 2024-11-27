
```shell
curl "https://api.deepinfra.com/v1/openai/chat/completions" \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer $DEEEPINFRA_API_KEY" \
  -d '{
      "model": "meta-llama/Meta-Llama-3.1-70B-Instruct",
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
          "content": "what is Coca Cola."
        }
      ]
    }'
```
```shell
{"id":"chatcmpl-75fc502802c94cafa05db0f7ee12f5f6","object":"chat.completion","created":1732684495,"model":"meta-llama/Meta-Llama-3.1-70B-Instruct","choices":[{"index":0,"message":{"role":"assistant","content":"Coca Cola is a carbonated soft drink that is one of the most recognized and beloved brands in the world. It's a sweet, fizzy drink that is enjoyed by people of all ages in over 200 countries.\n\nCoca Cola was first invented in 1886 by pharmacist John Pemberton in Atlanta, Georgia, USA. He developed the drink as a \"brain tonic and intellectual beverage\" that was supposed to cure headaches and relieve fatigue. The drink quickly became popular, and in 1888, Asa Griggs Candler bought the rights to the formula and founded the Coca Cola Company.\n\nToday, Coca Cola is a global beverage company that offers a wide range of drinks, including Coca Cola Classic, Diet Coke, Coke Zero, and many others. We're proud to be a part of so many people's lives, and we're committed to making a positive impact on the communities we serve.\n\nWould you like to know more about our company or our products?","name":null,"tool_calls":null},"finish_reason":"stop"}],"usage":{"prompt_tokens":48,"total_tokens":248,"completion_tokens":200,"estimated_cost":9.68e-05}}
```
