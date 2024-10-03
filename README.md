# GIF-QA
Our solution (Group 8) to the ML Prep-A-thon PS for 13th Inter IIT Tech Meet
A Model which processes a GIF and performs Visual Question Answering on the GIF.

## Proposed Architecture
![Model_Architecture](https://github.com/Shubham-Mate/GIF-QA/blob/main/WhatsApp%20Image%202024-10-03%20at%2021.33.23(1).jpeg)

## Pretrained Models used:
 * Llama 3.2 3B as the decoder LLM
 * XCLIP Patch-32 as the video encoder

## Parts of Model trained:
 * Llama 3.2 3B was finetuned using LoRA with Quantization
 * The MLP Connective Adapter Layer was trained using standard backpropogation

## Dataset:
 * TGIF-QA
 * TGIF-Description

# Training Hardware
The model was trained on a P100 GPU on Kaggle

# Checkpoint File
![Click Here](https://drive.google.com/file/d/1BY-I5nA_sItvN4l167xCgdmfrOjKnFGB/view?usp=sharing)
