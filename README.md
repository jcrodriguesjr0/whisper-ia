# 🎙️ Whisper AI - Transcrição Automática

Este repositório contém um Jupyter Notebook experimental (Google Colab) configurado para realizar transcrições automatizadas de áudio utilizando a arquitetura open-source **Whisper**, desenvolvida pela OpenAI.

## 🚀 Sobre o Notebook

O projeto visa demonstrar como subir um ambiente rápido de Inferência de Modelos de Voz (*Speech-to-Text*). 

A abordagem técnica foca em abstrair a complexidade do modelo diretamente via linha de comando, mostrando na prática o poder do prompt engineering (com `--initial_prompt`) para forçar o modelo a adotar gramática e coloquialismos específicos do cenário brasileiro.

## 🛠️ Tecnologias Utilizadas

- **Python & Google Colab**
- **OpenAI Whisper (Modelo Tiny)**
- **FFmpeg** para o processamento de mídia/codec primário.

## 💻 Como utilizar

Pode ser executado localmente ou em nuvem:

1. Abra o arquivo `WHISPER_IA.ipynb` em um ambiente Jupyter.
   Se preferir, clique no botão "Open in Colab" localizado dentro do notebook.
2. Siga as células predefinidas. A primeira instalará as dependências (`ffmpeg` e `whisper`).
3. Faça o upload do arquivo de áudio desejado renomeando-o para `arquivo.mp3` e deixe a inteligência artificial realizar o processamento!

## 📄 Licença
Projeto de código aberto fornecido sem garantias. Fique à vontade para copiar e customizar os parâmetros.
