# VocaWild 🐾
### Live Animal Voice Detection System

VocaWild is a real-time animal voice detection system that continuously listens to live microphone input and identifies animal sounds using machine learning and audio signal processing techniques.

The system is trained on a structured dataset where each animal has a dedicated folder containing multiple audio samples. During execution, the application captures live audio until manually stopped and predicts the corresponding animal whenever a sound is detected.

## Supported Animals
Lion, Bear, Cat, Chicken, Cow, Dog, Dolphin, Donkey, Elephant, Frog, Horse, Monkey, Sheep

## Technologies Used
- Python
- Librosa (audio feature extraction)
- scikit-learn
- SoundDevice
- NumPy

## How It Works
1. Audio dataset organized by animal name
2. MFCC feature extraction from audio samples
3. Machine learning model training
4. Continuous live microphone listening
5. Real-time animal voice prediction

## Usage
```bash
python train_model.py
python live_detect.py
