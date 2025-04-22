# 🚀 Ollama Installation & Model Guide for Beginners

> Run powerful AI models locally on your computer with just a few commands.

---

## ✅ What is Ollama?

Ollama is a tool that lets you easily run large language models (LLMs) like LLaMA, Deepseek, or Mistral **on your local device**, without needing to rely on the cloud or APIs.

---

## 📥 Step 1: Install Ollama
### 🪟 For Windows
1. Download the installer from [Download Ollama](https://ollama.com/download)
2. Run the `.exe` and follow the setup instructions.

### 🖥 For macOS
```bash
curl -fsSL https://ollama.com/install.sh | sh
```



### 🐧 For Linux (Ubuntu/Debian)
```bash
curl -fsSL https://ollama.com/install.sh | sh
```

---

## 🧠 Step 2: Choose an AI Model

Ollama supports a growing number of models. Some examples:

| Model                | Description                                 | Command                           |
|---------------------|---------------------------------------------|-----------------------------------|
| `deepseek-r1:7b` | Smaller size, faster performance            | `ollama run deepseek-r1:7b`    |
| `deepseek-r1:14b`| Larger, better reasoning but more resources | `ollama run deepseek-r1:14b`   |
| `llama3`            | Latest Meta model (April 2024)           | `ollama run llama3`               |
| `mistral`           | Lightweight and optimized                | `ollama run mistral`              |
| `qwen2.5:72b`           | Large-scale, high-performance model  | `ollama run qwen2.5:72b`              |

To view all available models on your local device by using Terminal or CMD:
```bash
ollama list
```

---

## 📦 Step 3: Download & Run a Model Locally

Use the `ollama run` command to automatically download and start the model:

```bash
ollama run deepseek-r1:7b
```

🔄 It will download the model on first run and start a local interactive session.

---

## 🛠 Step 4: Using the Model in Your Terminal

Once it’s running, just type your question or prompt directly in the terminal:

```txt
> What is the difference between Python and JavaScript?
```

Press **Enter**, and the model will respond right there.

---

## ⚙️ Advanced: Run a Specific Model Version or Pull it First

### Pull a model without starting it:
```bash
ollama pull deepseek-r1:14b
```

### Then run it later:
```bash
ollama run deepseek-r1:14b
```

---

## 🔄 Switch Between Models

Simply run another model:
```bash
ollama run llama3
```

You don’t need to uninstall anything — you can keep multiple models.

---

## 💡 Tips

- `7b` models use less RAM and are faster. Ideal for most laptops.
- `14b` models give better responses but may need >16GB RAM or dedicated GPU.
- For coding tasks, `deepseek-coder` is optimized for code generation and explanation.

---

## 🧽 Optional: Clean Up

To remove downloaded models:
```bash
ollama rm deepseek-r1:7b
```
---

## ⚙️ Tools that halps you to use these models
- GitHub Copilot : [the best tool ever ](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
- open-webui: [WebUI](https://github.com/open-webui/open-webui)
- Continue VScode extension : [https://www.continue.dev/](https://www.continue.dev/)
- AnythingLLM : [https://anythingllm.com/](https://anythingllm.com/)

  
---

## 📚 More Info

- Official Site: [ollama](https://ollama.com)
- Full Model List: [ollama libraries](https://ollama.com/library)
- How to Run Ollama: [Beginner’s Guide](https://www.freecodecamp.org/news/how-to-run-open-source-llms-locally-using-ollama/)



