---
title: "Abraji 2024: Turning Audio and Video into useable data"
format:
  html:
    toc: false
    embed-resources: true
    linkcolor: red
    theme: cosmo
---

Jonathan Soma, Knight Chair in Data Journalism, Columbia Graduate School of Journalism

- **Contact:** jonathan.soma@gmail.com, [@dangerscarf](https://twitter.com/dangerscarf)
- **A few links:** [Practical AI for Investigative Journalism](https://www.youtube.com/playlist?list=PLewNEVDy7gq1_GPUaL0OQ31QsiHP5ncAQ), [jonathansoma.com](jonathansoma.com), [https://jonathansoma.com/everything/](Everything I Know)

[Slides are here](abraji-audio-video.pdf), and my site from yesterday's Abraji session about analyzing documents [can be found here](https://github.com/jsoma/2024-abraji-ai-docs)

## Transcribing

- [MacWhisper](https://goodsnooze.gumroad.com/l/macwhisper) for macOS
- [EasyWhisper](https://easywhisper.io/) for Windows and macOs
- [WhisperJAX](https://huggingface.co/spaces/sanchit-gandhi/whisper-jax) to try it out online
- [Facebook's MMS](https://huggingface.co/spaces/mms-meta/MMS) to try out a non-Whisper model
- [insanely fast whisper](https://github.com/Vaibhavs10/insanely-fast-whisper) for Python (see "Audio transcription" notebook below)

## Software

- [yt-dlp](https://github.com/yt-dlp/yt-dlp) for download videos (YouTube, TikTok, etc) from Python or the command line
- [statcher](https://stacher.io/) for downloading videos *without code*
- [ffmpeg](https://ffmpeg.org/) for manipulating videos in a far too technical way
- [Shutterencoder](https://www.shutterencoder.com) or [ffworks](https://ffworks.net) for a less technical interface to ffmpeg

## AI in Spreadsheets

We have one example of using **Claude for Sheets** to analyze text. You will need to install [Claude for Sheets](https://workspace.google.com/marketplace/app/claude_for_sheets/909417792257) first.

- [Claude for Sheets demo](https://docs.google.com/spreadsheets/d/14CHGyrcmq3M9OFXohsItKdSokdkBl-5DIP5TZWtBL0M/edit?usp=sharing)

## AI with images and video in code (Jupyter notebooks)

We have three examples of using **Python code** to analyze audio and video:

1. [Audio transcription and summarization](https://colab.research.google.com/github/jsoma/abraji24-ai-audio-video/blob/main/01-Audio%20transcription%20and%20summarization.ipynb)
2. [Video analysis](https://colab.research.google.com/github/jsoma/abraji24-ai-audio-video/blob/main/02-Video%20analysis%20pyscenedetect.ipynb)
3. [Custom image classifier](https://colab.research.google.com/github/jsoma/abraji24-ai-audio-video/blob/main/03-Custom-classifier.ipynb)

