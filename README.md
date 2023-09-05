# Text to Image Generator using Streamlit and OpenAI API 📚

## Overview

This project uses Streamlit to create a simple web application that takes a text prompt and generates images using the OpenAI API. The web app allows users to enter a text prompt, specify the number of images to generate, choose the image size, and select the output format.

## Features

- User-friendly Streamlit interface
- Image generation using OpenAI's API
- Option to generate multiple images from a single prompt
- Support for different image sizes and output formats

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/text-to-image-streamlit.git
    ```

2. Navigate to the project directory:

    ```bash
    cd text-to-image-streamlit
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. To run the Streamlit app, execute the following command:

    ```bash
    streamlit run app.py
    ```

2. Open the displayed URL in your web browser.

3. Enter the text prompt, number of images, image size, and output format as needed.

4. Click on "Generate Images" to view the results.

## Configuration

- `prompt`: Text prompt for image generation
- `num_image`: Number of images to generate (1-5)
- `size`: Size of the image (Available options: 1024x1024, 512x512, 256x256)
- `output_format`: Output format of the image (Available options: url, b64_json)

## Examples
## GUI of Text to image in  streamlit
![Capture1](https://github.com/Umeshbalande/Text_to_image_DallE/assets/3708552/e6ac252d-928e-4e86-b47e-1c5cb0ea0208)

### Generate a single 512x512 image with URL output

- **Prompt**: "A sunset over a mountain."
- **Number of images**: 1
- **Size**: 1024 x 1024
- **Output Format**: URL
![sunset](https://github.com/Umeshbalande/Text_to_image_DallE/assets/3708552/9c82d4a1-5587-440b-a146-866b2b85bfbf)

After clicking "Generate Images," you will see a single  1024 x 1024 image of a sunset over a mountain.

### Generate  1024 x 1024  images with Base64 JSON output

- **Prompt**: "realistic anime girl in maid dress with coal colored hair in battle pose with spear look at viever, Highres illustration"
- **Number of images**: 1
- **Size**: 1024 x 1024
- **Output Format**: b64_json
![anime](https://github.com/Umeshbalande/Text_to_image_DallE/assets/3708552/46be7af1-6017-48a0-8c7b-52e4745ad73a)

After clicking "Generate Images," you will receive 1024 x 1024  images with Base64 JSON output, displayed on the Streamlit interface.


### Generate multiple 256x256 images with Base64 JSON output

- **Prompt**: "A cat sitting on a chair."
- **Number of images**: 3
- **Size**: 256x256
- **Output Format**: b64_json
  
![c1](https://github.com/Umeshbalande/Text_to_image_DallE/assets/3708552/ba586da1-cfe1-4f8e-b0ae-1491ae7651b6)
![c2](https://github.com/Umeshbalande/Text_to_image_DallE/assets/3708552/ebe344cd-fcbc-41f2-9385-8eac86a07d02)
![c3](https://github.com/Umeshbalande/Text_to_image_DallE/assets/3708552/bdb773c2-8936-4518-a018-cf64361c1b64)


After clicking "Generate Images," you will receive three 256x256 images of cats sitting on chairs, displayed on the Streamlit interface.


## API Reference

This project uses the OpenAI API. You'll need to obtain an API key from OpenAI to use this feature.

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

Feel free to adjust these examples to better fit the functionality of your project. Adding screenshots or even GIFs in the Examples section can make it even more informative.
