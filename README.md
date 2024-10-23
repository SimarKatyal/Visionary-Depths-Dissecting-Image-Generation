# Visionary Depths | Dissecting Image Generation
# Stable Diffusion Image Generation Pipeline with ControlNet


## Overview
Visionary Depths is a comprehensive evaluation of controlled image generation utilizing Stable Diffusion and guided by ControlNet. This project leverages metadata, including text prompts and depth maps, to create descriptive and photorealistic images. Through rigorous experimentation with various conditioning techniques, we benchmark the quality of generated images across different aspect ratios, providing insights into the efficacy of these methods.


## Objectives
1. To generate high-quality images from text prompts and depth maps.
2. To explore the impact of different aspect ratios on image quality.
3. To analyze and optimize generation latency for improved efficiency.


## Tasks and Deliverables

### Task 1: Generate Best-Quality Images
Utilized Stable Diffusion combined with ControlNet to generate images based on the provided metadata. Employed conditioning techniques such as integrating depth maps with Canny edges and normal maps to enhance visual fidelity.

### Task 2: Generate Images at Different Aspect Ratios
Tested image generation across multiple aspect ratios: 1:1, 16:9, 4:3, and 9:16. Compared the quality of images generated at these ratios against the standard 1:1 aspect ratio, evaluating how changes in dimensions affect the overall output.

### Task 3: Analyze Generation Latency
Measured the time taken for image generation under various configurations. Implemented strategies such as reducing inference steps and enabling memory-efficient attention to decrease latency. Discussed the trade-offs between latency reduction and image quality preservation.


## Running the Project Locally

**Clone the repository**:
git clone https://github.com/username/repo-name.git
cd repo-name

**Installing Required Dependencies**:
pip install -r requirements.txt

**Running the Image Generation Pipeline**:
python main_script.py

