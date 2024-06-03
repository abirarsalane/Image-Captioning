# Image Captioning

This project is an Image Captioning tool that uses Hugging Face's BLIP (Bootstrapping Language-Image Pre-training) model to generate captions for images. The project also includes a Gradio web interface for easy interaction.

## Features

- Generates descriptive captions for images
- Uses the pre-trained BLIP model from Salesforce
- Provides a web interface using Gradio

## Setup

### Prerequisites

- Python 3.6 or higher
- pip (Python package installer)

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/abirarsalane/image-captioning.git
    cd image-captioning
    ```

2. Install the required libraries:

    ```sh
    pip install transformers torch pillow gradio
    ```

## Usage

To generate a caption for an image, run the script and open the Gradio interface in your browser:

```sh
python image_captioning.py
```

## Example Interaction
Open the Gradio interface in your browser, upload an image, and see the generated caption.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the coding guidelines and document your code.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any questions or suggestions, feel free to contact [Abir Arsalane](mailto:abir.arsalane@outlook.com).

## Acknowledgements
- [Hugging Face](https://huggingface.co/) for providing the BLIP model
- [Salesforce Research](https://github.com/salesforce) for developing BLIP

