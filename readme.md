# Turn an image into and audio story

## Introduction
------------
This is an app for generating sci-fi stories from images you upload. 

## Function
------------
1. Convert an image to text using the Salesforce BLIP image captioning model.
2. Generate a short sci-fi love story based on a given scenario using the GPT-3.5 turbo language model.
3. Translate the generated text story into audio using the ESPnet Kan-Bayashi LJ Speech VITS model.
4. Create a web interface using Streamlit to upload an image, process it, generate a story, and play the audio.


# Dependencies 
----------------------------
Install:

1. Clone the repository to your local machine.

2. Create VM


Using `conda`:
``` bash
cd hf-play
conda create -n hfp-env 
conda activate hfp-env
```

2. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the root directory of the project. Inside the file, add your OpenAI API key:

```makefile
OPENAI_API_KEY=your_api_key_here
```

## Usage
-----
Steps:

1. Ensure that you have installed the required dependencies and added the OpenAI API key to the `.env` file.

2. Run the `main.py` file using the Streamlit CLI. Execute the following command:
   ```
   streamlit run app.py
   ```

3. The application will launch in your default web browser, displaying the user interface.

4. Upload an image. 

5. Generate an audio story. 

