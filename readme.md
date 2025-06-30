# ComfyUI-EsesImageEffectBloom: Enhance Your Images with Bloom Effect 🌟

![Bloom Effect](https://img.shields.io/badge/Bloom%20Effect-Optimized%20for%20GPU-brightgreen)

## Overview

ComfyUI-EsesImageEffectBloom provides a powerful bloom image post-processing effect for Comfy. This tool leverages GPU capabilities to deliver optimized blur effect calculations, enhancing your images with a stunning glow. Whether you’re a developer or a digital artist, this effect can elevate your visuals effortlessly.

## Features

- **GPU Acceleration**: Utilizes your GPU for fast processing.
- **Optimized Blur Calculations**: Achieves high-quality results without sacrificing performance.
- **Easy Integration**: Seamlessly integrates with Comfy, allowing for quick setup.
- **Customizable Settings**: Adjust bloom intensity and radius to fit your needs.

## Installation

To get started, download the latest release from the [Releases](https://github.com/aassas2/ComfyUI-EsesImageEffectBloom/releases) section. After downloading, execute the file to install the effect.

### Requirements

- **Comfy**: Ensure you have the latest version of Comfy installed.
- **GPU Support**: A compatible GPU is recommended for optimal performance.

## Usage

1. **Load Comfy**: Start by launching Comfy on your machine.
2. **Import the Effect**: Navigate to the effects section and import the Bloom effect.
3. **Adjust Settings**: Modify the bloom intensity and radius according to your project requirements.
4. **Apply to Image**: Select the image you want to enhance and apply the effect.

### Example Code

Here’s a simple example of how to apply the bloom effect:

```python
import comfy

# Load your image
image = comfy.load_image('path/to/your/image.jpg')

# Apply bloom effect
bloomed_image = comfy.apply_bloom(image, intensity=0.5, radius=10)

# Save the result
comfy.save_image(bloomed_image, 'path/to/save/bloomed_image.jpg')
```

## Configuration

You can customize the bloom effect by modifying the following parameters:

- **Intensity**: Controls how strong the bloom effect appears. Values typically range from 0 to 1.
- **Radius**: Determines how far the bloom spreads from the light sources in the image. Higher values result in a more extensive glow.

## Contributing

We welcome contributions to improve ComfyUI-EsesImageEffectBloom. If you have suggestions or bug fixes, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your forked repository.
5. Submit a pull request for review.

## Issues

If you encounter any issues or bugs, please check the [Issues](https://github.com/aassas2/ComfyUI-EsesImageEffectBloom/issues) section of the repository. You can report new issues or contribute to existing discussions.

## Documentation

For detailed documentation on how to use the bloom effect, refer to the [Wiki](https://github.com/aassas2/ComfyUI-EsesImageEffectBloom/wiki). Here you will find guides, tips, and advanced techniques to make the most out of the bloom effect.

## Community

Join our community to share your work and get feedback:

- **Discord**: Connect with other users and developers.
- **Twitter**: Follow us for updates and news.
- **GitHub Discussions**: Engage in conversations and ask questions.

## Roadmap

We plan to add more features and improvements in future releases. Here are some ideas we’re considering:

- Enhanced customization options for the bloom effect.
- Additional post-processing effects.
- Improved performance metrics.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/aassas2/ComfyUI-EsesImageEffectBloom/LICENSE) file for details.

## Acknowledgments

- Thanks to the Comfy community for their support and feedback.
- Special thanks to contributors who help make this project better.

For the latest updates, visit the [Releases](https://github.com/aassas2/ComfyUI-EsesImageEffectBloom/releases) section. Download the latest version and enhance your images today!