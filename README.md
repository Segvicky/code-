# Speech recognition

Speech is the most common means of communication and the majority of the population in the world relies on speech to communicate with one another. 
Speech recognition system basically translates spoken languages into text

Convert an audio file into text using the python library KaldiRecognizer

**Installations**
**Prerequisites**
The most notable prerequisite is time and space. The Kaldi installation can take hours, and consumes almost 40 GB of disk space, so prepare accordingly. If you need transcriptions ASAP, check out the Cloud Speech-to-Text APIs section!

**Automatic Installation**
If you would like to manually install Kaldi and its dependencies, you can move on to the next subsection. If you are comfortable with an automatic installation, you can follow this subsection.

You will need wget and git installed on your machine in order to follow along. wget comes installed natively on most Linux distributions, but you may need to open a terminal and install using git, further documentation can be gotten from the Kaldi documentation.
 
**Steps:**

Import Speech recognition library
Initializing recognizer class in order to recognize the speech. We are using google speech recognition.
Audio file supports by speech recognition: wav, AIFF, AIFF-C, FLAC. I used ‘wav’ file in this example
I have used speeches from movies in different format to carry out this project. 
By default, google recognizer reads English. It supports different languages, for more details please check the relevant documentation from their website.
