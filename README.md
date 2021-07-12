# Audio-Search-BOT
So it is basically a bot which listens to you, then save it in a .wav file and then convert it to chunks so that the speech recognition can work on it. Then the audio fle is opened using PyDub then the audio is further splitted into more chunks. After that the chunks are stored in a new file directory to save the processed audio file in it, then the speech to text conversion take place when the process is completed the test is printed after going through all the chunks to give the most accurate text. 
The second part is the web search of the coverted audio to text using googlesearch package which gives the most appropriate URLs for that search. Afterwards that URL is opened in your default browser using the module webbrowser.

Modules required to install via pip and pipwin: pyaudio(using pipwin), wave(pip), speech_recognition(pip), pydub(pip), googlesearch(pip), webbroswer(in-built in PyCharm), os(in-built in PyCharm)
