import Image from 'next/image';

# Minecraft-Three.js

A **browser-based Minecraft clone** powered by **Three.js** and **TypeScript**, offering endless exploration, block-building, and fun!

## 🚀 Demo

Try it here: [Minecraft - Three.js](https://minecraft-threejs-main.vercel.app/)

For the best experience, use **Google Chrome**.

<Image
  src="https://user-images.githubusercontent.com/88306344/154383952-9b33bad4-eebb-4a98-a12e-f5f137422d06.gif"
  alt="Minecraft Three.js Preview"
  width={800}
  height={400}
/>

---

## ✨ Features

### ✔️ Currently Supported

- **Block Placement & Destruction**: Build and reshape your world at will.
- **Block Selection**: Switch block types with the mouse wheel or number keys.
- **Player Movement & Collision**: Move freely while adhering to terrain constraints.
- **Randomized Terrain**: Enjoy procedurally generated landscapes and trees.
- **Infinite World**: Seamlessly explore a limitless environment.
- **Save/Load Game**: Preserve your progress and pick up where you left off.
- **Audio Effects**: Immerse yourself with sound effects and background music.
- **Customizable Rendering**: Adjust render distance and field of view for optimal performance.
- **Highlighted Blocks**: Precisely target blocks with a crosshair.
- **Responsive UI**: Navigate through a minimal, intuitive interface.
- **Mobile & Desktop Compatibility**: Play on any device!

### 🔧 In Development

- **Optimized Algorithms**:
  - Time-slice rendering for smoother performance.
  - Improved block placement/destruction logic.
- **Water Features**: Dynamic water generation for enhanced realism.
- **Multiplayer Mode**: Connect and play with others online.

---

## 🛠️ Setup

Follow these steps to run the project locally:

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v16 or later recommended)
- **npm** (comes with Node.js)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/minecraft-threejs.git
   cd minecraft-threejs
   ```

2. **Install Dependencies**:
    ``bash
    npm install
    ```

3. **Run the Development Server**:

    ```bash
    npm run dev
    ``


Open in Browser: Navigate to http://localhost:3000 (or the port displayed in your terminal).

4. **Build for Production**:

```bash
npm run build
```
5. **Preview Production Build**:
    ```bash
    npm run preview
    ```
