# AirCanvas
This is a project that helps to create images thru hand gestures from a basic laptop camera.

💡 Core Concept: Use only the webcam and hand gestures to draw on a virtual canvas — no hardware, no touchscreen. It’s like an invisible whiteboard controlled by the user fingers. 

✋ Core Gesture Examples, we can change them as progress: Gesture Action Index Finger Up Draw on the canvas Two Fingers Up (V) Cycle through colors Three Fingers Up Cycle through brush sizes Circle Gesture Clear the canvas Palm Open Pause drawing You can also add thumbs-up to save the drawing as an image. 

🧠 Why It’s Unique: - 
- No special equipment (just a webcam)
- Natural, intuitive controls
- Great blend of computer vision + creativity
- Very shareable
- people love seeing air-drawing on video
- Can be extended with AI features later (e.g., shape recognition, style transfer)

🛠️ Tech Stack Suggestions: 
- Python + OpenCV – video capture, drawing, and gesture processing 
- MediaPipe Hands – robust, lightweight hand and finger tracking 
- Tkinter or Pygame – to create a visual canvas 
- Optional: NumPy for drawing logic or storing canvas data 
- Optional: OpenCV gestures for custom gesture recognition (e.g., circle detection) 

🧩 Suggested Features to Add: 
- Dynamic Brush Styles – switch between pen, spray, highlighter 
- Auto Shape Snap – draw a rough circle, it auto-snaps to a perfect one 
- Live Recording – export a timelapse of your air-drawing process 
- Gesture-based Undo/Redo – swipe left/right to undo/redo 
- Face-triggered UI – raise eyebrows to bring up color palette! 

🖼️ Output Example: 

The user waves two fingers to bring the color palet to visibility, to pick the color with thumb and index finger. Then uses middle finger to draw a smiley face in the air. It appears in real-time on a canvas overlay window. 

🧪 Bonus Modes (Stretch Goals): 
- **AR Mirror Mode**: Show the user’s reflection with the drawing layered on top (like a Snapchat filter) 
- **Game Mode**: Draw specified objects in the air and have the system guess them (like a Pictionary AI) 
- **Kids Mode**: Bigger brushes, fun colors, sound effects, and animal stamps
