# AIKitchen: CNN's Eye for Ingredients, LLM's Language Charm for Recipes

Welcome to AIKitchen, where we leverage the power of artificial intelligence to transform images into delicious recipes! With the combination of Convolutional Neural Networks (CNNs) for image analysis and Large Language Models (LLMs) for recipe generation, AIKitchen offers an innovative solution for culinary enthusiasts and home cooks alike.

## Project Overview

AIKitchen is a web application that allows users to upload images of ingredients, which are then analyzed using CNNs to extract text descriptions. These descriptions are passed to LLMs to generate detailed recipes tailored to the ingredients detected in the image. Additionally, the application provides text-to-speech functionality to read out the ingredients and recipe instructions, making cooking a seamless and accessible experience.

## Features

- **Image to Text Conversion:** Utilize state-of-the-art image captioning models to extract text descriptions from uploaded images of ingredients.
- **Recipe Generation:** Generate customized recipes based on the identified ingredients using advanced language models.
- **Text-to-Speech:** Convert text-based ingredients and recipe instructions into speech for easy auditory consumption.
- **Streamlit Web Interface:** User-friendly web interface powered by Streamlit for seamless interaction and visualization.

## Installation

To run the AIKitchen application locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Set up environment variables for OpenAI and Hugging Face Hub API tokens in a `.env` file.
4. Run the application using `streamlit run app.py`.
5. Access the web interface at `http://localhost:8501` in your browser.

## Usage

1. Launch the AIKitchen web application by following the installation instructions.
2. Upload an image containing ingredients using the provided interface.
3. Wait for the image analysis and recipe generation processes to complete.
4. Explore the generated recipe, including ingredients and cooking instructions.
5. Listen to the audio rendition of the ingredients and recipe instructions for added convenience.
6. Experiment with different ingredients and images to discover new recipes tailored to your preferences.

