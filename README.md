# Modern 3D Landing UI Interactive IPhone 15 Pro Page - React Website

![Screenshot 2025-07-30 at 14 44 39](https://github.com/user-attachments/assets/89d167f9-90e5-420d-b79c-86bde2df42f7)
![Screenshot 2025-07-30 at 14 45 01](https://github.com/user-attachments/assets/0f82cb68-5fcb-47aa-921c-356d1c1ee9e8)
![Screenshot 2025-07-30 at 14 45 26](https://github.com/user-attachments/assets/b615a648-89b5-4257-829c-e1c073ef3be5)
![Screenshot 2025-07-30 at 14 45 50](https://github.com/user-attachments/assets/1a876950-53e2-4e2a-8bee-4eb7867afce3)
![Screenshot 2025-07-30 at 14 46 01](https://github.com/user-attachments/assets/565e5aea-dcb0-4e18-b553-6d7399dea815)
![Screenshot 2025-07-30 at 14 46 16](https://github.com/user-attachments/assets/48900118-c3b5-4cf5-841f-6adb612994e6)
![Screenshot 2025-07-30 at 14 46 41](https://github.com/user-attachments/assets/3a768b56-3d0d-4c24-ace8-885c7179c224)

---

## Project Overview

This project is a modern, interactive ReactJS website inspired by the Apple iPhone 15 Pro Max product page. It showcases advanced UI/UX, 3D model integration, smooth animations, and responsive design. The site is built for learning, demonstration, and as a template for high-quality product landing pages.

- **Live-Demo:** [https://modern-iphone-3d-ui.netlify.app/](https://modern-iphone-3d-ui.netlify.app/)

---

### Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technology Stack](#technology-stack)
4. [Project Structure](#project-structure)
5. [Components & Reusability](#components--reusability)
6. [How to Run](#how-to-run)
7. [Deployment](#deployment)
8. [Usage & Walkthrough](#usage--walkthrough)
9. [Keywords](#keywords)
10. [Conclusion](#conclusion)

---

## Features

- **3D iPhone Model**: Interactive, color and size selection using Three.js and react-three-fiber.
- **GSAP Animations**: Smooth scroll-based and timeline animations for engaging transitions.
- **Video Highlights**: Carousel of product highlight videos with animated progress indicators.
- **Responsive Design**: Mobile-first, fully responsive layout using Tailwind CSS.
- **Sentry Integration**: Error tracking and performance monitoring.
- **Reusable Components**: Modular React components for easy extension and reuse.
- **Netlify Ready**: SPA routing and deployment configuration for Netlify.

---

## Technology Stack

- **ReactJS**
- **Vite** (build tool)
- **Tailwind CSS**
- **GSAP** (GreenSock Animation Platform)
- **Three.js** & **@react-three/fiber**
- **@react-three/drei** (3D helpers)
- **Sentry** (monitoring)
- **Netlify** (deployment)

---

## Project Structure

```bash
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
├── netlify.toml
├── public/
│   └── assets/
│       ├── images/ (SVGs, JPEGs)
│       └── videos/ (MP4s)
│   └── models/
│       └── scene.glb
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   ├── constants/
│   │   └── index.js
│   ├── utils/
│   │   ├── animations.js
│   │   └── index.js
│   └── components/
│       ├── Navbar.jsx
│       ├── Hero.jsx
│       ├── Highlights.jsx
│       ├── VideoCarousel.jsx
│       ├── Model.jsx
│       ├── ModelView.jsx
│       ├── IPhone.jsx
│       ├── Features.jsx
│       ├── HowItWorks.jsx
│       ├── Lights.jsx
│       ├── Loader.jsx
│       └── Footer.jsx
```

---

## Components & Reusability

Each component is modular and can be reused in other React projects:

- **Navbar**: Responsive navigation bar with Apple branding and links.
- **Hero**: Main product showcase with video and CTA.
- **Highlights**: Section with animated video carousel and highlight texts.
- **Model**: Interactive 3D iPhone model with color/size selection.
- **Features**: Storytelling section with images, video, and animated text.
- **HowItWorks**: Explains the A17 Pro chip with visuals and video.
- **Footer**: Informational footer with links and copyright.

To reuse a component, import it in your React project and provide necessary props (see each file for details). For example:

```jsx
import Model from './components/Model';

<Model />
```

---

## How to Run

1. **Clone the repository:**

   ```sh
   git clone <your-repo-url>
   cd iphone
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Start the development server:**
  
   ```sh
   npm run dev
   ```

4. **Open in browser:**
   Visit `http://localhost:5173` (or as shown in terminal)

---

## Deployment

This project is ready for Netlify deployment. The `netlify.toml` file ensures SPA routing works smoothly.

1. **Build the project:**

   ```sh
   npm run build
   ```

2. **Deploy to Netlify:**
   - Drag and drop the `dist` folder in Netlify dashboard, or connect your GitHub repo.
   - All routes will redirect to `index.html` for client-side navigation.

---

## Usage & Walkthrough

### Main Flow

1. **Navbar**: Top navigation with Apple logo, search, and bag icons.
2. **Hero Section**: Displays iPhone 15 Pro with responsive video and CTA button.
3. **Highlights**: Animated carousel of product highlight videos and texts.
4. **Model**: Interactive 3D iPhone model. Users can select color and size.
5. **Features**: Story-driven section with images and video.
6. **How It Works**: Details about the A17 Pro chip with visuals and video.
7. **Footer**: Informational links and copyright.

### Animations

- GSAP powers scroll and timeline animations for smooth transitions.
- Video carousel uses GSAP for progress indicators and transitions.

### 3D Model

- Uses Three.js via @react-three/fiber and @react-three/drei.
- Model is loaded from `/public/models/scene.glb`.
- Color and size selection updates the model in real-time.

### Error Monitoring

- Sentry is integrated for error tracking and performance monitoring.

---

## Keywords

ReactJS, Vite, Tailwind CSS, GSAP, Three.js, @react-three/fiber, @react-three/drei, Sentry, Netlify, SPA, 3D Model, Animation, Product Landing Page, Apple, iPhone, UI/UX, Responsive Design, Modular Components, Error Monitoring

---

## Conclusion

This project demonstrates how to build a modern, interactive product landing page using React, 3D graphics, and advanced animations. All components are reusable and the codebase is well-structured for learning and extension. Use this as a template for your own product pages or to learn best practices in React and 3D web development.

---

## Happy Coding! 🎉

Feel free to use this Project Repository and extend this project further!  

If you have any questions or want to share your work, reach out via GitHub or my portfolio [https://arnob-mahmud.vercel.app/](https://arnob-mahmud.vercel.app/).

**Enjoy building and learning!** 🚀

Thank you! 😊

---
