
# 💻 Setup


## 1. Local

### 1. Clone project

```bash
git clone https://github.com/datvodinh/rag-chatbot.git
cd rag-chatbot
```

### 2 Install

#### 1. Using script (Ollama, Ngrok, python package)

```bash
source ./scripts/install_extra.sh
```

##### 2. Install `rag_chatbot` Package

```bash
source ./scripts/install.sh
```

#### 3. Run

```bash
source ./scripts/run.sh
```

or

```bash
python -m rag_chatbot --host localhost
```

### 3. Go to: `http://0.0.0.0:7860/`