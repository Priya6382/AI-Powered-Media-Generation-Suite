# AI Social Media Content Generator Pro


An advanced AI-powered tool to generate stunning social media content — including engaging text, custom images, and dynamic videos — tailored to your style, platform, and audience. Leverages multiple AI models for text, image, and video generation with customizable templates, hashtags, tones, and styles.

---

## Features

- **Customizable Text Templates:** Use a variety of professionally crafted templates for different social media themes (Tech Launch, Bold Sale, Inspiring, etc.)
- **Tone Control:** Generate content in different tones — Professional, Friendly, Exciting, Inspirational.
- **Multi-platform Formatting:** Automatically format text for platforms like LinkedIn, Instagram, Twitter, Facebook.
- **Hashtag Support:** Add relevant hashtags based on categories like Tech, Business, Lifestyle, etc.
- **High-quality Image Generation:** Generate images in various artistic styles (Realistic, Minimalist, Cyberpunk, etc.) using state-of-the-art diffusion models.
- **Dynamic Video Generation:** Create short videos with style and motion customization.
- **Interactive Gradio UI:** User-friendly interface to customize input and instantly generate output.
- **Evaluation Metrics:** Automated scoring and grading for generated content quality (text coherence, tone alignment, image sharpness, video consistency, and more).

## Demo

Try the live demo hosted on [Your Demo URL] (replace with your deployed link) or run locally to explore all features.

---

## Installation

### Prerequisites

- Python 3.8 or higher
- PyTorch with CUDA support (for GPU acceleration)
- OpenCV
- Gradio
- Transformers and Diffusers libraries from Hugging Face
- Other dependencies (listed in `requirements.txt`)

## Usage

Run the Gradio app locally:

```bash
python app.py

This will open a browser window with the interactive interface where you can:

- Enter your content idea
- Select a template and platform
- Choose tone and AI models for text, image, and video
- Adjust advanced settings like hashtags, image style, video motion
- Generate and view results instantly

---

## Configuration

- **Templates:** Modify or add custom text templates in `TEMPLATES` dictionary.
- **Hashtags:** Customize hashtag categories in the `HASHTAGS` dictionary.
- **Image Styles:** Update or expand `IMAGE_STYLES` list for new artistic effects.
- **Models:** Update the model selection dictionaries (`MODEL_CHOICES`, `IMAGE_MODEL_CHOICES`, `VIDEO_MODEL_CHOICES`) to add or switch AI backends.
