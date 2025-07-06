# Virtual-Meeting-Analyzer
---
## About the project
This project processes meetings or any video clip by extracting the speech, transcribing it into concise summaries, and analyzing it to detect the sentiment/tone in the speech. After analysis, it can predict whether the environment is good, mediocre, or bad for working. Pre-trained models present on Hugging Face have been used for transcription and analysis.<br/>

## About the data
- It uses locally provided MP4 files

## Hugging Face model
- `facebook/bart-large-cnn` - for summarizing the text
- `distilbert-base-uncased-finetuned-sst-2-english` - for analyzing sentiment<br/>

## Machine learning Pipeline
1. Loading the video file and extracting audio from it
2. Converting audio to text (Speech to text)
3. Summarising the text
4. Converting text to speech (Text to speech)
5. Performing the sentiment analysis
6. Classifying the working environment
   
**Machine learning, Natural language processing, Sentiment Analysis, Text summarization, Speech-to-text, Text-to-speech, Hugging Face model, Healthy/Unhealthy working environment, Speaker diarization**

## Installation and setup
---
**Dependencies**
- Moviepy
- Gtts
- Transformers
- Python
- Speech_recognition
- Pydub
   
**Steps for running the file**
1. Create a virtual environment and activate it<br/>
   conda create -n meeting-analyzer python<br/>
   conda activate meeting-analyzer
2. Install the required Python libraries
3. Run the notebook by adding the required video file name in the file path in mp4_file 

## Result
---




