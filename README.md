# IP-AIv1

Your own AI model — 7B parameters, internet search, free API.

## Live
- Chat: https://yashplmokn09-hue.github.io/Ip-ai/
- API Keys: https://yashplmokn09-hue.github.io/Ip-ai/apikey.html
- Model: https://huggingface.co/Plmokn09/IP-AIv1

## Features
- 7B parameter model
- Real-time internet search (Wikipedia + DuckDuckGo)
- Free API keys for developers
- Always available via HF Inference API

## API Usage
```javascript
const response = await fetch(
  "https://api-inference.huggingface.co/models/Plmokn09/IP-AIv1/v1/chat/completions",
  {
    method: "POST",
    headers: {
      "Authorization": "Bearer YOUR_KEY",
      "Content-Type": "application/json"
    },
    body: JSON.stringify({
      model: "Plmokn09/IP-AIv1",
      messages: [{"role": "user", "content": "Hello!"}],
      max_tokens: 512
    })
  }
);
```

Built by Yash.
