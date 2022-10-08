# Keyword_Recognition

An application used for extracting video clips containing specific keywords such as "near misses".

## Requirements
The notebook should be run under Python 3.3+ with the following libraries installed:

[moviepy](https://github.com/Zulko/moviepy)

[PocketSphinx](https://github.com/cmusphinx/pocketsphinx)

[speech-recognition](https://github.com/Uberi/speech_recognition)

[vosk](https://github.com/alphacep/vosk-api)

To install the libraries, run the following command:
```
pip install -r requirements.txt
```


## Input Parameters
* <b>input_video:</b> The input video in mp4 format whose codec is H264. 
* <b>keyword:</b> The keyword (like "near misses") to recognise.
* <b>time_buffer:</b> Time (second) before and after each keyword appears in the output video.
* <b>threshold:</b> Threshold of confidence score. Higher means stricter identification.
