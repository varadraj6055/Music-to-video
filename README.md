# KlingCreator

KlingCreator is a powerful tool that allows you to generate images and videos based on user-provided prompts. This repository supports text-to-image and text-to-video generation using cutting-edge AI models.

## Features
- **Image Generation**: Create images based on textual prompts.
- **Video Generation**: Generate videos from text prompts using predefined AI models.
- **High-Quality Output**: Option to generate high-quality images and videos.
- **Easy Integration**: Simple command-line interface for quick access to generation tools.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repository/klingCreator.git
Install the required dependencies:

bash

cd klingCreator
pip install -r requirements.txt
If needed, install pyenv to manage Python versions:

bash

brew install pyenv
pyenv install 3.9.6
pyenv global 3.9.6
Usage
Image Generation
To generate an image based on a text prompt, run the following command:

bash

python kling.py --prompt "A surreal dream-like forest with magical creatures" --type image --model_name 1.5 --output-dir ./output/
Video Generation
To generate a video based on a text prompt, use the following command:

bash

python kling.py --prompt "A surreal dream-like forest with magical creatures" --type video --model_name 1.5 --output-dir ./output/
High-Quality Output
If you want to generate high-quality images or videos, add the --high-quality flag:

bash

python kling.py --prompt "A futuristic city at night" --type video --model_name 1.5 --output-dir ./output/ --high-quality
Authentication
If authentication is required for the API, retrieve the authentication cookie from your browser and pass it using the -U argument:





## Example Image Output
![IMAGE FROM AUDIO](https://github.com/user-attachments/assets/adff37ab-5af0-490c-9ff5-eaf93e7b4884)
