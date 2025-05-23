

## 📦 `SynapseStack-sdk`

# 🔌 SynapseStack-sdk

The official SDK for interacting with **SynapseStack**, the modular AI agent platform by [SynapseStack](https://github.com/synapsestack). This SDK allows developers to easily connect, submit tasks, and receive responses from multiple AI agents handling tasks like summarization, code generation, image analysis, and more.

## ✨ Features

- Unified API for accessing various SynapseStack agents
- Supports Python and JavaScript
- Async + sync client support
- Built-in error handling and logging
- Plug-and-play in web apps, scripts, or backend pipelines

---

## 📦 Install

### Python

```bash
pip install SynapseStack-sdk
```

### JavaScript / TypeScript

```bash
npm install @SynapseStack/sdk
```

---

## 🚀 Usage

### Python

```python
from SynapseStack import SynapseStackClient

client = SynapseStackClient(api_key="your_api_key")

result = client.summarize("This is a long document...")
print(result)
```

### JavaScript

```js
import { SynapseStackClient } from "@SynapseStack/sdk";

const client = new SynapseStackClient("your_api_key");

const result = await client.summarize("This is a long document...");
console.log(result);
```

---

## 📂 Project Structure

```bash
SynapseStack-sdk/
├── python/
│   ├── SynapseStack/
│   │   ├── __init__.py
│   │   └── client.py           # Core Python SDK
│   ├── setup.py
│   └── pyproject.toml
├── js/
│   ├── src/
│   │   └── SynapseStackClient.js    # Core JavaScript SDK
│   ├── package.json
│   └── tsconfig.json           # (optional for TypeScript support)
├── examples/
│   ├── summarize.py
│   └── summarize.js
├── tests/
│   ├── test_python_client.py
│   └── test_js_client.test.js
├── README.md
└── LICENSE
```

---

## 🧪 Testing

### Python

```bash
pytest tests/test_python_client.py
```

### JS

```bash
npm test
```

---

## 🛠️ Contributing

1. Fork the repo
2. Create a feature branch (`feat/agent-support`)
3. Submit a PR with clear description

---

## 📄 License

MIT © 2025 SynapseStack
