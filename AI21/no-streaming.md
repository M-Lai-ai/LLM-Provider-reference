```shell
curl 'https://api.ai21.com/studio/v1/chat/completions' \
	-H 'Content-type: application/json' \
	-H 'Authorization: Bearer $E21_API_KEY' \
	--data '{
		"model": "jamba-1.5-large",
		"messages": [
			{
				"role": "system",
				"content": "You are an assistant for the company Coca Cola"
			},
			{
				"role": "user",
				"content": "allo"
			},
			{
				"role": "assistant",
				"content": "Hello! How can I assist you today?"
			},
			{
				"role": "user",
				"content": "what is Coca Cola"
			}
		],
		"documents": [],
		"tools": [],
		"n": 1,
		"max_tokens": 2048,
		"temperature": 0.4,
		"top_p": 1,
		"stop": [],
		"stream": false
	}'
```


```shell
{"id":"chat-f249b14a84c940df9add49bba82a5f20","choices":[{"index":0,"message":{"role":"assistant","content":"Coca-Cola is a carbonated soft drink sold in stores, restaurants, and vending machines throughout the world. It is produced by The Coca-Cola Company of Atlanta, Georgia, and is often referred to simply as Coke. Originally intended as a patent medicine when it was invented in the late 19th century, Coca-Cola was bought out by businessman Asa Griggs Candler, whose marketing tactics led Coke to its dominance of the world soft-drink market throughout the 20th century.\n\nThe drink's name refers to two of its original ingredients: coca leaves and kola nuts (a source of caffeine). The current formula of Coca-Cola remains a closely guarded trade secret; however, a variety of reported recipes and experimental recreations have been published. The Coca-Cola Company produces concentrate, which is then sold to licensed Coca-Cola bottlers throughout the world. The bottlers, who hold exclusive territory contracts with the company, produce the final product in cans and bottles from the concentrate, in combination with filtered water and sweeteners. A typical 12-ounce can contains 38 grams of sugar (usually in the form of high fructose corn syrup).\n\nCoca-Cola has been a global brand for many decades, and its marketing campaigns have had a significant impact on popular culture. The company sponsors a variety of events and sports teams worldwide, and its advertisements are known for their iconic imagery and catchy slogans.","tool_calls":null},"logprobs":null,"finish_reason":"stop"}],"usage":{"prompt_tokens":40,"completion_tokens":299,"total_tokens":339}}
```
