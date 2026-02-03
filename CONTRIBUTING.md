# Contributing to Nyarm 🐱

Thank you for your interest in contributing to Nyarm! We welcome contributions from everyone.

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Expo CLI (`npm install -g expo-cli`)
- Android device or emulator (for testing)

### Setup

1. Fork this repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/nyarm-android.git
   cd nyarm-android
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npx expo start
   ```

## 📝 How to Contribute

### Reporting Bugs

1. Check if the bug is already reported in [Issues](../../issues)
2. If not, create a new issue with:
   - Clear title
   - Steps to reproduce
   - Expected vs actual behavior
   - Device/OS information

### Suggesting Features

1. Open a new issue with the `enhancement` label
2. Describe the feature and why it would be useful
3. Include mockups or examples if possible

### Submitting Code

1. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. Make your changes
3. Test thoroughly on Android device/emulator
4. Commit with clear messages:
   ```bash
   git commit -m "Add: description of what you added"
   ```
5. Push and create a Pull Request

## 📁 Project Structure

```
nyarm-android/
├── App.tsx              # Main app entry
├── src/
│   ├── components/      # UI components
│   ├── hooks/           # Custom React hooks
│   ├── utils/           # Utility functions
│   └── types/           # TypeScript types
├── assets/              # Images and assets
└── app.json             # Expo configuration
```

## 🎨 Code Style

- Use TypeScript for all new files
- Follow existing code patterns
- Use meaningful variable/function names
- Add comments for complex logic
- Keep components small and focused

## ✅ Pull Request Checklist

Before submitting a PR, make sure:

- [ ] Code compiles without errors
- [ ] App runs on Android device/emulator
- [ ] No TypeScript errors
- [ ] Commit messages are clear
- [ ] PR description explains the changes

## 💬 Questions?

Feel free to open an issue with the `question` label or reach out!

---

🐱 *"Thanks for helping make Nyarm better, nya~!"*
