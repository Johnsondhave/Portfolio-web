# React Portfolio Website 💼
A personal portfolio website built with React and Tailwind CSS.

## Features
- Responsive design  
- Smooth scroll navigation  
- Modern UI layout  

## Tech Stack
React | Tailwind CSS | JavaScript (ES6+)

## Live Demo
https://johnsondhave.github.io/portfolio/# Portfolio-web
import React from "react";

function App() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-800">
      <header className="text-center p-6">
        <h1 className="text-3xl font-bold">Johnson David</h1>
        <p className="text-lg">Front-End Developer | React | JavaScript</p>
      </header>

      <section className="max-w-3xl mx-auto p-6">
        <h2 className="text-2xl font-semibold mb-2">About Me</h2>
        <p>I build responsive, user-friendly web apps with React and modern JS.</p>
      </section>
    </div>
  );
}

export default App;
