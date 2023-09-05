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
## GUI in streamlit
![Capture1](https://github.com/Umeshbalande/Text_to_image_DallE/assets/3708552/e6ac252d-928e-4e86-b47e-1c5cb0ea0208)

### Generate a single 512x512 image with URL output

- **Prompt**: "A sunset over a mountain."
- **Number of images**: 1
- **Size**: 512x512
- **Output Format**: URL

After clicking "Generate Images," you will see a single 512x512 image of a sunset over a mountain.

### Generate multiple 256x256 images with Base64 JSON output

- **Prompt**: "A cat sitting on a chair."
- **Number of images**: 3
- **Size**: 256x256
- **Output Format**: b64_json

After clicking "Generate Images," you will receive three 256x256 images of cats sitting on chairs, displayed on the Streamlit interface.

## API Reference

This project uses the OpenAI API. You'll need to obtain an API key from OpenAI to use this feature.

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

Feel free to adjust these examples to better fit the functionality of your project. Adding screenshots or even GIFs in the Examples section can make it even more informative.
