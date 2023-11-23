# Conversational agent with RAG on audio files

## :rocket: Overview
This chat agent is a tool that is able to transcribe audio input, and answer user's questions based on the information in the audio. It is made for efficient summarization, information retrieval, and organization of data after attending events like meetups, lectures, or webinars.\
\
![Version](https://img.shields.io/badge/Version-1.0-blue.svg)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) \
![OpenAI](https://img.shields.io/badge/OpenAI-gpt3.5_turbo-F96854)
![LangChain](https://img.shields.io/badge/LangChain-0.0.316-4BC51D)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0.4.15-7755CC)
![AssemblyAI](https://img.shields.io/badge/AssemblyAI-0.19.0-58A6FF)
![Gradio](https://img.shields.io/badge/Gradio-4.5.0-FF6F61)
![Jupyter Lab](https://img.shields.io/badge/Jupyter%20Lab-IDE-F37626)

## :star: Example
![Demo](https://github.com/Logisx/audio-conversational-agent/blob/main/assets/chat_showcase_cropped.gif?raw=true)

## :toolbox: Technologies used
- OpenAI :robot:
- LangChain :link:
- ChromaDB :floppy_disk:
- AssemblyAI :loud_sound:
- Gradio :computer:
  
## :bar_chart: How It Works
1. **Audio Input**: Input audio is transcribed using AssemblyAI's transcription capabilities.
2. **Storage**: Transcribed data is stored in the Chroma vector database.
3. **Query Response**: User queries are answered using Retrieval Augmented Generation, providing detailed and accurate information.
4. **Conversation History**: Chat is keeping the history of preivous messages and is able to provide more accurate answers based on that.

## :world_map: How to Get Started
1. Open the [notebook](https://github.com/Logisx/audio-conversational-agent/blob/main/audio_conversational_agent.ipynb) file
2. Install dependencies
3. Insert the links to your audio
4. Run the cells and start your chat!

# ⚖️ License

[MIT](https://github.com/Logisx/audio-conversational-agent/blob/main/LICENSE)


# 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aleksandrshishkov)