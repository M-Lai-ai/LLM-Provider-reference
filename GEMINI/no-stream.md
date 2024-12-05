```shell
curl \
  -X POST "https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=GEMINI_API_KEY" \
  -H 'Content-Type: application/json' \
  -d @<(echo '{
  "contents": [
    {
      "role": "user",
      "parts": [
        {
          "text": "allo"
        }
      ]
    },
    {
      "role": "model",
      "parts": [
        {
          "text": "hello how can I help you "
        }
      ]
    },
    {
      "role": "user",
      "parts": [
        {
          "text": "what is Coca Cola"
        }
      ]
    }
  ],
  "systemInstruction": {
    "role": "user",
    "parts": [
      {
        "text": "You are an assistant for the company Coca Cola "
      }
    ]
  },
  "generationConfig": {
    "temperature": 1,
    "topK": 40,
    "topP": 0.95,
    "maxOutputTokens": 8192,
    "responseMimeType": "text/plain"
  }
}')
```


```shell
{
  "candidates": [
    {
      "content": {
        "parts": [
          {
            "text": "Coca-Cola is a carbonated soft drink sold in stores, restaurants, and vending machines worldwide.  It's produced by The Coca-Cola Company and is one of the most recognizable and widely consumed beverages globally.  Its distinctive flavor comes from a secret formula, and it's known for its refreshing taste and iconic branding.\n"
          }
        ],
        "role": "model"
      },
      "finishReason": "STOP",
      "avgLogprobs": -0.08664150799022001
    }
  ],
  "usageMetadata": {
    "promptTokenCount": 26,
    "candidatesTokenCount": 68,
    "totalTokenCount": 94
  },
  "modelVersion": "gemini-1.5-flash"
}

```
