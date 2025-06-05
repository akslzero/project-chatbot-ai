[CHATBOT AI - OPENROUTER MODELS v1.0]

# Cara Menjalankan

1. Download source codenya
2. Copy ke folder projek mu
3. Masukkan token discord bot mu dan api key openrouter ke file .env
4. Buka terminal (cmd/shell/vscode)
5. Jalankan perintah berikut di terminal:

```bash
cd "folder projekmu"
pip install discord.py requests python-dotenv
py bot.py
```

# Bisa ganti model ai nya pada script ini

```bash
payload = {
            "model": "meta-llama/llama-3.3-8b-instruct:free",  # Model gratis dari OpenRouter
            "messages": [
                {"role": "user", "content": user_input}
            ]
        }
```
