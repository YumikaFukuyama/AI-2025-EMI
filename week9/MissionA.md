# MISSION　Ａ
### **Objective:**
Students will deeply engage with the “DronePaint” paper, use ChatGPT to accelerate comprehension of AI components, synthesize a concise summary, and deliver a clear 3-minute presentation, 
reinforcing both technical understanding and creative STEAM thinking.

### **result:**
This paper proposes DUIR, a Dynamic Universal Image Restoration system designed to handle multiple distortions—such as blur, noise, and compression—using a single model. 
Traditional approaches require separate models for each distortion, but DUIR uses a Distortion Embedding Module (DEM) to identify distortion types, 
and a Distortion Attention Module (DAM) with bi-directional LSTM to guide the restoration process.
The main restoration network, DAIR-DCNN, uses Semi-Dynamic Layers (SDLs) to adapt its parameters dynamically. 
Experiments show DUIR outperforms existing methods on both synthetic and real-world data, offering an efficient and versatile solution for image restoration tasks.

### Reference Questions for Learning
- **In two sentences, what is DronePaint?**

DronePaint is an interactive system that enables users to control a swarm of drones using hand gestures, recognized by a deep neural network.
The drones are equipped with lights and coordinate in real time to create dynamic light paintings in the sky.

- **How do hand gestures move the drones?**

Hand gestures are captured by a camera and interpreted by a deep neural network trained to recognize specific movements.
These recognized gestures are then translated into flight commands, allowing users to intuitively control the position, formation, and motion of the drone swarm in real time.

- **What is the system archtecture?**

1. Gesture Recognition Module: Uses a deep neural network to detect and classify hand gestures from a video stream in real time.
   
2. Swarm Control Module: Translates recognized gestures into coordinated flight commands for the drone swarm, ensuring smooth and synchronized movement.
   
3. Light Painting Module: Controls the drones' onboard lights to produce visual patterns and drawings, based on the trajectories generated from user input.

Together, these modules enable seamless human-swarm interaction for creative light-based performances.
  
- **Why do we smooth my hand’s path before flying?**

Smoothing your hand’s path before flying helps to eliminate small, unintended jitters or fluctuations in your gesture.
This ensures the drones follow a stable and fluid trajectory, resulting in more accurate and visually appealing light paintings.
  
- **Three simple metaphors for LightPaint?**

1. Airborne Paintbrush: Like painting on a canvas, but your hand guides glowing drones that draw in the sky.

2. Sky Calligraphy: Your gestures are like strokes of a pen, and the drones write glowing letters across the night.

3. Digital Fireflies: The drones act like trained fireflies, dancing in patterns that reflect your hand movements.
  




