# 📌 Suburbia Skate

A modern, interactive website for a skateboarding brand, built with **Next.js 15**, **React 19**, and **Tailwind CSS**. This project features physics-based animations, 3D elements, and a headless CMS integration for content management.

## 🌍 Live Demo

🔗 [https://suburbia-skate.netlify.app/](https://suburbia-skate.netlify.app/)

## 🚀 Features

- **Next.js 15 (App Router)** with Turbopack for optimized development
- **React 19** with the latest features
- **Physics-based Animations** using Matter.js
- **3D Elements** using React Three Fiber and Drei
- **Headless CMS Integration** with Prismic for content management
- **Advanced Animations** using GSAP with React integration
- **Responsive Design** with Tailwind CSS
- **TypeScript** for type safety
- **Component Slice Machine** for modular content management
- **Deployed on Netlify** for optimal performance

## 📂 Project Structure

````
📦 suburbia
┣ 📂 src
┃ ┣ 📂 app
┃ ┃ ┣ 📜 layout.tsx # Root layout file
┃ ┃ ┣ 📜 page.tsx # Homepage entry
┃ ┃ ┣ 📜 globals.css # Global styles
┃ ┃ ┗ 📂 [other pages] # Additional pages
┃
┃ ┣ 📂 components
┃ ┃ ┣ 📂 ui # Reusable UI components
┃ ┃ ┣ 📂 skate # Skate-related components
┃ ┃ ┣ 📂 layout # Layout components
┃ ┃ ┗ 📂 slices # Prismic slice components
┃
┃ ┣ 📂 lib
┃ ┃ ┣ 📜 prismic.ts # Prismic client configuration
┃ ┃ ┣ 📜 physics.ts # Matter.js physics utilities
┃ ┃ ┗ 📜 utils.ts # Utility functions
┃
┃ ┣ 📂 hooks # Custom React hooks
┃ ┣ 📂 types # TypeScript type definitions
┃ ┣ 📂 styles # Additional styling
┃ ┗ 📂 sass # SASS modules (if applicable)
┃
┣ 📂 public
┃ ┣ 📂 images # Static images
┃ ┣ 📂 models # 3D model assets
┃ ┗ favicon.ico
┃
┣ 📜 package.json
┣ 📜 tailwind.config.ts # Tailwind CSS configuration
┣ 📜 tsconfig.json # TypeScript configuration
┣ 📜 slicemachine.config.json # Slice Machine configuration
┣ 📜 README.md
┗ 📜 .gitignore

```

---

## 🛠 Tech Stack

- **Framework:** [Next.js 15](https://nextjs.org/) with Turbopack
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **3D Graphics:** [React Three Fiber](https://docs.pmnd.rs/react-three-fiber) + [Drei](https://github.com/pmndrs/drei)
- **Physics Engine:** [Matter.js](https://brm.io/matter-js/)
- **Animations:** [GSAP](https://gsap.com/) + [@gsap/react](https://www.npmjs.com/package/@gsap/react)
- **CMS:** [Prismic](https://prismic.io/) with [Slice Machine](https://www.slicemachine.dev/)
- **UI Utilities:** [clsx](https://www.npmjs.com/package/clsx)
- **Icons:** [React Icons](https://react-icons.github.io/react-icons/)
- **Deployment:** [Netlify](https://netlify.com/)

---

## ⚙️ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/suburbia.git
   cd suburbia
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a \`.env.local\` file with the following variables:
   ```
   PRISMIC_ACCESS_TOKEN=your_prismic_access_token
   PRISMIC_REPOSITORY_NAME=your_repository_name
   ```

4. **Run development server:**

   ```bash
   npm run dev
   ```

   Project will be available at: [http://localhost:3000](http://localhost:3000)

5. **Start Slice Machine (for content editing):**

   ```bash
   npm run slicemachine
   ```

6. **Build for production:**

   ```bash
   npm run build
   npm start
   ```

## 📦 Key Dependencies

```json
{
  "dependencies": {
    "@gsap/react": "^2.1.1",
    "@prismicio/client": "^7.13.0",
    "@prismicio/next": "^1.7.1",
    "@prismicio/react": "^2.9.1",
    "@react-three/drei": "^9.120.4",
    "@react-three/fiber": "^9.0.0-rc.1",
    "@types/matter-js": "^0.19.8",
    "clsx": "^2.1.1",
    "gsap": "^3.12.5",
    "matter-js": "^0.20.0",
    "next": "15.0.3",
    "react": "19.0.0-rc-66855b96-20241106",
    "react-dom": "19.0.0-rc-66855b96-20241106",
    "react-icons": "^5.4.0",
    "three": "^0.171.0"
  },
  "devDependencies": {
    "@slicemachine/adapter-next": "^0.3.61",
    "@types/node": "^20",
    "@types/react": "^18",
    "@types/react-dom": "^18",
    "eslint": "^8",
    "eslint-config-next": "15.0.3",
    "fluid-tailwind": "^1.0.4",
    "postcss": "^8",
    "slice-machine-ui": "^2.11.1",
    "tailwindcss": "^3.4.1",
    "typescript": "^5"
  }
}
````

## 🚀 Build Commands

```bash

# Development server with Turbopack

npm run dev

# Production build

npm run build

# Start production server

npm start

# Lint code

npm run lint

# Start Slice Machine

npm run slicemachine
```

## ✨ Author

**Fahad Ali**  
Frontend Developer | Pakistan  
📧 [fa6084904@gmail.com](mailto:fa6084904@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/fahad-ali-759700369/)

## 📌 Notes

- This project uses a modern tech stack with a focus on physics-based animations and 3D elements
- The component structure is designed for scalability and reusability
- Physics-based interactions provide an engaging user experience
