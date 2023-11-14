# 🌟 Text-to-Image Generator 🖼️


## Overview
This project implements a text-to-image generator using the Hugging Face API key. The generator utilizes the Stable Diffusion model for image generation and the GPT-2 model for prompt-based text generation. The provided code demonstrates how to use these models to generate images based on textual prompts.

## 🚀 Setup

### Prerequisites
- Python 3.x
- [Hugging Face API key](https://huggingface.co/join)

### 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/text-to-image-generator.git
   cd text-to-image-generator

1. Install the required dependencies:
      ```Pip
         pip install -r requirements.txt
  
3. Set up your Hugging Face API key:
- Obtain your API key from Hugging Face.
- Set the API key as an environment variable:
export HF_HOME=<path_to_your_home_directory>  # Set your home directory path
export TRANSFORMERS_HOME=$HF_HOME/.cache/huggingface  # Set Hugging Face cache directory
export HF_HOME_API_KEY=<your_api_key_here>

### Usage

Generate Image from Text
To generate an image from a text prompt, use the generate_image function in the provided Python script. 
Here's an example:

from text_to_image_generator import generate_image
Example usage: generate an image with the prompt "a boy sits on a chair"
generated_image = generate_image("a boy sits on a chair")
generated_image.show()  # Display the generated image


### 🤝 Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

### 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

