# Single-Frame-Video-Captioning-using-BLIP-2-Model

I built a simple video captioning pipeline using the BLIP-2 model. Since my input videos were very short (5–10 seconds), I extracted a single representative frame from each video using OpenCV—specifically, the middle frame. I then passed this frame to the BLIP-2 image captioning model from Hugging Face to generate a natural language description. The process was done in Google Colab using 8-bit and float16 settings for better memory efficiency.
