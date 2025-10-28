# SnapCAD

A web application that converts images to 3D models using AI.

## Setup

### Frontend

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

The frontend will be available at http://localhost:5173

### Backend

1. Navigate to the backend directory:
```bash
cd backend
```

2. Install Python dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Flask server:
```bash
python backend.py
```

The backend API will be available at http://localhost:5500

## Features

- Upload images or take photos with your camera
- Generate 3D models from images
- Download 3D models in GLB format
- Refine models with custom drawings

## Technologies

- Frontend: React, TypeScript, Vite, Three.js
- Backend: Flask, Hunyuan3D API
- 3D Rendering: Three.js

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
