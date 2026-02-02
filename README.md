# 🎉 AI Greeting Generator

An intelligent greeting card generator powered by Google's Gemini AI. Create personalized, heartfelt greetings in multiple languages.

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

## ✨ Features

- 🎂 **Multiple Occasions**: Birthday and New Year greetings
- 🌍 **Multi-language Support**: Russian, Belarusian, English, German, Spanish, French
- 🎭 **Customizable Tone**: Official, Friendly, Humorous, Romantic, Touching, 18+
- 🖼️ **AI-Generated Images**: Optional greeting card illustrations
- ⚡ **Real-time Generation**: Fast AI-powered content creation
- 📋 **Copy to Clipboard**: Easy sharing of generated greetings
- 📱 **Responsive Design**: Works seamlessly on all devices

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Google Gemini API Key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/JGRex-Joy/greeting-generator.git
cd greeting-generator
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```env
VITE_GEMINI_API_KEY=your_gemini_api_key_here
```

4. Start the development server:
```bash
npm run dev
```

5. Open your browser and navigate to `http://localhost:5173`

## 🎨 Usage

1. **Choose an Occasion**: Select between Birthday or New Year
2. **Enter Recipient Details**: 
   - Name (required)
   - Age (optional)
   - Interests and hobbies (optional)
3. **Customize Settings**:
   - Select a tone (Official, Friendly, Humorous, etc.)
   - Choose output language
   - Enable image generation (optional)
4. **Generate**: Click the "Generate" button to create your personalized greeting
5. **Copy & Share**: Use the copy button to share your greeting

## 🛠️ Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **AI Integration**: Google Gemini AI (gemini-2.5-flash & gemini-2.5-flash-image)
- **State Management**: React Hooks

## 📁 Project Structure

```
src/
├── components/
│   ├── AppTitle.tsx           # Main title component
│   ├── ExtraDetailsSection.tsx # Language & image settings
│   ├── GenerateButton.tsx     # Generate action button
│   ├── Header.tsx             # App header
│   ├── OccasionButton.tsx     # Occasion selection button
│   ├── ResultSection.tsx      # Generated content display
│   ├── ToneSelector.tsx       # Tone selection component
│   └── UserDetailsSection.tsx # User input fields
├── services/
│   └── geminiService.ts       # Gemini AI integration
├── constants.ts               # App constants
├── types.ts                   # TypeScript type definitions
├── App.tsx                    # Main application component
└── main.tsx                   # Application entry point
```

## 🔑 Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `VITE_GEMINI_API_KEY` | Your Google Gemini API key | Yes |

To get your Gemini API key, visit [Google AI Studio](https://makersuite.google.com/app/apikey).

## 🎯 Available Tones

- **Official**: Formal, respectful tone
- **Friendly**: Warm, casual tone
- **Humorous**: Fun, light-hearted with jokes
- **Romantic**: Tender, loving, affectionate
- **Touching**: Heartfelt, emotional
- **18+**: Bold, sarcastic, adult humor

## 🌐 Supported Languages

- Russian (Русский)
- Belarusian (Белорусский)
- English
- German (Deutsch)
- Spanish (Español)
- French (Français)

## 📝 Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint         # Run ESLint
```


## 🙏 Acknowledgments

- [Google Gemini AI](https://deepmind.google/technologies/gemini/) for powering the greeting generation
- [Lucide React](https://lucide.dev/) for beautiful icons
- [Tailwind CSS](https://tailwindcss.com/) for styling utilities
