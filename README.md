# Speech Summarizer

This tool is designed to transcribe and summarize speech or audio files efficiently.

### Prerequisites
Ensure that Python 3 is installed on your system, as the tool is written in Python.

### Installation Guide
After installing Python 3, install all required dependencies by executing the following command:

bash
pip3 install -r requirements.txt


### Model Download Links

1. *Deepspeech model*: [Download Here](https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.tflite)
2. *Summarization model*: [Download Here](https://huggingface.co/facebook/bart-large-cnn)

### Steps to Follow

To build your Speech Summarizer, follow these steps:

1. *Select a Development Environment*: Choose the development environment that suits you best.
2. *Analyze Speech Files*: Ensure that speech files meet the specified requirements:
   - Sample Rate: 16KHz
   - Audio Channel: Mono
   - File Format: .wav
3. *Convert Speech to Text*: Utilize the Deepspeech model to convert speech into text.
4. *Encode Text to Tokenized IDs*: Prepare the text by encoding it into tokenized IDs.
5. *Generate and Decode Summarized Text*: Employ the summarization model to generate and decode the summarized text.
6. *Optional*: Utilize servers and web frameworks to serve the summarization tool as a REST API.

### Build Your Speech Summarizer in 5 Minutes

1. *Run Jupyter Notebook*: Launch a Jupyter notebook for quick experimentation and modifications.
2. *Run speech_summarizer.py*: Execute the provided script by passing audio files and model files as input.

Feel free to customize and enhance the tool according to your specific needs. Happy summarizing!