# My Movie Mood 🎬

A modern web application that recommends movies based on your emotional state, powered by TMDB API and Firebase authentication.

## 🌟 Features

- 🎭 **Mood-Based Recommendations**: Get personalized movie suggestions based on your current mood
- 🔍 **Advanced Filtering**: Filter by year range and movie format (Animation/Live Action)
- 🔐 **Secure Authentication**: User authentication powered by Firebase
- 💾 **Smart Caching**: Local caching system for improved performance
- 📱 **Responsive Design**: Beautiful glass-morphism UI that works on all devices
- 🎬 **Rich Movie Data**: Detailed movie information from TMDB API
- 🚫 **Content Filtering**: Built-in filtering for appropriate content

## 🚀 Quick Start

### Prerequisites
- Node.js (v18 or higher recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository
```bash
git clone https://github.com/rahulpatel902/my-movie-mood.git
cd my-movie-mood
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
   - Copy `.env.example` to `.env`
   - Fill in your Firebase and TMDB API credentials

### Development

```bash
npm run dev
```
Visit `http://localhost:5173` in your browser

### Production Build
```bash
npm run build
npm run preview
```

## 🏗️ Project Structure

```
project-root/
├── src/                    # Source files
│   ├── api.js             # TMDB API integration
│   ├── authCheck.js       # Authentication utilities
│   ├── config.js          # Configuration and constants
│   ├── firebase.js        # Firebase initialization
│   ├── ui.js             # UI update functions
│   └── utils.js          # Helper utilities
├── public/                # Static assets
├── documentation/         # Project documentation
├── auth.{html,css,js}    # Authentication pages
├── index.html            # Main application page
├── main.js              # Application entry point
├── style.css            # Global styles
├── vite.config.js       # Vite configuration
└── netlify.toml         # Deployment configuration
```

## 🛠️ Tech Stack

- **Frontend Framework**: Vanilla JavaScript with modern ES6+ features
- **Build Tool**: Vite v5.4
- **Authentication**: Firebase v10.14
- **API Integration**: TMDB API v3
- **Styling**: Custom CSS with Glass-morphism design
- **Deployment**: Netlify

## 🔒 Security Features

- Environment variables for sensitive data
- Secure authentication flow
- API key protection
- Content filtering
- Error handling and retry mechanisms

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Environment Variables

Required environment variables (see `.env.example`):
- `VITE_FIREBASE_*`: Firebase configuration
- `VITE_TMDB_API_KEY`: TMDB API key

## 🙏 Acknowledgments

- [TMDB](https://www.themoviedb.org/) for the comprehensive movie database
- [Firebase](https://firebase.google.com/) for authentication services
- [Vite](https://vitejs.dev/) for the excellent build tool
- [Font Awesome](https://fontawesome.com/) for icons

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details
