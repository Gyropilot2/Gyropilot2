# Hi, I'm Alison Sanches Krinski
### Technical Game Designer | Unreal Engine 5 | Gameplay Systems & Implementation
📍 *Curitiba, Brazil (Remote)* | 🗣️ *English (Fluent) & Portuguese (Native)*

💬 **Discord:** `gyropilot`
📧 **Email:** alisonskrinski@gmail.com

**Quick Links:**
* 📄 **[Download Resume (PDF)](https://drive.google.com/drive/folders/15HxNB2A7KWy2dLUearuRZGNfE2DYE2qX)**
* 🎮 **[Forgotten Eras (Steam)](https://store.steampowered.com/app/3423760/Forgotten_Eras/)**
* 💼 **[LinkedIn Profile](https://www.linkedin.com/in/alison-krinski)**

---

### 📑 Table of Contents
* [🚀 About Me](#-about-me)
* [🛠️ Technical Skills](#%EF%B8%8F-technical-skills)
* [💼 Professional Experience](#-professional-experience)
* [🧩 Technical Showcase (GIFs)](#-technical-showcase-gifs)

---

### 🚀 About Me
I am a **Technical Game Designer** with **6+ years** of experience in 3D pipelines and **2+ years** of specialized development in Unreal Engine. I focus on asset integration, clean system architecture, and creating efficient developer tools.

---

### 🛠️ Technical Skills

**Programs:**
* ![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=flat&logo=unrealengine&logoColor=white) **Unreal Engine** (Blueprints, UMG, Niagara, Chaos)
* ![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=flat&logo=blender&logoColor=white) **Blender** (Modeling, Rigging, Animation, Shaders)
* ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) **Git / Source Control**
* ![Jira](https://img.shields.io/badge/Asana-F06B07?style=flat&logo=asana&logoColor=white) **Asana / Task Tracking**
* ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?logo=visualstudiocode&logoColor=fff&style=plastic) **VS Code** 

**Core Competencies:**
* **Blueprint Architecture:** I apply strict **Object-Oriented Programming (OOP)** principles to Visual Scripting. My code is encapsulated, modular, and self-documenting. I prioritize clean, readable logic that the entire team can understand and maintain.
* **System Implementation:** I specialize in architecting functional gameplay frameworks. I focus on logic and data structures, creating systems that are error-resistant and reduce technical debt.
* **3D Background:** Having worked with 3D modeling, animation, and the technical challenges inherent to the pipeline, I possess the experience to find the best approach for asset implementation and performance optimization.
* **Technical Art & Tools:** I build procedural tools to assist the Level Design process. I am also proficient in **Niagara VFX System (including Simulation Stages)** and Material logic for VFX behavior implementation.
* **Pipeline Stability:** I act as Technical QA for the team. This involves debugging packaging failures, fixing asset animation incompatibilities, and identifying gameplay soft-locks to ensure the build remains at a high quality standard.
* **Technical Foresight:** I possess a strong intuition for identifying structural bottlenecks, logic conflicts, and gameplay issues before implementation begins. I anticipate how systems will scale, preventing technical debt and costly refactors.

**Additional Skills:**
* **Math & Logic:** Strong proficiency in math operations and code logic for creating elegant and efficient solutions.
* **AI Design:** Experienced with BehaviorTrees, EQS, and UtilityAI logic.
* **Communication:** Transparent reporting of progress, limitations, and a willingness to listen to expert feedback.
* **Workflow:** Disciplined remote worker with a focus on clear documentation, Git version control, and Asana task tracking.

---

### 💼 Professional Experience

#### **Technical Game Designer @ [Behind The Hump](https://www.linkedin.com/company/behind-the-hump/)**
*(August 2024 – Present)*
> Key developer for **[Forgotten Eras](https://store.steampowered.com/app/3423760/Forgotten_Eras/)**, a playable demo released on Steam.

* **Gameplay Programming:** Engineered clear, encapsulated Blueprint systems for Single-Player gameplay, utilizing Interfaces and Actor Components to ensure code modularity and scalability.
* **Technical Design:** Created procedural tools using Instanced Static Meshes and Chaos Destruction to assist the Level Design process. Created VFX and dynamic materials. Implemented Clothing Physics and resolved mesh and animation incompatibility issues.
* **Technical Support & QA:** Diagnosed and resolved game-breaking bugs, gameplay softlocks, and implemented user-experience adjustments.
* **Documentation & Workflow:** Maintained comprehensive technical documentation for all implemented tools and systems. Ensured smooth remote collaboration via English voice chat meetings and organized task tracking (Asana).

#### **Freelance 3D Generalist & Gameplay Developer**
*(June 2019 – Present)*

* **3D Pipeline Experience:** Studied and practiced the full asset pipeline in Blender—covering modeling, rigging, animation, and shaders. Gained a practical understanding of the difference between rendering vs. game-ready assets.
* **Modding:** Tackled unique technical issues across various games (e.g., Kenshi, Project Zomboid). Overcame limitations of having little to no modding support, requiring creative solutions and reverse-engineering to extract assets and inject code.
* **Game Design Documents (GDD):** Wrote detailed Game Design Documents for personal projects. Focused on breaking down mechanics, defining specific control schemes, and mapping out object communication to understand scope and limitations before coding.
* **Unreal Engine Development:** Explored many Unreal Engine features like Behavior Trees, Widgets, Niagara VFX System, and Animation Blueprints. Learned Object Oriented Programming fundamentals and their Visual Scripting implementation methods.

---

### 🧩 Technical Showcase (GIFs)

## 🛠️ Unreal Engine Systems & Tools
<table>
  <tr>
    <td width="50%" valign="top">
      <h4>1. Tactical AI Flanking System (EQS)</h4>
      <p>Implemented using Behavior Trees and Environment Query System (EQS). Agents dynamically calculate flanking vectors, line-of-sight, and cover considerations to encircle opponents in real-time.</p>
      <img src="https://github.com/Gyropilot2/Gyropilot2/blob/main/EQS%20Sample.gif?raw=true" width="100%" alt="EQS AI">
    </td>
    <td width="50%" valign="top">
      <h4>2. Modular Building System</h4>
      <p>A State-Machine architecture driven centrally by the Main Widget handling the logic flow for mode transitions and making sure every object is valid. A child ConstructionMode Widget manages ghost actor collision validation and the Undo/Redo stack.</p>
      <img src="https://github.com/Gyropilot2/Gyropilot2/blob/main/Building%20System%20Sample.gif?raw=true" width="100%" alt="Building System">
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>3. Procedural Spline Tools</h4>
      <p>Editor Utility for rapid Level Design. Uses Splines to drive procedural Instanced Static Mesh (ISM) placement. Includes a custom minecart spawner with fully exposed parameters for quick iteration.</p>
      <img src="https://github.com/Gyropilot2/Gyropilot2/blob/main/Spline%20Tool%20Sample.gif?raw=true" width="100%" alt="Spline Tool">
    </td>
    <td width="50%" valign="top">
      <h4>4. Universal Camera Manager</h4>
      <p>A modular <code>APlayerCameraManager</code> extension built with strict OOP encapsulation to ensure universal compatibility across different projects. Features predictive wall-trace occlusion, velocity smoothing, and weighted interest interpolation.</p>
      <img src="https://github.com/Gyropilot2/Gyropilot2/blob/main/CameraManager%20Sample.gif?raw=true" width="100%" alt="Camera System">
    </td>
  </tr>
</table>

## 🎨 Tech Art & VFX
<table>
  <tr>
    <td width="50%" valign="top">
      <h4>1. GPU-Accelerated Cellular Automata</h4>
      <p>Simulates Conway's Game of Life entirely on the GPU using Niagara Simulation Stages. Demonstrates performant read/write operations on Grid2D collections.</p>
      <img src="https://github.com/Gyropilot2/Gyropilot2/blob/main/GameOfLife%20Sample.gif?raw=true" width="100%" alt="Niagara Game of Life">
    </td>
    <td width="50%" valign="top">
      <h4>2. Gameplay VFX Showcase</h4>
      <p>A Niagara attack sample demonstrating particle timing, ground alignment, and impact feedback. Designed to be visually distinct and readable for gameplay purposes.</p>
      <img src="https://github.com/Gyropilot2/Gyropilot2/blob/main/VFX%20Sample.gif?raw=true" width="100%" alt="Ice Attack VFX">
    </td>
  </tr>
</table>

## 🧊 3D Modeling & Additional Works
<table>
  <tr>
    <td width="33%" valign="top">
      <h4>⚙️ Mechanical Engineering</h4>
      <p><b>Functional Prosthetic Assembly</b><br>
      High-fidelity, print-ready mechanical model designed with accurate joint constraints. Commissioned engineering work.</p>
      <img src="https://github.com/Gyropilot2/Gyropilot2/blob/main/Prosthetic%20Sample.gif?raw=true" width="100%" alt="Prosthetic Arm">
    </td>
    <td width="33%" valign="top">
      <h4>🔧 Advanced Modding</h4>
      <p><b>Legacy Engine Injection</b><br>
      Overcame the lack of documentation and rigid restrictions in engines like Kenshi (Ogre) and Zomboid (Java). Solved invisible meshes, broken hierarchies, and file format issues without official tools.</p>
      <img src="https://github.com/Gyropilot2/Gyropilot2/blob/main/Kenshi%20Modding%20Sample.gif?raw=true" width="100%" alt="Kenshi Modding">
    </td>
    <td width="33%" valign="top">
      <h4>📺 Visual Identity</h4>
      <p><b>Vaporwave Animation Loop</b><br>
      High-fidelity looped animation focusing on retro-futuristic aesthetics. Demonstrates a strong grasp of composition, lighting, and style consistency.</p>
      <img src="https://github.com/Gyropilot2/Gyropilot2/blob/main/Vaporwave%20Animation%20Sample.gif?raw=true" width="100%" alt="Blender Render">
    </td>
  </tr>
</table>

---
