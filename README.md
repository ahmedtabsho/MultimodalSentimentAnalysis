# MultimodalSentimentAnalysis
Abstract:
This report explores a multimodal sentiment analysis project that integrates data from both video
and audio to assess sentiment more accurately than unimodal methods. The project involves
detecting faces in video frames and classifying sentiment using the POSTER model, while
concurrently transcribing audio using WhisperModel, preprocessing the text, and classifying
sentiment using an LSTM classifier. The results from both classifiers are combined through a
softmax-based dot product to determine the overall sentiment. The final sentiment and text,
translated into Turkish, are displayed with subtitles. The findings demonstrate the effectiveness of
this approach in providing nuanced sentiment analysis for multimedia content. Code Sources
[https://drive.google.com/drive/folders/1T1XMsrnmHWzYkQO-ipRj5Y-_fuO5dvc-?
usp=drive_link]
Introduction:

The technogloies that I have used:
FaceXzoo for face detection in video frames,
POSTER for visual sentiment classification,
WhisperModel for audio transcription,
LSTM classifiers for textual sentiment analysis.
