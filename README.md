# webcam-gemini-APP
This is an example of how we can use the API gemini to play with interesting things, such as use your own webcam to make question to gemini and the elevenLabs to synthetize the response for fun.

The Gemini provides a multimodal model (gemini-pro-vision) that accepts both text and images and inputs. The model.generate_content API is designed handle multi-media prompts and returns a text output.

# How to run

python webcam_gemini.py

#Requirements

#1. python libraries

pip install PyQt5

pip install opencv-python

pip install python-dotenv

pip install google-generativeai

pip install google-ai-generativelanguage

pip install elevenlabs

pip install --upgrade pydantic

pip install qasync

pip install asyncSlot

pip install QtCore

# 2. Install ffmpeg

in my scenario, i used it to play the audios.

https://www.wikihow.com/Install-FFmpeg-on-Windows

# 3. Get Gemini and elevenLabs API's:

To get the Gemini API key:

https://makersuite.google.com/app/apikey

check if you are in one those available regions, if not, use vpn!

https://ai.google.dev/available_regions

therefore, if you ask to someone to get the API for you and try to use it in one not available country on the list above, you going to receive the error bellow:

400 User location is not supported for the API use.

To get ElevenLabs API key:

https://elevenlabs.io/api

Both are free to use with their due limitations. 

