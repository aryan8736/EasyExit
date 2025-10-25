# EasyExit

A digital outpass management system with mobile and web interfaces.

## Project Structure

- **Backend**: Node.js/Express.js REST API with Prisma ORM
  - Authentication & Authorization
  - Role-based access control (Admin, Manager, Checker, User)
  - Firebase notifications integration
  - Cloudinary integration for media handling

- **Frontend**: React Native mobile application
  - Built with Expo
  - TypeScript support
  - Tamagui UI framework
  - React Query for API state management

## Getting Started

### Backend Setup

1. Navigate to the backend directory:
```bash
cd Backend/clean-repo
```

2. Install dependencies:
```bash
npm install
```

3. Set up your database with Prisma:
```bash
npx prisma migrate dev
```

4. Start the server:
```bash
npm start
```

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd Frontend/Frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

## Features

- Digital outpass request and approval system
- Real-time notifications
- Role-based access control
- User profile management
- Announcement system for managers
- QR code based verification for checkers


