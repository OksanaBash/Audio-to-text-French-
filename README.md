# Audio-to-text-French
Transforms the audio file in French into the text.

Splits the audio into chunks based on silence. Each chunk is converted into text and a simple spelling check is performed in the end. 
You may need to install following libraries: 

- pydub (to work with audio)
- transformers 
- autocorrect 

All three could be easily installed with pip: pip install <library>
