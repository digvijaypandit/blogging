# React + Vite  

This template provides a minimal setup to get React working with Vite, featuring HMR (Hot Module Replacement) and ESLint rules.  

Currently, two official plugins are available:  

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) - Uses [Babel](https://babeljs.io/) for Fast Refresh.  
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) - Uses [SWC](https://swc.rs/) for Fast Refresh.  

## Project Information  

This project is a React application integrated with **AppWrite** for backend services. It includes a **rich text editor (RTE)** component using TinyMCE and **React Hook Form** for form handling.  

> **This project is developed under the guidance of [Hitesh Choudhary](https://www.youtube.com/@HiteshChoudhary) and the Chai aur Code community.** ☕🚀  

## Detailed Description  

The goal of this project is to provide a seamless experience for creating and managing content with a rich text editor. It utilizes **React** for the user interface and **AppWrite** for backend functionalities such as authentication, database, and storage.  

### Features  

- **Rich Text Editor** using TinyMCE.  
- **Form handling** with React Hook Form.  
- **AppWrite integration** for backend services.  
- **Responsive design** using Tailwind CSS.  

## Technologies Used  

- **React** – A JavaScript library for building user interfaces.  
- **Vite** – A fast build tool for modern web projects.  
- **AppWrite** – An open-source backend server for web, mobile, and Flutter developers.  
- **TinyMCE** – A powerful and flexible rich text editor.  
- **React Hook Form** – A library for managing forms in React applications.  
- **Tailwind CSS** – A utility-first CSS framework for rapid UI development.  

## Getting Started  

To set up and run this project locally, follow these steps:  

1. **Clone the repository**:  
   ```sh
   git clone https://github.com/digvijaypandit/blogging.git
   
Navigate to the project directory:
```sh
  cd your-repo
```
Install dependencies:
```
  npm install
```
Start the development server:
```
  npm run dev
```
##Demo
Check out the live demo: [Live Demo] (https://blog-deployment-ghu9.vercel.app/)
---

#### **Option 2: If You Use Environment Variables in a Hosting Service**  
```md

## Environment Variables  

If deploying on platforms like **Vercel, Netlify, or Railway**, set the following environment variables in the dashboard:  

- `VITE_APPWRITE_URL` → Your AppWrite URL  
- `VITE_APPWRITE_PROJECT_ID` → Your AppWrite project ID
- `VITE_APPWRITE_DATABASE_ID` →  Your AppWrite database ID
- `VITE_APPWRITE_COLLECTION_ID` →  Your AppWrite collection ID
- `VITE_APPWRITE_BUCKET_ID` →  Your AppWrite bucket ID
- `VITE_TINYMCE_API_KEY` → Your TinyMCE API key
Refer to the official documentation of your hosting provider on how to configure environment variables.  
```
##License
This project is licensed under the MIT License. See the LICENSE (LICENSE) file for more details.
