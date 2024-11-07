# talkinghead
A Talking Head to describe the scene captured from a Webcam

Steps:
*   Capture an image using the webcam
*   Use moondream2 VLM to describe the image or for VQA
*   Clone a source reference voice using TTS (xtts2) model
*   Generate speech for the text output from moondream2 using the cloned voice
*   Animate a reference image (a head portrait) driven by the above audio using LivePortrait Talker 
