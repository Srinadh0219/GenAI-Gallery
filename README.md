1. Project Title

GenAIGallery – AI-Powered Image Generation & Sharing Platform (MERN Stack)

2.Problem Statement

With the rise of generative AI, users lack a simple, unified platform to generate high-quality AI images, store them efficiently, and explore or share creations in a community-driven gallery. Existing tools are either complex, fragmented, or lack scalability and user-friendly design.

3.Solution Overview

GenAIGallery is a full-stack MERN application that enables users to:

Generate AI images in real time using text prompts

Explore a gallery of AI-generated images

Download and share generated content seamlessly

The platform integrates ClipDrop API for AI image generation and Cloudinary for optimized image storage and delivery, ensuring performance, scalability, and high image quality.

3.Key Features

🔹 AI Image Generation using ClipDrop API

🔹 Image Gallery with responsive grid layout

🔹 Download & Share Images

🔹 Post Creation with prompt metadata

🔹 User Profiles to manage generated content

🔹 Interactive UI with notifications and feedback

🔹 Secure Environment Configuration using .env

🔹 Production Deployment on Netlify & Render

4.Technology Stack
Frontend

React (Vite) – Fast and modern UI development

Tailwind CSS – Responsive and clean UI styling

Axios – API communication

Backend

Node.js – Server-side runtime

Express.js – RESTful API development

MongoDB – NoSQL database for storing posts and user data

Mongoose – Schema modeling and data validation

5.AI & Media Services

ClipDrop API – AI-powered image generation

Cloudinary – Image storage, optimization, and delivery

Deployment

6.Netlify – Frontend hosting

Render – Backend hosting

System Architecture (High Level)

User enters a text prompt on the frontend

Request is sent to the Node.js/Express API

Backend calls ClipDrop API to generate the image

Generated image is uploaded to Cloudinary

Image metadata is stored in MongoDB

Image is displayed in the gallery UI
