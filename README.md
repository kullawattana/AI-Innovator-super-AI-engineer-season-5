# AI Innovator: Super AI Engineer Season 5

This repository contains training materials, example code, datasets, notebooks, and workshop exercises for the AI Innovator Super AI Hackathon Season 5 program.

The content is organized as a five-day learning path that introduces practical AI development topics, starting from LLM-based chatbots and Thai AI APIs, then moving through IoT, computer vision, and time series analysis.

## Repository Structure

```text
.
├── Day 1 _ Chatbot and LLM with Line Bot
├── Day 2 _ AI for Thai API (NLP, Image Processing, Speech Recognition) with Line Bot
├── Day 3 _ iOT
├── Day 4 _ Computer Vision
├── Day 5 _ Time Series Analysis
└── documents
```

## Learning Modules

### Day 1: Chatbot and LLM with Line Bot

Focuses on large language models, embeddings, retrieval-augmented generation, and chatbot development.

Included materials:

- LLM and RAG slide decks
- Google Colab notebooks for text embedding, indexing, searching, and retrieval with LLMs
- A Streamlit-based RAG demo
- Persona and knowledge-base examples for LLM training exercises

Key folders:

- `Day 1 _ Chatbot and LLM with Line Bot/RAG-for-SuperAI-main`
- `Day 1 _ Chatbot and LLM with Line Bot/llm-training-main`

### Day 2: AI for Thai API with Line Bot

Provides a LINE bot workshop using AI for Thai APIs for NLP, image processing, and speech-related use cases.

Included materials:

- FastAPI backend service
- LINE bot integration code
- AI for Thai service examples
- Environment template and run scripts

Key folders:

- `Day 2 _ AI for Thai API (NLP, Image Processing, Speech Recognition) with Line Bot/aiforthai-linebot-workshop-main`
- `Day 2 _ AI for Thai API (NLP, Image Processing, Speech Recognition) with Line Bot/aiforthai-linebot-workshop-main-workshop`

### Day 3: IoT

Covers IoT sensor workshops and hardware-related learning materials.

Included materials:

- Arduino lab documents
- PMS7003 dust sensor material
- DHT11 and soil sensor exercises
- Smart soil and dust sensor slide decks
- Driver files for supported hardware

### Day 4: Computer Vision

Introduces image prediction, object detection, YOLOv8 custom training, handwritten recognition, and video object detection.

Included materials:

- Computer vision slide deck
- Colab notebooks for image prediction and object detection
- Sample images and videos
- TACO dataset image samples
- Output video examples

### Day 5: Time Series Analysis

Contains time series, smoothing, decomposition, forecasting, regression, and dashboard exercises.

Included materials:

- Excel and Python activities
- Moving average and exponential smoothing examples
- Time series decomposition scripts
- Baby height analysis exercises
- Multiple linear regression examples
- A Shiny dashboard using healthcare data

## Documents

The `documents` folder contains program-related PDFs, including schedules, participant information, and coordination documents.

## Running Selected Labs

Most exercises are designed to be opened directly as notebooks, slide decks, documents, or local scripts. Some folders include runnable Python applications.

### Day 1 RAG Demo

```sh
cd "Day 1 _ Chatbot and LLM with Line Bot/RAG-for-SuperAI-main"
python -m pip install -r requirement.txt
streamlit run src/main.py
```

### Day 2 FastAPI LINE Bot Workshop

```sh
cd "Day 2 _ AI for Thai API (NLP, Image Processing, Speech Recognition) with Line Bot/aiforthai-linebot-workshop-main"
python -m pip install -r requirements.txt
python -m fastapi dev
```

Before running the LINE bot workshop, copy the environment template and configure the required credentials:

```sh
cp env-example .env
```

### Day 5 Shiny Dashboard

```sh
cd "Day 5 _ Time Series Analysis/Lab/Activity/11-dashboard"
python -m pip install -r requirements.txt
shiny run app.py
```

## Requirements

Requirements vary by module. Install dependencies from the `requirements.txt` or `requirement.txt` file inside the specific lab folder you want to run.

Common tools used across the repository include:

- Python
- Jupyter Notebook or Google Colab
- FastAPI
- Streamlit
- Shiny for Python
- pandas, seaborn, and related data analysis libraries
- LINE Bot SDK
- AI for Thai API client
- Computer vision and deep learning libraries used in the notebooks

## Recommended Workflow

1. Start with the day folder that matches the topic you want to study.
2. Read the slides or documents first.
3. Open the related notebook or script.
4. Install dependencies only for that specific lab.
5. Run the examples and modify the code for experimentation.

## Notes

- Folder names contain spaces and special characters, so wrap paths in quotes when using the terminal.
- Some labs require external services, API keys, LINE bot credentials, model downloads, or Google Colab runtime access.
- Large media files and datasets are included for workshop use.
- The repository is intended as training material, so each day may use different frameworks and setup steps.
