# 🎙️ Whisper AI - Speech-to-Text / Transcrição Automática

[🇺🇸 English](#english) | [🇧🇷 Português](#português)

---

<a name="english"></a>
## 🇺🇸 English Version

This repository contains an experimental Jupyter Notebook (Google Colab) configured to perform automated audio transcriptions using the open-source **Whisper** architecture, developed by OpenAI.

### 🚀 About the Notebook

The project aims to demonstrate how to quickly spin up a Speech-to-Text Inference environment. 

The technical approach abstracts the underlying model complexity by running it via CLI, demonstrating the power of Prompt Engineering (`--initial_prompt`) to force the model into adopting specific grammars and regional colloquialisms (e.g., Brazilian Portuguese accents).

### 🛠️ Tech Stack

- **Python & Google Colab**
- **OpenAI Whisper (Tiny Model)**
- **FFmpeg** as the primary media/codec processor.

### 💻 How to Use

Can be executed locally or on the cloud:

1. Open `WHISPER_IA.ipynb` in a Jupyter environment (or click 'Open in Colab').
2. Follow the predefined cells. The first one will install dependencies (`ffmpeg` and `whisper`).
3. Upload your audio tracking file, rename it to `arquivo.mp3`, and let the AI process it!

### 📄 License
Open source project provided as is, without warranty. Feel free to copy and customize the CLI parameters.

---

<a name="português"></a>
## 🇧🇷 Versão em Português

Este repositório contém um Jupyter Notebook experimental (Google Colab) configurado para realizar transcrições automatizadas de áudio utilizando a arquitetura open-source **Whisper**, desenvolvida pela OpenAI.

### 🚀 Sobre o Notebook

O projeto visa demonstrar como subir um ambiente rápido de Inferência de Modelos de Voz (*Speech-to-Text*). 

A abordagem técnica foca em abstrair a complexidade do modelo diretamente via linha de comando, mostrando na prática o poder do prompt engineering (com `--initial_prompt`) para forçar o modelo a adotar gramática e coloquialismos específicos do cenário brasileiro.

### 🛠️ Tecnologias Utilizadas

- **Python & Google Colab**
- **OpenAI Whisper (Modelo Tiny)**
- **FFmpeg** para o processamento de mídia/codec primário.

### 💻 Como utilizar

Pode ser executado localmente ou em nuvem:

1. Abra o arquivo `WHISPER_IA.ipynb` em um ambiente Jupyter.
   Se preferir, clique no botão "Open in Colab" localizado dentro do notebook.
2. Siga as células predefinidas. A primeira instalará as dependências (`ffmpeg` e `whisper`).
3. Faça o upload do arquivo de áudio desejado renomeando-o para `arquivo.mp3` e deixe a inteligência artificial realizar o processamento!

### 📄 Licença
Projeto de código aberto fornecido sem garantias. Fique à vontade para copiar e customizar os parâmetros.
