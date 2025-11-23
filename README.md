# File Upload API

A RESTful API for uploading and managing images using Node.js, Express, Multer, and MongoDB.

## Features
- ✅ Upload single/multiple images
- ✅ File validation (type and size limits)
- ✅ Store metadata in MongoDB
- ✅ Serve uploaded files
- ✅ Delete files

## Installation
```bash
npm install
```

## Setup

1. Install MongoDB locally or use MongoDB Atlas
2. Update connection string in `server.js`
3. Run the server:
```bash
npm run dev
```

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/upload` | Upload single file |
| POST | `/api/upload-multiple` | Upload multiple files |
| GET | `/api/files` | Get all files |
| GET | `/api/files/:id` | Get file by ID |
| DELETE | `/api/files/:id` | Delete file |
| GET | `/uploads/:filename` | Serve uploaded file |

## Technologies Used
- Node.js
- Express.js
- Multer
- MongoDB
- Mongoose

## Author
KUNDANIOS