# Enclothed

Enclothed is a project developed as part of the Buildspace program, where participants take an idea from zero to proof of concept. This project focuses on generating realistic images of an avatar wearing a specific clothing item by training models on images of a person and a dummy clothing item.

![GQzeq2HaQAEw4Wb](https://github.com/user-attachments/assets/6e6b2672-2aab-41b2-aec1-9cc1f7455f6f)


## Overview

The project involves several stages:

1. **Avatar Creation**: Train a model on over 15 images of a person to create a realistic avatar.
2. **Clothing Item Training**: Train another model on a dummy clothing item.
3. **Image Generation**: Generate realistic images of the avatar wearing the clothing item.

## Project Structure

- **create_faceid_finetune.py**: Fine-tunes a model for a specific clothing item.
  - References: 
    ```python:create_faceid_finetune.py
    startLine: 1
    endLine: 28
    ```

- **generate_images.py**: Generates images of the avatar wearing the clothing item.
  - References:
    ```python:generate_images.py
    startLine: 1
    endLine: 25
    ```

- **tune.py**: Creates the avatar by training a model on multiple images of a person.
  - References:
    ```python:tune.py
    startLine: 1
    endLine: 45
    ```

- **check_prompt_status.py**: Checks the status of the image generation process.
  - References:
    ```python:check_prompt_status.py
    startLine: 1
    endLine: 12
    ```

- **heic_to_jpg_converter.py**: Converts HEIC images to JPG format for compatibility.
  - References:
    ```python:heic_to_jpg_converter.py
    startLine: 1
    endLine: 38
    ```

## Getting Started

1. **Prerequisites**: Ensure you have Python and the necessary libraries installed. You may need to install additional packages such as `requests`, `PIL`, and `pyheif`.

2. **Running the Scripts**:
   - Start by running `tune.py` to create the avatar.
   - Next, run `create_faceid_finetune.py` to fine-tune the model for the clothing item.
   - Use `generate_images.py` to generate images of the avatar wearing the clothing item.
   - Check the status of the image generation with `check_prompt_status.py`.

3. **Image Conversion**: If you have HEIC images, use `heic_to_jpg_converter.py` to convert them to JPG format.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Buildspace for the program and support.
- The team and collaborators who contributed to the early version of Enclothed.
