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

## ⚡ Usage

1. Open the notebook in **Google Colab**:  

   - Standard version: https://colab.research.google.com/github/chunix64/jupyter-ssh/blob/main/jupyter_ssh.ipynb
   - Obfuscated version: https://colab.research.google.com/github/chunix64/jupyter-ssh/blob/main/jupyter_essessjack_okphuzkatiz.ipynb

2. Run each cell step by step:  
   - **Step 0**: 🛠️ Prepare the environment  
   - **Step 1**: 🔐 Setup SSH (set your username, password, or SSH key)  
   - **Step 2**: 📂 Start Miniserve (file sharing, upload/download)  
   - **Step 3**: 🚀 Start Ngrok (enter your Ngrok auth token, get tunnel links)  
   - **Step 4**: ⏳ Keep runtime alive (prevents Colab from stopping)  

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

- Google Colab may block SSH, ngrok, and miniserve sometimes (Check [Google colab policies](https://research.google.com/colaboratory/faq.html#limitations-and-restrictions))
- Obfuscation can help bypass restrictions (not finished yet)
- Kaggle requires account verification to enable internet access.

---

## 🔮 Obfuscated version
- File: jupyter-essessjack-okphuzkatiz.ipynb
- Method: base64 encode
- Obfuscated:
    + ngrok == n{lalaar}ok
    + ssh == {eggeggs}h
    + miniserve == mini{kenook}ve
    + tunnel = tu{rnonoff}
- Only bypass source code restrictions in this time, runtime restrictions not
- Needfix: Still not bypass google colab restrictions
- Suggestion: Fork or patch ssh, ngrok, miniserve. Change port of sshd 

---

## 🛠 Todos

- Bypass google colab restrictions  
- Support Cloudflared and other tunnels  
- Support terminal/SSH over web, especially on mobile  
- Add more detailed documentation  
- Open common ports by default
- Add port manager GUI
- Create a compact version for Kaggle (since Kaggle does not support the Colab-style UI form)

---

## 🔗 Links

- ngrok signup: [https://ngrok.com/signup](https://ngrok.com/signup)  
- miniserve project: [https://github.com/svenstaro/miniserve](https://github.com/svenstaro/miniserve)  

---

## 📄 License

Apache 2.0 — free and open source.
