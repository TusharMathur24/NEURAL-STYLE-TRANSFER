# Neural Style Transfer

This project demonstrates **Neural Style Transfer** using PyTorch and a pre-trained VGG19 model. Neural Style Transfer is a technique that blends the content of one image with the style of another, producing a new, stylized image.

## Features

- Uses PyTorch and torchvision's pre-trained VGG19 model.
- Supports GPU acceleration (if available).
- Customizable style and content weights.
- Easy-to-use functions for loading, displaying, and saving images.
- Modular code for educational and practical use.

## How It Works

1. **Content Image**: The image whose structure you want to preserve.
2. **Style Image**: The image whose artistic style you want to apply.
3. The notebook optimizes a copy of the content image to minimize content and style losses, producing a new image that looks like the content image painted in the style of the style image.

## Requirements

- Python 3.7+
- torch
- torchvision
- Pillow
- matplotlib

Install dependencies with:

```sh
pip install torch torchvision pillow matplotlib
```

## Usage

1. **Clone the repository** and place your `content.jpg` and `style.jpg` images in the same directory as the notebook.

2. **Open the notebook**:

   ```
   Neural_Style_Transfer.ipynb
   ```

3. **Run all cells**. The notebook will:
   - Load your images
   - Perform style transfer
   - Display and save the stylized output as `stylized_output.jpg`

## Customization

- **Change Images**: Replace `content.jpg` and `style.jpg` with your own images.
- **Adjust Weights**: Modify `style_weight` and `content_weight` to control the blend.
- **Steps**: Change `num_steps` in `run_style_transfer` for more/less optimization.

> *Note: The output will be generated after running the notebook.*
