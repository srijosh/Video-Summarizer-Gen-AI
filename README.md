# Video Summarizer Gen AI

This repository contains a project for a Video Summarizer that leverages advanced generative AI models and tools to summarize video content. The project integrates Google Gemini and PhiData tools, offering a streamlined experience for extracting meaningful insights from videos.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The Video Summarizer Gen AI is designed to generate concise summaries of video content using Google Gemini, PhiData tools, and DuckDuckGo for contextual searches. It provides a powerful interface for uploading video files, analyzing their content, and producing meaningful summaries in seconds.

## Features

- Integration with Google Gemini for generative video analysis.
- Video upload and handling via Streamlit.
- Web search functionality via DuckDuckGo for contextual information.
- AI-driven summarization with highly accurate results.
- User-friendly interface for interacting with the summarization system.

## Installation

1. Clone the repository to your local machine:

```
   git clone https://github.com/srijosh/Video-Summarizer-Gen-AI.git
```

2. Navigate to the project directory:

```
   cd Video-Summarizer-Gen-AI
```

3. Install the required dependencies:

```
   pip install -r requirements.txt
```

4. Set up environment variables by creating a .env file (Use .env.sample as a reference for setting up your .env file.)

## Usage

1. Run the app.py to launch the Streamlit application:

```
   streamlit run app.py
```

2. Upload a video file through the interface.

3. The system will process the video, generate a summary, and display it on the interface.
