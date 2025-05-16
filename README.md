# 🎤 Traductor de Voz Multilingüe con IA

Una aplicación que **transcribe audio en español** y lo **traduce automáticamente** a varios idiomas, generando además audios hablados de las traducciones.

---

## 🌟 Funcionalidades

- 🎙️ Transcripción de voz en español usando el modelo **Whisper** de OpenAI.
- 🌍 Traducción automática a:
  - Inglés
  - Francés
  - Italiano
  - Japonés
- 🔊 Generación de audio hablado en cada idioma traducido usando la API de **ElevenLabs**.
- 💻 Interfaz web sencilla y amigable con **Gradio**, permite grabar directamente desde el micrófono.

---

## ⚙️ Cómo funciona

1. Graba un audio en español (desde micrófono o archivo).
2. Se transcribe el texto con Whisper.
3. El texto se traduce automáticamente a los cuatro idiomas.
4. Se generan archivos de audio en cada idioma traducido.
5. Puedes escuchar las traducciones directamente desde la interfaz.

---

## 🛠️ Requisitos

- Clave API de **ElevenLabs** (para la síntesis de voz) implementada en el achivo .env.
- Python 3.7 o superior.
- Dependencias principales:
  - `gradio`
  - `whisper`
  - `translate`
  - `elevenlabs`
  - `python-dotenv`
