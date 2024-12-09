# Keystroke Dynamics Authentication

A modern web application that implements keystroke dynamics for enhanced security authentication. This system uses machine learning techniques to analyze typing patterns as an additional layer of security.

## Features

- 🔒 Multi-factor authentication combining passwords with keystroke dynamics
- 📊 Machine learning-based typing pattern analysis
- 🔄 Multiple typing samples collection during registration
- 📱 Fallback OTP system for additional security
- ⚡ Built with React and TypeScript for robust performance

## Technology Stack

- React 18
- TypeScript
- Tailwind CSS
- Zustand for state management
- Lucide React for icons
- Vite for development and building

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/keystroke-dynamics-auth.git
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

## How It Works

### Registration
1. Users enter their username and password
2. The system requires 5 password entry attempts to learn typing patterns
3. Keystroke dynamics (timing between keystrokes and key hold duration) are recorded
4. A machine learning model analyzes and stores the typing pattern

### Login
1. Users enter their credentials
2. The system verifies both the password and typing pattern
3. If the typing pattern doesn't match, an OTP verification is required
4. Successful verification grants access to the dashboard

## Security Features

- Keystroke pattern analysis for typing behavior verification
- OTP fallback for additional security
- Multiple sample collection for accurate pattern recognition
- Secure state management with Zustand

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.