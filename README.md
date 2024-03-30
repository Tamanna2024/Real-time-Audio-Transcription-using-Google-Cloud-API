## Real-time-Audio-Transcription-using-Google-Cloud-API

This Python application leverages Google's Live Transcribe Speech Engine for real-time audio transcription through the microphone.

## Setup Process

## Google Cloud Platform (GCP) Setup:
- Signing up for a Google Cloud Platform (GCP) account.
- Enabling the Cloud Speech API in the GCP Console.
- Creating a project and noting down the Project ID.
- Creating a service account key in JSON format with Editor role and download it securely.

## Development Environment Setup:
- Ensuring Python is installed on my development machine.
- Installing the Google Cloud CLI, then initialize it by running the following command: "gcloud init"
- Installing necessary libraries: "pip install google-cloud-speech pyaudio"

## Usage Instructions:
- Clone the repository: git clone <https://github.com/Tamanna2024/Real-time-Audio-Transcription-using-Google-Cloud-API>
- Navigate to the project directory: "cd Real-time-Audio-Transcription-using-Google-Cloud-API"
- Set up the Google Cloud service account key: "export GOOGLE_APPLICATION_CREDENTIALS="/path/to/service-account-key.json"
- Run the Python script: "python audio_transcription.py"

## Configurations:
- Put the value of rate by the value of rate for input device in your system.
- CHUNK size is usually taken as 1024 or 2048. Modify it in the code depending upon your rate and results of real time transcription.
- Give the path of your service account key json file.
- Modify the 'phrase_time_limit' parameter in the listen method to control the maximum duration of each transcription.

# The link to video video that showcases the application's real-time transcription capability is: 
https://drive.google.com/file/d/1AKfyBedDwDV1NmPlxhwF3ZPUX_og3BGc/view?usp=sharing

