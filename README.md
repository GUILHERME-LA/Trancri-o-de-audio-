
  <br/>
  <img alt="Transcrição Áudio" src="https://img.shields.io/badge/Transcrição%20Áudio-🎙️-6C63FF?style=for-the-badge" />
</div>

# Transcrição de Áudio 🎙️

**Ferramenta de transcrição de áudio para texto utilizando Processamento de Linguagem Natural (NLP)** — converta arquivos de áudio em texto de forma rápida e precisa.

---

## ✨ Funcionalidades

- 🎙️ **Transcrição automática** de arquivos de áudio
- 📝 **Suporte a múltiplos formatos** (MP3, WAV, M4A, etc.)
- 🌐 **Reconhecimento de idioma** automático
- 📄 **Exportação** para TXT, SRT e outros formatos
- 🧹 **Pré-processamento inteligente** de áudio (redução de ruído)
- 📊 **Métricas de confiança** por segmento transcrito

---

## 🛠️ Stack

<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/NLP-6C63FF?style=flat-square&logo=spaCy&logoColor=white" />
  <img src="https://img.shields.io/badge/Audio_Processing-FF6F00?style=flat-square&logo=ffmpeg&logoColor=white" />
</div>

| Categoria | Tecnologia |
|-----------|------------|
| **Linguagem** | Python |
| **NLP** | Modelos de processamento de linguagem natural |
| **Áudio** | FFmpeg, Librosa |
| **API** | FastAPI / Flask |

---

## 🚀 Como Executar Localmente

```bash
# Clone o repositório
git clone https://github.com/GUILHERME-LA/transcricao-audio.git

# Acesse a pasta
cd transcricao-audio

# Crie um ambiente virtual
python -m venv venv

# Ative o ambiente
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Execute a aplicação
python app.py
```

---

## 📂 Estrutura do Projeto

```
transcricao-audio/
├── app/                  # Código principal da aplicação
├── models/               # Modelos de NLP
├── audio/                # Processamento de áudio
├── utils/                # Utilitários
├── tests/                # Testes
└── requirements.txt      # Dependências Python
```

---

## 📄 Licença

Este projeto é de código aberto para fins educacionais e de portfólio.
