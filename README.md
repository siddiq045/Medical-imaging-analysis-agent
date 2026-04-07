# Medical Imaging Analysis Agent

An AI-based application that analyzes medical images such as X-rays, MRIs, CT scans, and ultrasounds using a multimodal large language model.

## Overview
This project allows users to upload medical images and receive structured insights including image type, key observations, and potential abnormalities. The system leverages Google's Gemini model for multimodal understanding.

## Features
- Detects type of medical scan (X-ray, MRI, CT, Ultrasound)
- Identifies anatomical regions
- Highlights key findings and possible abnormalities
- Generates structured diagnostic insights
- Provides simplified explanations for better understanding

## Tech Stack
- Python
- Streamlit (UI)
- Google Gemini API (Multimodal AI)
- Agno Agent Framework

## How It Works
1. User uploads a medical image
2. The image is processed and sent to the Gemini model
3. The model analyzes the image using structured prompts
4. Results are displayed with findings and explanations

## Setup Instructions
```bash
pip install -r requirements.txt
streamlit run ai_medical_imaging.py