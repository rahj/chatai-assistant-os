## INTRODUCTION

This is a Chat AI bot that i released as an Open Source version, which i redacted some 
information i used during my testing phase. The original version of this AI Bot has both the Chat AI and Computer vision capabilities, which i will be releasing as an Open Source in a separate repository. The code for this Chat AI Bot still contains some of the Computer vision functionalities. If you found any issues or bug report, submit it in issue link. 
<br/><br/>

## INSTALL 

Open CV2 <br/>
pip install opencv-contrib-python <br/><br/>

Pyperclip <br/>
pip install pyperclip <br/><br/>

Google GenAI <br/>
pip install google-generativeai <br/><br/>

Groq <br/>
pip install groq <br/><br/>

Pillow <br/>
pip install Pillow <br/><br/>
 
OpenAI <br/>
pip install openai <br/><br/>

<hr>

**Note**

The packages below is only for the computer vision capabilities. <br/><br/>

RealTime TTS <br/>
pip install realtimetts[all] <br/><br/>

Piper TTS <br/>
issues on python 3.12.x on Ubuntu 24.4 <br/>
https://github.com/rhasspy/piper/issues/509 <br/>
https://github.com/rhasspy/piper/issues/384 <br/>
https://github.com/rhasspy/piper/issues/395 <br/><br/>

pip install piper-phonemize-cross <br/>
pip install piper-tts --no-deps <br/><br/>

ffmpeg <br/>
pip install ffmpeg <br/>
pip install python-ffmpeg <br/>
sudo apt install ffmpeg <br/>
<br/>

<hr>
<br/>

## SETUP API KEYS FOR THESE SERVICES 

GROQ API KEY <br/>
GROQ_API_KEY="KEYS HERE" <br/><br/>

GOOGLE GEN AI API KEY <br/>
GOOGLE_GENAI_API_KEY="" <br/><br/>

OPENAI API KEY <br/>
OPENAI_API_KEY="" <br/><br/>

## INSTRUCTIONS 

1. Create Python Environment <br/>
2. Create Environment file for your environment variables in the root folder named .env 
The main services used in the Chat AI Bot is from Groq, you can just disregard the Google Gen AI and Open AI.
<br/><br/>

**GROQ API KEY** <br/>
GROQ_API_KEY="keys-here" <br/><br/>

**GOOGLE GEN AI API KEY** <br/>
GOOGLE_GENAI_API_KEY="keys-here" <br/><br/>

**OPENAI API KEY** <br/>
OPENAI_API_KEY="keys-here" <br/><br/>

3. Install necessary dependencies listed above <br/>
4. Adjust the variables for the Chat AI Bot name and the prompt according to your needs, however the i prompt i made is more than enough. <br/> 
5. Adjust the LLM model accordingly.  <br/>
6. Enjoy! 

