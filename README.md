# YouTube Transcriber Application (Assets/image.jpg)

## Overview

This application allows you to transcribe the audio from YouTube videos. Simply provide the YouTube video URL, and the application will attempt to generate a text transcript of the spoken content.

## Features

* **Easy to Use:** Simple interface for pasting YouTube video URLs.
* **Automatic Transcription:** Leverages powerful speech-to-text models to generate transcripts.
* **Error Handling:** Gracefully handles invalid URLs or videos where transcription might not be available.


## Getting Started

### Prerequisites

* **Python 3.x:** Ensure you have Python 3 installed on your system. You can download it from [https://www.python.org/downloads/](https://www.python.org/downloads/).
* **pip:** Python's package installer, which usually comes bundled with Python.
* **API_KEY** Require to get GOOGLE_API_KEY from https://aistudio.google.com/app/prompts/new_chat to use google gemini models.

### Installation

1.  **Clone the Repository (Optional):** If you have the application code in a Git repository, clone it to your local machine:

    ```bash
    git clone <repository_url>
    cd YoutubeVideoTranscriber
    ```
2.2.  **Creating Environment and Install Dependencies:** Navigate to the application directory in your terminal and install the required Python libraries using pip:

    ```bash
    conda create -p venv python==3.12
    ```

    ```bash
    conda activate vevn/
    ```

    ```bash
    pip install -r requirements.txt
    ```

2.3  **Creating a Environment variable file** Create a .env file in root directory and place the GOOGLE_API_KEY as GOOGLE_API_KEY = "xxxxxxxxxxxx" 

### Running the Application

1.  **Navigate to the Application Directory:** Open your terminal and go to the directory where the main application file (e.g. `app.py`) is located.

2.  **Run the Application:** Execute the application using Python:

    ```bash
    streamlit run app.py
    ```


3.  **Follow On-Screen Instructions:** The application should now be running. Follow the prompts or use the graphical interface to enter the YouTube video URL.

## Usage

1.  **Enter YouTube URL:** When prompted, paste the full URL of the YouTube video you want to transcribe.
2.  **Initiate Transcription:** Press Enter or click the "Transcribe" button (if it's a GUI application).
3.  **Wait for Transcription:** The application will process the video and generate the transcript. This might take some time depending on the length of the video. Progress will be displayed if available.
4.  **View Transcript:** Once the transcription is complete, the text will be displayed in the application.


## Potential Issues and Troubleshooting

* **Dependency Errors:** If you encounter errors related to missing libraries, ensure you have run `pip install -r requirements.txt` successfully.
* **Transcription Errors:** The accuracy of the transcript depends on the quality of the audio and the capabilities of the speech-to-text model being used. Expect some errors, especially with fast speech, background noise, or technical jargon.
* **Video Not Transcribable:** Some YouTube videos might not have automatically generated captions available, which this application might rely on. In such cases, the application might not be able to produce a transcript.
* **Network Issues:** Ensure you have a stable internet connection for the application to access YouTube and the transcription services.
* **Rate Limiting:** If you are making a large number of transcription requests, you might encounter rate limiting from the underlying services.

## License

This project is licensed under the [Specify License Name] License. See the `LICENSE` file for more details.

## Acknowledgements

* youtube-transcript-api @jdepoix special tanks for creating such amazing library.

## Contact

If you have any questions or issues, please feel free to [apise81@gmail.com/open an issue on GitHub].
























Requirements  

1. Require to get GOOGLE_API_KEY from https://aistudio.google.com/app/prompts/new_chat to use google gemini models.

Steps to make code working.

1. create a environment using conda create -p venv python==3.10

2. Activate conda environment conda activate venv/

3. Install all the required requirement. pip install -r requirements.txt

4. Create a .env file and place the GOOGLE_API_KEY as GOOGLE_API_KEY = "Google_api_key"

5. To Run the code  Enter streamlit run app.py

