# From Zero to AI Hero: Build Your First App in Google AI Studio

Workshop materials for the **Google Developer Group at Polish-Japanese Academy of Technology (GDG PJATK)**.

Welcome to the repository for the "From Zero to AI Hero" workshop! This session, organized for GDG PJATK, guides you through building your first applications using Google AI Studio and the power of Gemini models via the `google-genai` library in Google Colab.

## Useful Resources

*   **Google AI Studio:** [https://ai.dev](https://ai.dev) - Explore and prototype with generative models. Get your API key here!
*   **Google Colab:** [http://colab.google](http://colab.google) - Run the workshop notebooks in your browser.
*   **Gemini Cookbook:** [https://github.com/google-gemini/cookbook/](https://github.com/google-gemini/cookbook/) - Examples and guides for using the Gemini API.
*   **Gemma Cookbook:** [https://github.com/google-gemini/gemma-cookbook](https://github.com/google-gemini/gemma-cookbook) - Examples for working with Google's open Gemma models.

## Workshop Notebooks

This repository contains two Google Colaboratory notebooks:

*(You can add "Open in Colab" badges here once the repo is public)*

1.  **`text_generation.ipynb`**:
    *   Setting up the `google-genai` client and API Key authentication in Colab.
    *   Performing basic text generation tasks with Gemini Flash.
    *   Using multimodal capabilities to analyze and describe images.
    *   Building a simple conversational chatbot using the chat interface.
    *   Applying system instructions to customize model behavior (e.g., writing emails).
    *   Introduction to "Thinking" models (conceptual overview and current API limitations).
    *   Leveraging built-in tools for enhanced functionality:
        *   `GoogleSearch`: Grounding responses with real-time web information.
        *   `CodeExecution`: Enabling the model to write and run code (e.g., for calculations).

2.  **`image_generation.ipynb`**:
    *   Setting up the client specifically for image generation tasks.
    *   Generating new images from text prompts using the `gemini-2.0-flash-exp-image-generation` model (suitable for the free tier).
    *   Modifying existing images based on text instructions (inpainting/outpainting concepts).
    *   Handling image data within the API response, saving, and displaying generated images in Colab.

## Getting Started

1.  **Google Account:** Ensure you have a Google account.
2.  **API Key:** Obtain a Google AI API key from [Google AI Studio](https://ai.dev) (Click "Get API key").
3.  **Open in Colab:** Click the "Open in Colab" badges above (or navigate to [Google Colab](http://colab.google) and upload the `.ipynb` files).
4.  **Configure API Key:** In Colab, go to the "Secrets" tab (usually accessible via the key icon 🔑 in the left sidebar) and add your `GOOGLE_API_KEY` as a secret. Make sure notebook access is enabled for the secret, as shown in the notebook instructions.
5.  **Run the Notebooks:** Execute the cells step-by-step to follow the workshop content. Upload required images when prompted in the notebooks.

## License

This project is licensed under the Apache License, Version 2.0. 

```text
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
