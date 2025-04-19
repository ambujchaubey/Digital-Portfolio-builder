# Digital Portfolio Builder

A modern platform for developers to build and showcase their digital portfolios. Built with React.js, Node.js, Express, and MongoDB.

## Features

- 🎨 Interactive portfolio templates
- 💻 GitHub repository integration
- 🎥 Multimedia support (images, videos, presentations)
- ⭐ Skill showcase with verification links
- 🔗 Easy portfolio sharing
- 📱 Responsive design
- 🔒 Secure authentication

## Tech Stack

- **Frontend**: React.js, Material-UI, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Storage**: Cloudinary (for media files)
- **Authentication**: JWT

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/portfolio-builder.git
   cd portfolio-builder
   ```

2. Install dependencies:
   ```bash
   npm run install-all
   ```

3. Create a `.env` file in the root directory:
   ```
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

The application will be available at `http://localhost:3000`

## Project Structure

```
portfolio-builder/
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── components/     # Reusable components
│       ├── pages/         # Page components
│       ├── context/       # React context
│       ├── hooks/         # Custom hooks
│       └── utils/         # Utility functions
├── server/                # Node.js backend
│   ├── config/           # Configuration files
│   ├── controllers/      # Request handlers
│   ├── middleware/       # Custom middleware
│   ├── models/          # Database models
│   └── routes/          # API routes
└── uploads/             # Temporary file storage
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. # Digital-Portfolio-builder
# Digital-Portfolio-builder
