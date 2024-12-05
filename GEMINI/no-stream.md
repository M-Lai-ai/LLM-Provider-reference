API_KEY="YOUR_API_KEY"

curl \
  -X POST "https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=AIzaSyB0vKg4mbUP6W40JlUHYFFfyEETW7q6WcE" \
  -H 'Content-Type: application/json' \
  -d @<(echo '{
  "contents": [
    {
      "role": "user",
      "parts": [
        {
          "text": "allo\n"
        }
      ]
    },
    {
      "role": "model",
      "parts": [
        {
          "text": "Hello there!\n"
        }
      ]
    },
    {
      "role": "user",
      "parts": [
        {
          "text": "donne moi "
        }
      ]
    }
  ],
  "systemInstruction": {
    "role": "user",
    "parts": [
      {
        "text": "tu"
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
