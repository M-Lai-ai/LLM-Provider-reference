```shell
curl 'https://api.ai21.com/studio/v1/chat/completions' \
	-H 'Content-type: application/json' \
	-H 'Authorization: Bearer E21_API_KEY' \
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
		"stream": true
	}'

```


```shell
data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"role": "assistant"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "Coca"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "-"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "Cola"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " is"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " a"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " globally"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " recognized"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " brand"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " one"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " of"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " the"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " largest"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " beverage"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " companies"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " in"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " the"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " world"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "."}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " It"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " is"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " best"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " known"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " for"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " its"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " flagship"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " product"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " Coca"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "-"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "Cola"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " a"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " carbon"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "ated"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " soft"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " drink"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "."}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " The"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " company"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " also"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " produces"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " sells"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " a"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " wide"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " range"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " of"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " other"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " beverages"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " including"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " sparkling"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " drinks"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " water"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " juices"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " teas"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " coffe"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "es"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " energy"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " drinks"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "."}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "\n"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "\n"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "Founded"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " in"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " "}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "1"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "8"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "8"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "6"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " by"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " Dr"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "."}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " John"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " S"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "."}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " P"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "ember"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "ton"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " Coca"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "-"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "Cola"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " was"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " initially"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " sold"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " at"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " soda"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " fountains"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "."}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " The"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " brand"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " has"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " since"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " grown"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " exponentially"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " is"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " now"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " available"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " in"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " over"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " "}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "2"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "0"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "0"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " countries"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "."}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " The"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " Coca"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "-"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "Cola"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " Company"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " owns"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " markets"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " four"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " of"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " the"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " world"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "'"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "s"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " top"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " five"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " non"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "alcohol"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "ic"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " sparkling"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " soft"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " drink"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " brands"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " including"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " Coca"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "-"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "Cola"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " Diet"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " Coke"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " F"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "anta"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " Spr"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "ite"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "."}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "\n"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "\n"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "The"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " company"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " operates"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " on"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " a"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " global"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " scale"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ","}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " with"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " a"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " vast"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " distribution"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " network"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " a"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " strong"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " focus"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " on"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " marketing"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " innovation"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "."}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " Coca"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "-"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "Cola"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "'"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "s"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " mission"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " is"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " to"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " refresh"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " the"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " world"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " inspire"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " moments"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " of"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " optimism"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " happiness"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " through"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " its"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " brands"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " actions"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "."}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " The"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " company"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " also"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " emphasizes"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " sustainability"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " and"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " corporate"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " social"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " responsibility"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " in"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " its"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": " operations"}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": "."}, "logprobs": null, "finish_reason": null}]}

data: {"id": "chat-aedcc36d3e454a40bf520872ce80992d", "choices": [{"index": 0, "delta": {"content": ""}, "logprobs": null, "finish_reason": "stop"}], "usage": {"prompt_tokens": 40, "completion_tokens": 216, "total_tokens": 256}}

data: [DONE]
```
