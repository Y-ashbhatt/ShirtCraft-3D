# 🪄 ShirtCraft 3D

**Transform your creativity into reality with the 3D Shirt Customizer!**

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Usage](#usage)
- [What I Learned](#what-i-learned)
- [Installation](#installation)
- [Future Enhancements](#future-enhancements)
- [Author](#author)

---

## Overview

**A feature-packed 3D shirt customization application built with React and Three.js, featuring AI-powered enhancements, dynamic animations, and seamless responsiveness.**

---

## Features

- **🎨 3D Shirt Generation**: Generate unique 3D shirts dynamically, allowing users to explore endless possibilities.
- **🌈 Color Customization**: Apply any color to the 3D shirt for a personalized look and feel.
- **📂 Logo Upload Functionality**: Upload any file as a logo and integrate it seamlessly onto the 3D shirt.
- **🖼️ Texture Image Upload**: Upload texture images to style the 3D shirt with favorite designs.
- **🤖 AI-Generated Logos**: Utilize the **black-forest-labs/FLUX.1-dev** model from Hugging Face to generate logos and intelligently apply them to the 3D shirt.
- **🎨 AI-Generated Textures**: Leverage AI to create custom textures for enhanced 3D customization.
- **📦 Download Options**: Download customized shirts for sharing or printing.
- **🌐 Theme Change with Color Selection**: Dynamically adjust the application theme based on the selected color for an immersive experience.
- **📱 Responsive 3D Application**: Seamlessly adaptable to all devices, ensuring great usability.
- **🔄 Framer Motion Animations**: Smooth transitions between 3D models with Framer Motion.
- **🏗️ Code Architecture & Reusability**: Efficiently organized, reusable components for scalability and maintainability.

---

## Tech Stack

- **Frontend**:
  - React.js
  - Three.js
  - React Three Fiber
  - React Three Drei
  - Vite
  - Tailwind CSS
- **Additional Libraries & Tools**:
  - Hugging Face API (using the **black-forest-labs/FLUX.1-dev** model)
  - Framer Motion
  - Valtio

---

## Usage

Users can:

- Customize 3D shirts with colors, logos, and textures.
- Generate AI-powered logos and textures for personalization using Hugging Face's **black-forest-labs/FLUX.1-dev** model.
- Seamlessly interact with a responsive interface across devices.

---

## What I Learned

- **3D Rendering**: Gained hands-on experience with Three.js and React Three Fiber for advanced rendering.
- **AI Integration**: Integrated Hugging Face's **black-forest-labs/FLUX.1-dev** model for real-time logo and texture generation.
- **Dynamic Design**: Enhanced understanding of responsive design and animations with Tailwind CSS and Framer Motion.
- **Code Efficiency**: Improved skills in creating reusable components for scalability.

---

## Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Hugging Face API key for **black-forest-labs/FLUX.1-dev** model

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/3d-shirt-customizer.git
   cd 3d-shirt-customizer
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. Create a `.env` file in the root directory and add your Hugging Face API key for the **black-forest-labs/FLUX.1-dev** model:

   ```
   VITE_HUGGINGFACE_API_KEY=your_api_key_here
   ```

4. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open the application in your browser at `http://localhost:3000`.

---

## Future Enhancements

- **Localization**: Add support for multi-language options.
- **AR/VR Integration**: Enable virtual try-ons using augmented reality.
- **Performance Optimization**: Optimize performance for larger texture files.

---

## Author

- **Name**: Yash Bhatt
- **GitHub**: [@Y-ashbhatt](https://github.com/Y-ashbhatt)
- **LinkedIn**: [Yash Bhatt](https://www.linkedin.com/in/yashbhatt30/)
