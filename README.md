# **3D Space Adventure**  
**Name:** Vinay Kumar  
**Roll No.:** B22CS062  

A **3D space-themed game** built using **PyOpenGL**, featuring an immersive **third-person and first-person gameplay experience**.  

---

## **Game Overview**  

Embark on a thrilling **space adventure** where you pilot a **transporter** through the vast cosmos. Navigate through challenging obstacles, evade enemy ships, and make your way to the **space station**. The game offers:  

✔ **First-Person and Third-Person Modes**  
✔ **Laser Combat System**  
✔ **Minimap Arrow for Navigation**  
✔ **Realistic Space Movement and Controls**  

---

## **System Requirements**  

Ensure you have **Python 3.8+** installed along with the required dependencies.  

### **Install Dependencies**  

Run the following command to install the necessary libraries:  

```sh
pip install PyOpenGL glfw numpy imgui[glfw]
```

## **How to Play**  
### **Launching the Game**
1. Clone this repository or download the ZIP file:
```sh
git clone https://github.com/vinaykumar/3D-Space-Adventure.git  
cd 3D-Space-Adventure  
```
2. Start the game:
```sh
python main.py  
```

## **Controls**  
### **Third-Person Mode:**
W – Pitch Down
S – Pitch Up
A – Yaw Left
D – Yaw Right
Q – Roll Left
E – Roll Right
SPACE – Accelerate Forward
LEFT SHIFT – Decelerate


### **First-Person Mode:**
RIGHT CLICK – Switch to First-Person View
LEFT CLICK – Fire Laser

## **Game Screens**  
Main Menu: Start a new adventure.
Game Over Screen: Displayed when the transporter crashes or is destroyed.
Victory Screen: Appears when you successfully reach the space station.

## **Project Structure**  
📂 main.py – Entry point of the game.
📂 game.py – Core gameplay logic.
📂 window_manager.py – Handles game window and input.
📂 objects.py – Loads and manages 3D objects.
📂 graphics.py – Responsible for rendering and visuals.
📂 shaders.py – Defines shaders for lighting and effects.

## **Credits & Technologies**  
This project was built using:
✅ PyOpenGL – For 3D graphics rendering.
✅ GLFW – For window and input management.
✅ NumPy – For mathematical operations.
✅ ImGui – For UI elements.