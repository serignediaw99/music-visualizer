# Music Visualizer

A deep learning project that generates artistic visualizations from music using StyleGAN neural networks. This project transforms audio into dynamic, artistic visual representations by leveraging the power of generative adversarial networks.

## Overview

This project uses StyleGAN, a state-of-the-art generative adversarial network, to create unique visual interpretations of music. The system analyzes audio input and generates corresponding artistic visualizations that evolve with the music's characteristics. The project is implemented as a Google Colab notebook to take advantage of GPU acceleration, which is essential for running StyleGAN models.

## Features

- Audio processing and analysis
- StyleGAN-based visualization generation
- Support for various music formats
- Artistic style transfer capabilities

## Project Structure

The project consists of a single Jupyter notebook:
- `music_visualizer.ipynb` - Main notebook containing the visualization code, designed to run on Google Colab

## Setup and Usage

1. Clone the repository:
```bash
git clone https://github.com/yourusername/music-visualizer.git
```

2. Open the notebook in Google Colab:
   - Go to [Google Colab](https://colab.research.google.com)
   - Upload `music_visualizer.ipynb` or open it directly from GitHub
   - Ensure you're using a GPU runtime (Runtime → Change runtime type → GPU)

3. Follow the notebook instructions to:
   - Load your music file
   - Configure visualization parameters
   - Generate and save visualizations

## Requirements

- Google Colab account (free tier available)
- GPU runtime in Colab (required for StyleGAN)
- Python 3.8+
- PyTorch
- StyleGAN2-ADA (Pytorch version)
- Librosa (for audio processing)
- Additional dependencies are automatically installed in the notebook

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- StyleGAN authors for their groundbreaking work in generative adversarial networks
- Google Colab for providing GPU resources
- Various open-source libraries that made this project possible