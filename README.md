# Black Hole Simulation in Blender (Crna Rupa 3D)  
**Author:** Antun Abičić, MiR (Sveučilište Josipa Jurja Strossmayera in Osijek)
**Project Type:** Educational / Visualization / Simulation  

## 🌌 Overview  
This repository contains a 3D simulation of a black hole created using **Blender**. The project aims to replicate a realistic gravitational lensing effect and accretion disk, inspired by the scientific visualization used in the movie **Interstellar**.

The main goal was to simulate a black hole using **physically accurate ray tracing techniques**, rendering realistic effects caused by extreme gravity such as light bending and relativistic distortions.

Presentation of the project can be viewed via youtube link below or via compressed video located in video_presentation folder on github.
> 🎥 **Presentation Video:** [Watch on YouTube](https://www.youtube.com/watch?v=hKKKDw-CXUk)

---

## 🚀 Features  
- Realistic **gravitational lensing** (light bending around the black hole)  
- Visually accurate **accretion disk**  
- Based on scientific references and high-quality Blender rendering  
- Inspired by the visualization in *Interstellar (2014)*  

---

## 📦 How to Use  

### 1. Clone the Repository  
```bash
git clone https://github.com/AntTAnt092/CrnaRupa3Dracunalna.git
cd CrnaRupa3Dracunalna
```

### 2. Project Structure  
After cloning, the folder structure will look like this:

```
CrnaRupa3Dracunalna/
├── background/             # HDRI space backgrounds used in the scene
├── blackhole_animations/  # Rendered animations of the black hole simulation
├── blender_file/          # Main Blender (.blend) project file
├── presentation/          # PowerPoint about the project
├── video_presentation/    # Exported compressed video presentation 
├── README.md              # Project documentation
```

### 3. Opening and Rendering the Simulation  
- Open the `.blend` file from the `blender_file/` folder using **Blender 3.x or later**
- Press `F12` to render a frame  
- Explore the `Shader Editor` and `Compositing` tabs to inspect how gravitational lensing is implemented    

### 4. Viewing the Presentation   
- The `video_presentation/` folder contains a screen-recorded explanation of the project
- The `presentation/` contains PowerPoint presentation used in screen-recorded explanation

### 5. Background Assets  
- HDRI files located in the `background/` folder can be replaced or modified via **World Settings > Environment Texture** in Blender

---

## 🛠 Methodology  
- Learned Blender techniques through extensive tutorials  
- Studied black hole physics, gravitational lensing, and accretion disks  
- Implemented ray tracing techniques using Blender’s built-in **Cycles Renderer**  
- Used high-resolution HDRI background for realism  

---

## 🔗 Resources & References  
- 🔭 Gravitational lensing: [Wikipedia](https://en.wikipedia.org/wiki/Gravitational_lens)  
- ☄️ Accretion disk: [Wikipedia](https://en.wikipedia.org/wiki/Accretion_disk)  
- 🧠 Scientific accuracy inspiration: [CERN Courier – Building Gargantua](https://cerncourier.com/a/building-gargantua/)  
- 📹 Tutorial used: [YouTube - Beginner Blender Tutorial - Full Course](https://www.youtube.com/watch?v=4haAdmHqGOw)  
- 🌌 HDRI background: [Freepik - Milky Way](https://www.freepik.com/free-photo/milky-way_1179901.htm)  

---

## 🔮 Future Improvements  
If more time were available, the following enhancements could be implemented:  
- Higher-detail accretion disk with particle effects and dynamic flow  
- Implementation of **Doppler shift effect**, where the color of light changes based on the observer’s position relative to the black hole 
- Animation of camera movement to simulate flyby or orbit around the black hole  
- Use of custom GLSL shaders for more accurate relativistic rendering  

---

## 📬 Contact  
For questions or collaboration:  
**Antun Abičić** – *Student, MiR program (Sveučilište Josipa Jurja Strossmayera in Osijek)*  
Email for contant: antunabicic668@gmail.com
*Feel free to open issues or suggestions directly on this GitHub repository.*
