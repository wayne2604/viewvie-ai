<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&pause=1000&color=8B0000&center=true&vCenter=true&width=900&lines=??+Viewvie+Movie+Recommendation+App" alt="Title" />
</div>

A modern Android movie recommendation app powered by AI. Viewvie combines Netflix-style browsing with intelligent recommendations from Cue, your personal AI movie assistant.

---

### ?? Stack

- Kotlin
- Android SDK (API 24+)
- Google Generative AI
- Glide (Image Loading)
- Gson (JSON Processing)
- RecyclerView

---

### ? Quick start

`ash
# Clone the repository
git clone https://github.com/wayne2604/viewvie-ai.git

# Navigate to the directory
cd viewvie-ai

# Open in Android Studio
# File ? Open ? Select the project directory

# Add your Google AI API key
# Create a local.properties file and add:
# GOOGLE_AI_API_KEY=your_api_key_here
`

Sync Gradle dependencies and run the app on an emulator or physical device.

---

### ?? Features

- **AI-Powered Recommendations** — Get personalized movie suggestions through conversational AI via Cue.
- **Netflix-Style Browsing** — Familiar interface with horizontal scrolling categories and movie cards.
- **Smart Search** — Find movies quickly with intelligent filtering and search.
- **Distinctive Branding** — Deep red/maroon to cream color palette with custom "bitten TV" logo.
- **Seamless UX** — Floating action button access to Cue without disrupting browsing flow.

---

### ??? How it works

Viewvie follows modern Android architecture principles with a hybrid approach:

- **Dual Interface**: Traditional streaming interface combined with AI chat functionality for the best of both worlds.
- **Google Generative AI Integration**: Leverages Google's Gemini models to power intelligent movie recommendations.
- **Efficient Image Loading**: Uses Glide library for smooth, memory-efficient poster and backdrop loading.
- **Material Design**: Follows Android Material Design guidelines for intuitive navigation and interactions.

---

### ?? Project structure

`	ext
/app
+-- src/
¦   +-- main/
¦       +-- java/com/example/myapplication/
¦       ¦   +-- MainActivity.kt           # Main entry point
¦       ¦   +-- MovieAdapter.kt           # RecyclerView adapter for movie lists
¦       ¦   +-- CueActivity.kt            # AI chat interface
¦       ¦   +-- models/                   # Data models for movies
¦       +-- res/
¦       ¦   +-- layout/                   # XML layouts
¦       ¦   +-- drawable/                 # Icons and graphics
¦       ¦   +-- values/                   # Colors, strings, themes
¦       +-- AndroidManifest.xml
+-- build.gradle.kts                      # App-level build configuration
+-- README.md                             # Project documentation
`

---

### ?? Design

- **Color Palette**: Deep red (#8B0000) to cream (#FFFDD0)
- **Viewvie Logo**: Bitten TV screen design
- **Cue Logo**: Shield with play button
- **Typography**: Modern, clean sans-serif fonts
- **UI/UX**: Designed in Figma with professional presentation materials

---

### ?? Author

**KyRhetTeng** — Building the future of movie discovery with AI

---

### ?? License

This project is licensed under the MIT License - see the LICENSE file for details.

---

### ?? Roadmap

- [ ] Multi-language support
- [ ] User profiles and watch history
- [ ] Social sharing features
- [ ] Offline mode for saved recommendations
- [ ] Integration with streaming service APIs
