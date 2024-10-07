# Avataar_Assignment_HB1 - Dissecting Image Generation
# Stable Diffusion Image Generation Pipeline with ControlNet


## Overview
This project is a structured evaluation and review of controlled image generation with Stable Diffusion guided by ControlNet. Metadata comes in the form of text prompts and depth maps to be converted into descriptive images with photorealism. We experiment with different types of conditioning with the object of benchmarking the quality of the generated images at varying aspect ratios.


## Tasks and Deliverables

### Task 1: Generate Best-Quality Images
Using the metadata provided, images were generated using Stable Diffusion with ControlNet. Several conditioning techniques were applied to improve image quality, including combining depth maps with canny and normal maps where applicable.

### Task 2: Generate Images at Different Aspect Ratios
We tested different aspect ratios (1:1, 16:9, 4:3, and 9:16) and analyzed the image quality, comparing results with the default 1:1 ratio optimized for Stable Diffusion.

### Task 3: Analyze Generation Latency
The generation latency was recorded and optimized using techniques such as reducing inference steps and enabling memory-efficient attention. The effects on latency and quality were evaluated.


## Running the Code

**Clone the repository**:
   git clone https://github.com/username/repo-name.git
   cd repo-name
