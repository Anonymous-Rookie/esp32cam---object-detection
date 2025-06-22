# ESP32CAM---object-detection

This is a beginner-friendly project where I used an ESP32-CAM and Edge Impulse to detect objects. Here I have used a pencil and a sharpener for the basic detection purpose.

## 💡 What it does:
- Takes pictures with ESP32-CAM
- Uses a trained ML model to detect objects (pencil/sharpener)
- Shows result in serial monitor

## 🔧 Tools I used:
- ESP32-CAM
- Edge Impulse (for training)
- Arduino IDE (to upload code)

## 🚀 How to use:
1. Train your model on Edge Impulse
2. Export the `.eim` model file for ESP32
3. Upload the Arduino sketch from this repo
4. Open Serial Monitor at 115200 baud to see results

## 📝 Notes:
- This was my first object detection project!
- so I will include how to build the model below

## 🧠 Edge Impulse Model

### How I created the model:
1. Collected images of a **pencil** and a **sharpener** using Edge Impulse Data Acquisition.
2. Labeled the objects in the images.
3. Trained an **Object Detection** model.
4. Exported the model as a `.eim` file (ESP32 format).

### How you can do it too:
- Go to [Edge Impulse](https://studio.edgeimpulse.com/)
- Create a new project
- Collect images using your webcam or upload them
- Train an object detection model
- Go to **Deployment** → Export as **ESP32 (.eim)** file

