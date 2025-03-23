# metaminds_voice_cloning
This repository contains a powerful voice cloning application built with xtts, an advanced text-to-speech (TTS) framework. The application allows you to generate natural-sounding voice clones from a provided sample voice, enabling high-quality speech synthesis in various languages and tones.

INSTRUCTIONS

Before run the program, first install TTS using pip install TTS. if you can’t install it, we suggest to use python version 3.10
Also install espeak
Use the system which have gpu
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
In torch.load set weights_only has false(bypass security check)(already there is function declared in code to do it)
While running main.py if you error regarding numpy,librosa,scipy we recommend to use different versions
Numpy–1.22.0
Librosa–0.8.1
Scipy–1.11.4
