# Museum QR Art Guide System

A complete digital guide system for museums with online database storage and visitor engagement tracking.

## Features

### For Visitors:
- **No Login Required** - Instant access to artwork information
- **QR Code Scanning** - Scan codes or enter IDs manually
- **Rich Content** - Detailed descriptions, artist info, historical context
- **Privacy-First** - Anonymous engagement tracking

### For Museum Staff:
- **Secure Authentication** - JWT-based login system
- **Online Database** - MongoDB Atlas for data storage
- **Cloud Image Storage** - Cloudinary for artwork images
- **Engagement Analytics** - Track visitor viewing times and behavior
- **QR Code Generation** - Automatic QR code creation
- **Admin Dashboard** - Complete artwork management

## Technology Stack

- **Backend**: Node.js, Express.js, MongoDB, Mongoose
- **Authentication**: JWT, bcryptjs
- **File Storage**: Cloudinary, Multer
- **QR Generation**: QRCode
- **Frontend**: Vanilla JavaScript, CSS3, HTML5
- **Database**: MongoDB Atlas (Cloud)
- **Image Storage**: Cloudinary (Cloud)

## Setup Instructions

### 1. Prerequisites
- Node.js (v14 or higher)
- MongoDB Atlas account
- Cloudinary account

### 2. Environment Setup

Create `backend/.env` file:
```env
MONGODB_URI=mongodb+srv://username:password@cluster0.xxxxx.mongodb.net/museum_qr_system?retryWrites=true&w=majority
JWT_SECRET=your_super_secure_jwt_secret_key_2024_museum_qr
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
PORT=5000
FRONTEND_URL=http://localhost:5000