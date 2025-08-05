# Transcrição com Diarização de Fala 🎙️

Este projeto contém um notebook em Python que realiza **transcrição automática de áudios com diarização**, ou seja, **identificação de quem está falando em cada trecho**. Ele utiliza modelos de ponta como [Whisper](https://github.com/openai/whisper) para transcrição e [pyannote-audio](https://github.com/pyannote/pyannote-audio) para diarização.

---

## 📌 Funcionalidades

- Transcrição automática de áudios  
- Diarização: separação por locutores  
- Alinhamento entre fala e quem falou  
- Preparado para execução no **Google Colab com GPU**

---

## 🚀 Como usar no Google Colab

1. Acesse o notebook no Google Colab:
   - Faça upload do arquivo `Transcricao_com_Diarizacao_Atualizado.ipynb` para seu Google Drive
   - Clique com o botão direito > Abrir com > Google Colab

2. **Ative a GPU**:
   - Vá em: `Ambiente de execução > Alterar tipo de ambiente de execução`
   - Em "Acelerador de hardware", escolha: `GPU`

3. **Execute as células em ordem**:
   - As células estão divididas por seções, como:
     - Instalação de bibliotecas  
     - Carregamento do áudio  
     - Diarização  
     - Transcrição  
     - Resultados

4. **Faça upload do seu áudio** (em `.wav`, `.mp3` ou `.flac`):
   - Pode arrastar o arquivo para a área do notebook ou usar um botão de upload.

---

## 📂 Estrutura

- `Transcription-Diarization.ipynb`: notebook com o código organizado e comentado  
- `README.md`: este arquivo explicativo

---

## 📦 Requisitos

- Python 3.8+
- Recomendado: executar no Google Colab com GPU ativada
- Bibliotecas usadas:
  - `faster-whisper`
  - `pyannote-audio`
  - `torch`
  - `ffmpeg`
  - `librosa`, entre outras

---

## 📃 Licença

Este projeto é de uso livre para fins acadêmicos e pessoais. Sinta-se à vontade para contribuir ou adaptar ao seu fluxo de trabalho!
