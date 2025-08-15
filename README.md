# KathaKrithi
Swetcha Hackathon 
# Kathakriti: AI-Powered Folk Tale Animator

Kathakriti is a hackathon-ready web platform that transforms traditional oral or written folk tales into beautiful, interactive shadow puppet animations. It leverages modern frontend technologies and AI-powered services to create a seamless and magical storytelling experience, preserving cultural heritage in a new and engaging format.

This project was built to demonstrate a full user journey: from providing a story via voice, text, or file upload, to watching a dynamically generated, context-aware animated short story.

## 🚀 Core Features

* *Multi-Modal Story Input*: Users can provide their folk tales in three ways:
    * *Voice Recording*: An in-browser audio recorder to capture oral stories.
    * *File Upload*: Support for common audio formats (MP3, WAV, etc.).
    * *Text Input*: A dedicated text area for written stories.
* *AI-Simulated Poem Generation*: The user's original story is transformed into a poetic, folk-tale-style narrative with multiple, dynamically generated ending options based on the story's context.
* *Context-Aware Image Generation*: For each scene in the story, the platform intelligently extracts keywords from the user's original text and fetches relevant, high-quality images from the Unsplash API.
* *Dynamic Shadow Puppet Animation*: The fetched images are automatically styled with CSS filters to create a beautiful, consistent, fire-lit shadow puppet aesthetic. The scenes are then presented as an interactive, auto-playing animation with smooth transitions.
* *Interactive Player*: A fully-featured animation player with controls for play/pause, next/previous scene, restart, and volume adjustment, all wrapped in a responsive UI that works on both desktop and mobile.

## 🛠 Tech Stack

* *Frontend*: React 18 & Vite
* *Styling*: Tailwind CSS with a custom, culturally-inspired theme
* *State Management*: React Hooks (useState, useEffect, useCallback)
* *Routing*: React Router v6
* *Image Generation (API)*: [Unsplash API](https://unsplash.com/developers)
* *Animations*: CSS Transitions & Keyframe Animations

## ⚙ Running the Project Locally

To get Kathakriti running on your local machine, follow these steps:

1.  *Clone the repository:*
    bash
    git clone <your-repository-url>
    cd kathakriti 
    

2.  *Install dependencies:*
    bash
    npm install
    

3.  *Set up Environment Variables:*
    Create a .env file in the root of the project and add your Unsplash API Access Key.
    
    VITE_UNSPLASH_ACCESS_KEY="YOUR_UNSPLASH_ACCESS_KEY_HERE"
    

4.  *Start the development server:*
    bash
    npm run dev
    
    The application will be available at http://localhost:4028.
