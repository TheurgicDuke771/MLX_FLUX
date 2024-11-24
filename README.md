# Streamlit App for Generating Images using FLUX

## Overview

This Streamlit app allows users to generate images using the FLUX model, an AI-powered image generation tool. The app provides a simple and intuitive interface for selecting the image style, text prompt generation model, and FLUX model.

## Features

* Select from a list of available LLM models for text prompt generation
* Choose from two FLUX models: "schnell" and "dev"
* Select an art style for the generated image from a range of options (e.g. anime, graffiti, etc.)
* Enter a simple description of the image to be generated
* Generate a detailed prompt for the image using the selected LLM model
* Generate a file name based on the description generated earlier
* Generate the final image using the selected FLUX model and saves the image file

## Requirements

* Python 3.x
* Streamlit library
* Ollama APP and altest 1 language model. (for text prompt generation)
* FLUX MLX Python implementation provided by Apple MLX Example (for image generation). Clone [MLX Example](https://github.com/ml-explore/mlx-examples.git) repo and follow the instructions in the README file to install and run the FLUX MLX Python implementation.

## Installation

1. Clone this repository: `git clone https://github.com/TheurgicDuke771/MLX_FLUX.git`
2. Install required libraries: `pip install -r requirements.txt`
3. Run the app using Streamlit: `streamlit run streamlit_flux.py`

## Usage

1. Open the app in a web browser by navigating to `http://localhost:8501` (default port)
2. Select the desired LLM model, FLUX model, and art style
3. Enter a simple description of the image to be generated
4. Click the "Generate Image" button to generate the final image
5. The generated image will be displayed on the app and saved in the project root folder.

## Demo

<video controls src="assets/Demo.mp4" title="Demo Video"></video>

## Contributing

Contributions are welcome! If you'd like to add new features or fix bugs, please submit a pull request.

## Licensing

This code is released under the MIT License.