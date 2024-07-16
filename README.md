# face_emotion-recognition
Facial emotion recognition is the process of detecting human emotions from facial expressions. 
AI can detect emotions by learning what each facial expression means and applying that knowledge to the new information presented to it.

STEPS TO RUN:
1. Install pytorch:  pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu117  (command prompt windows)
2. Install openCV: pip install opencv-python
3. Install Facial Emotion recognition: pip install facial-emotion-recognition
4. Configuring pytorch for CPU: Open ./site-package/torch/serialization.py and Change:  def load(f, map_location=None, pickle_module=pickle, **pickle_load_args):
   to  def load(f, map_location='cpu', pickle_module=pickle, **pickle_load_args):

5. Download and run the emotionRecognition(1).py in any python code editor.
