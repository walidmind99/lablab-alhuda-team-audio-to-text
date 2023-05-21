# About

We members of the [Al Huda](https://lablab.me/event/gaia-hackathon/al-huda) team are going to use AI tool called Whisper which is made by openai.
The solution was implemented on the local machine first, and then the solution was implemented on the cloud due to the lack of capabilities on the local machine
During the following steps, we will mention how each method was accomplished, with a link to look at the results of the solution in the cloud

## General references

Whisper is a general-purpose speech recognition model. It is trained on a large dataset of diverse audio and is also a multitasking model that can perform multilingual speech recognition, speech translation, and language identification.

Official [Whisper GitHub](https://github.com/openai/whisper)

[Lablab Whisper](https://lablab.me/tech/openai/whisper)

Lablab [Whisper streamlit](https://github.com/lablab-ai/OpenAI_Whisper_Streamlit)

## Setup on the local machine

To run whisper AI on our local machine we have to install five different items as follows

1- Downloading [Python](https://www.python.org/downloads/release/python-31010/) programming language 

2- Downloading [PyTorch](https://pytorch.org/get-started/locally/) machine learning library

3- Downloading [Chocolatey](https://chocolatey.org/install#individual) package manager

4- Installing FFMPEG to read different audio files:

    choco install ffmpeg

5- Installing whisper AI:

    pip install -U openai-whisper

## Setup on the cloud

Because we need a capable computer so instead we are going to use google Collaboratory as follows

1- Through Google Drive, install Google Colaboratory

2- Installing whisper AI:

    !pip install git+https://github.com/openai/whisper.git

3- Installing FFMPEG to read different audio files:

    !sudo apt update && sudo apt install ffmpeg

## Cloud application result

With the cloud solution, we used converting audio into text for a very simple clip, and the results were excellent. Then, we took a clip of a user reading the Qur’an, and the result using the small model size was somewhat reasonable, but when the medium size model was used, the results came out excellent, especially at the beginning of the audio clip.
Look at the results on [Google Colab](https://colab.research.google.com/drive/1z_SYtmSvQ_tVBfTv237tJUD6XEcmaQp8?usp=sharing)

## In conclusion

We thank [lablab](https://lablab.me/) for giving us the opportunity to participate in this [hackathon](https://lablab.me/event/gaia-hackathon) and for helping us gain access to this practical experience and valuable educational materials.
