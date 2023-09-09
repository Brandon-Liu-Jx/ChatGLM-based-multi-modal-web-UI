
# FutureTechGPT-4: A Text-based Dialogue System for Image Captioning, Image Generation and Text Conversation

FutureTechGPT-4 is a text-based dialogue system that can leverage three large-scale models for image captioning, image generation and text conversation. The system is based on chatglm2, a generative language model that can dynamically switch between different tasks using natural language commands. The system can also utilize three pre-trained models for each task: BLIP2 for image captioning, diffusion model for image generation and chatglm2 itself for text conversation. These models are fine-tuned on domain-specific datasets to improve their performance and diversity. The system provides a webui interface based on gradio for easy interaction and showcases various examples of its capabilities. The code of this project is open sourced on GitHub [here].

## Usage 

You can use natural language commands to specify the desired output modality and task parameters. For example, you can use commands like:

- "draw me a picture of a dragon"
- "write me a poem about love"
- "tell me a joke"

The system will generate relevant responses based on your commands and display them on the webui interface.

## Examples

Here are some examples of the system's outputs for different commands:

### Image Captioning

Command: "describe this image [image of a cat]"

Output: This is an image of a cat. The cat is orange and white, and has green eyes. It is lying on a blue sofa, looking at the camera.

### Image Generation

Command: "draw me a picture of a unicorn"

Output: Here is a picture of a unicorn that I drew for you.

[image of a unicorn]

### Text Conversation

Command: "tell me a joke"

Output: Okay, here is a joke for you.

Q: What do you call a fish that wears a bowtie?

A: Sofishticated.
