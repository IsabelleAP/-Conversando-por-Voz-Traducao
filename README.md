# -Conversando-por-Voz-Traducao

# 🎤 Voice Translator AI

Sistema de tradução automática por voz em tempo real, utilizando reconhecimento de fala, tradução multi-idioma e síntese de voz.

---

## 🚀 Sobre o Projeto

Este projeto foi desenvolvido a partir de um código do DIO (https://web.dio.me/articles/conversando-por-voz-com-o-chatgpt-utilizando-whisper-openai-e-python) com o objetivo de criar um **intérprete de voz em tempo real**, permitindo a comunicação entre pessoas que falam idiomas diferentes.

O sistema captura áudio do usuário, transcreve a fala, identifica automaticamente o idioma e realiza a tradução para outro idioma, retornando o resultado também em áudio.

---

## 🧠 Como Funciona

O fluxo do sistema segue as etapas abaixo:

1. 🎤 Captura de áudio do usuário
2. 📝 Transcrição da fala com Whisper
3. 🌍 Detecção automática do idioma
4. 🔁 Tradução do texto com `deep-translator`
5. 🔊 Geração de áudio com `gTTS`

---

## 🛠️ Tecnologias Utilizadas

* Python
* Whisper (Speech-to-Text)
* deep-translator (tradução automática)
* gTTS (Text-to-Speech)
* Google Colab / Jupyter Notebook

---

## 💡 Diferenciais do Projeto

* ✅ Tradução automática em tempo real
* ✅ Detecção automática de idioma
* ✅ Conversão de voz → texto → voz
* ✅ Funciona sem necessidade de APIs pagas
* ✅ Estrutura interativa em loop

---

## 🔄 Exemplo de Uso

* Entrada: “Olá, tudo bem?”

* Saída: “Hello, how are you?” (em áudio)

* Entrada: “Hello, how are you?”

* Saída: “Olá, tudo bem?” (em áudio)

---

## ⚠️ Observações

* O sistema requer conexão com a internet para tradução
* A qualidade da transcrição depende da clareza do áudio
* Pequenos delays podem ocorrer devido ao processamento

---

## ▶️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

2. Instale as dependências:

```bash
pip install -r requirements.txt```

3. Execute o notebook no Google Colab ou Jupyter

4. Fale algo no microfone e acompanhe a tradução em áudio 🎧
