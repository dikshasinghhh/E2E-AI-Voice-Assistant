# E2E-AI-Voice-Assistant pipeline using Hugging Face
# Overview
The project implements Speech-to-Text (STT), natural language processing using a language model (LLM), and Text-to-Speech (TTS) to create a fully functional voice assistant. The assistant can transcribe spoken audio, process the transcribed text to generate responses, and convert those responses back into speech.<br>
- Note: The replicate API token key which is used in the project has been disabled. To run this code kindly use your own token.
<p align="center">
  <img src="https://github.com/user-attachments/assets/2013a186-0796-4a7d-bbdf-a24f7e9bf7dd" alt="Screenshot 2024-08-24 152752" style="width: 400px; height: 300px;">
</p> <br>
<h1>Features</h1> 
1. Speech-to-Text (STT): Converts spoken audio into text using the Whisper pretrained model.<br>
2. Language Processing (LLM): Processes the transcribed text using the LLaMA 2 language model to generate contextually relevant responses.<br>
3. Text-to-Speech (TTS): Converts the generated text back into audio using the Parler pretrained model.<br>

<h1>Additional</h1>
1. Pitch Adjustment: Adjusts the pitch of the generated audio to meet specific requirements.<br>
2. Voice Activity Detection (VAD): Implements VAD to detect and isolate speech segments in the audio.<br>
 <h2>Models</h2>

- [Whisper](https://github.com/openai/whisper) 
- [LLaMA 2](https://huggingface.co/models) 
- [Parler](https://github.com/synesthesiam/parler) 

<h2>Libraries and Frameworks</h2>

- [Hugging Face Transformers](https://github.com/huggingface/transformers)
- [PyTorch](https://github.com/pytorch/pytorch)
- [NumPy](https://github.com/numpy/numpy)
- [Matplotlib](https://github.com/matplotlib/matplotlib)


# Results
1. The voice assistant accurately transcribes audio, processes the text, and generates natural-sounding speech.<br>
2. The pitch adjustment and VAD features enhance the audio output quality and usability.<br>

# Conclusion
This project successfully demonstrates the integration of advanced NLP models into a voice assistant pipeline. Future work could focus on real-time processing, enhanced user interaction, and additional language support.
<br>

Good luck! 🍀


