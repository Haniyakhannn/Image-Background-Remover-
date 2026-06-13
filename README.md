# Image-Background-Remover-
AI Background Remover (U2Net + Gradio)

A simple AI-powered web application that removes image backgrounds using a pre-trained deep learning model (U2Net via rembg) and provides an interactive UI using Gradio in Google Colab.

# Live Demo
https://4134323f1d5465b740.gradio.live/

# Features
1. Upload image via web interface
2. AI-powered background removal (U2Net model)
3. Fast inference using rembg
4. Interactive UI using Gradio
5. Instant output preview

# Tech Stack
1. Python
2. rembg (U2Net deep learning model)
3. Pillow (Image processing)
4. Gradio (Frontend UI)
5. Google Colab (Execution environment)

# Installation

If running locally:
pip install rembg onnxruntime gradio pillow
# How to Run
In Google Colab:
!pip install rembg onnxruntime gradio pillow

Then run your notebook and execute:

interface.launch(share=True)

Model separates foreground from background
Output is returned as a transparent PNG
Gradio displays result in real-time
