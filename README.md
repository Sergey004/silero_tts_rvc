## Description:
**TL;DR: Let the bot answer you with the voice of your favorite character!** 

An extension to [oobabooga's textgen-webui](https://github.com/oobabooga/text-generation-webui) allowing you to hear **ANY** voice of your choice generated by [Retrieval-based-Voice-Conversion Project](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebU)

## How it works

Input from TextGen > Silero TTS > Magic of RVC > To chat history

Technically it's hijacking the audio from Silero TTS and redirecting it to RVC

## File to be downloaded and put in the root of the extension.

[hubert_base.pt](https://huggingface.co/lj1995/VoiceConversionWebUI/blob/main/hubert_base.pt)

Credit to (serp-ai)[https://github.com/serp-ai] for making rvc_infer.py, a file that made the impossible possible. 
