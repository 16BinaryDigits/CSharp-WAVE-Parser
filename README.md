# CSharp "C#" WAVE Parser:

Parses the audio data and the format chunck info from a WAVE-Format audio file ".wav".

To use simply add the "WAVE" class to your project then initialize an object of that class,
the object constructor take one string parameter which is the path to the audio file ".wav".

The Wave class exposes the following properties:

1- int Channels.  
2- int SampleRate.  
3- int ByteRate.  
4- int BlockAlign.  
5- int BitsPerSample.  
6- int DataLength.  
7- byte[] Data.  
