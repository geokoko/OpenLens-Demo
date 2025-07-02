# OpenLens SmartGlasses

Open Source Smart Glasses, aiming to aid people with communicational disabilities. This project was built for the PreECESCON 8 Competition in Xanthi. 

The current version of this repository includes a demo showcasing how the facial emotion recognition system would function when deployed on the glasses.

The model implementation is inspired by this [paper](https://arxiv.org/pdf/1902.01019). 

The datasets used to train the custom CNN are [FER 2013](https://paperswithcode.com/dataset/fer2013) and [Affectnet](https://paperswithcode.com/dataset/affectnet).

## Minimal Setup Guide

1. **Clone the repository**
   ```bash
   git clone https://github.com/geokoko/OpenLens-Demo.git
   cd OpenLens-Demo
   ```

2. **Set up a Python environment** (optional but recommended)
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Download the pre-trained model weights** (links to be added)
   ```bash
   mkdir models
   # Place .h5 model files inside the models directory
   ```

5. **Run the demo**
   ```bash
   python demo.py --camera 0 --model models/<your_model>.h5
   ```
