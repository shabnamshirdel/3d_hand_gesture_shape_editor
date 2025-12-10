### 3D Hand Gesture Editor

![3D hand gesture editor screenshot](./3d_hand_gesture_editor.png)

Edit 3D shapes with natural hand gestures.

* Right hand: "Pinch" to grab/move a corner of the cube.
* Right hand: "Pinch" and drag in the color wheel.
* left hand: Make a "fist" and move to rotate the shape.

Built with `threejs` / `WebGL` / `MediaPipe`.


### Setup for Development

Navigate to the project sub-folder in terminal:
```bash
cd 3d_hand_gesture_editor
```

In the terminal, type below command:
```bash
python3 -m http.server
```
Use your browser and go to:
```bash
http://localhost:8000
```
Note: Please clear your browser cache before entering the address.

### Requirements

- Modern web browser with WebGL support
- Camera access

### Technologies

- **Three.js** for 3D rendering
- **MediaPipe** for hand tracking and gesture recognition
- **HTML5 Canvas** for visual feedback
- **JavaScript** for real-time interaction
