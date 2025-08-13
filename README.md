# 🚀 jupyter-ssh
Ubuntu SSH over ngrok for Google Colab, Kaggle, and other Jupyter notebooks.

---

## ✨ Features

- ⚡ Quick install: SSH server with password or key login  
- 🔐 Secure remote SSH via ngrok TCP tunnel (no static IP needed)  
- 📂 Easy file sharing with miniserve HTTP server on port 80  
- 🛠 Minimal dependencies, works in Debian-based environments  
- 👤 Configurable username, password, SSH key, and ngrok token  
- 📝 Shows ready-to-use SSH commands for instant access  
- ⏳ Keeps runtime alive for long sessions (12 hours default)  

---

## ⚙️ How it works

1. Installs and starts SSH server with your user/password or SSH key  
2. Launches miniserve for easy file sharing on HTTP port 80  
3. Uses ngrok to create public tunnels for SSH (TCP) and miniserve (HTTP)  
4. Shows connection info and commands to connect instantly  
5. Keeps session running, perfect for Colab, Kaggle, or any VM  

---

## ✅ Requirements

- Debian-based Jupyter notebooks: Google Colab, Kaggle, etc.  
- ngrok account & auth token (free tier works)  

---

## ⚠️ Notes

- Google Colab may block SSH, ngrok, and miniserve sometimes  
- Obfuscation can help bypass restrictions (not included yet)
- Kaggle requires account verification to enable internet access.

---

## 🛠 Todos

- Add obfuscated version to bypass restrictions  
- Support Cloudflared and other tunnels  
- Support terminal/SSH over web, especially on mobile  
- Add more detailed documentation  
- Open common ports by default
- Add port manager GUI

---

## 🔗 Links

- ngrok signup: [https://ngrok.com/signup](https://ngrok.com/signup)  
- miniserve project: [https://github.com/svenstaro/miniserve](https://github.com/svenstaro/miniserve)  

---

## 📄 License

Apache 2.0 — free and open source.
