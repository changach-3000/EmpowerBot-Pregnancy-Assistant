# EmpowerBot - Pregnancy Journey Support Chatbot

EmpowerBot is an interactive chatbot application specifically designed to offer support and guidance to teen mothers throughout their pregnancy journey. This Streamlit-powered chatbot leverages cutting-edge technologies to provide comprehensive answers to a wide array of questions related to pregnancy, sexual health, and family planning.

## Overview

EmpowerBot aims to be a reliable and accessible resource for teen mothers, offering valuable information and guidance on various aspects of their pregnancy journey. Whether seeking insights on healthcare facilities, shelters, adoption agencies, sexual education, or family planning, EmpowerBot is equipped to provide accurate and timely responses.

## Features

- **Question Answering:** EmpowerBot uses advanced language processing capabilities powered by LangChain and an OpenAI language model. It's adept at answering queries on numerous topics concerning pregnancy, leveraging robust AI technology to provide accurate and informative responses.
  
- **Accessibility:** The chatbot operates within a user-friendly Streamlit interface, ensuring ease of use and accessibility for teen mothers seeking immediate and reliable information.

## Technologies Used

- **Streamlit:** EmpowerBot is built using Streamlit, providing an intuitive and interactive interface for users to engage with the chatbot effortlessly.

- **LangChain and OpenAI Language Model:** The chatbot harnesses LangChain's capabilities along with an OpenAI language model to process and generate responses to users' inquiries accurately.

## Usage

To use EmpowerBot, simply access the Streamlit interface and start interacting with the chatbot. Ask any questions related to pregnancy, sexual health, or family planning, and EmpowerBot will promptly provide helpful information and guidance.


## Prerequisites

Make sure you have the following installed on your system:

- Python (>= 3.9)
- Pip (Python package installer)

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/AmosMaru/Pregnancy-CHATBOT.git
    ```

2. Navigate to the project directory:

    ```bash
    cd pregnancy-chatbot
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

    Activate the virtual environment:

    - On Windows:

        ```bash
        .\venv\Scripts\activate
        ```

    - On Unix or MacOS:

        ```bash
        source venv/bin/activate
        ```

5. Create a file named `.env` in the project directory and add your OpenAI API key:

    ```env
    OPENAI_API_KEY=your_openai_api_key_here
    ```

    Replace `your_openai_api_key_here` with your actual OpenAI API key.

## Running the App

```bash
streamlit run app.py
