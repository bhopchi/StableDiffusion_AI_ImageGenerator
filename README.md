# StableDiffusion_AI_ImageGenerator
This Colab notebook employs a Stable Diffusion model for text-to-image synthesis. It facilitates image generation by loading a pre-trained model, processing user-provided text prompts, and subsequently saving and displaying the generated images.



# Stable Diffusion Image Generation in Google Colab

This repository provides a Google Colab notebook for generating images using Stable Diffusion, a powerful text-to-image AI model. 

## Description

This project leverages the `diffusers` library to access and utilize the Stable Diffusion model within the Google Colab environment. It allows users to input text prompts and generate corresponding images. The generated images can then be displayed within the notebook and saved to disk.

## Features

* **Text-to-Image Generation:** Generate images from descriptive text prompts.
* **Stable Diffusion v1-4 and v2-1:** Includes code to utilize both Stable Diffusion v1-4 and v2-1, providing flexibility and access to different model capabilities.
* **Image Display and Saving:** Display the generated images within the Colab notebook and save them as PNG files.
* **Easy to Use:** The code is organized into functions, making it easy to understand and modify.
* **CUDA Support:** Leverages GPU acceleration for faster image generation when available.

## Requirements

* **Google Colab:** This project is designed to run in a Google Colab environment.
* **Python Libraries:** The following libraries are required:
    * `diffusers`
    * `torch`
    * `torchvision`
    * `torchaudio`
    * `PIL`

## Getting Started

1. **Open the Colab Notebook:** Open the `StableDiffusion-AI-ImageGenerator.ipynb` notebook in Google Colab.
2. **Install Dependencies:** Run the code cells to install the necessary libraries.
3. **Run the Main Function:** Execute the `main()` function.
4. **Enter Prompt:** Provide a text prompt when prompted.
5. **Generate and View:** The generated image will be displayed and saved to disk.


## Example Usage

Get text prompt from user
prompt = input("Enter your text prompt: ")

Generate image based on prompt
generated_image = generate_image(prompt)

Save and show the image
show_image(generated_image) save_image(generated_image)

if name == "main": main()

Enter a text prompt, such as "a cat wearing a hat," and the code will generate and display a corresponding image.

## Note

Ensure that you have a Google Colab account and are familiar with the basics of using Colab notebooks.

## License

This project is licensed under the MIT License.
