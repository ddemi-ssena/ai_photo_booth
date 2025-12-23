# 📸 Time Booth AI  
### The Ultimate AI-Driven Time Travel Photo Experience

**Time Booth AI** is a cutting-edge mobile application built with **React Native** that transforms the traditional *Korean-style photobooth* into an immersive, AI-powered time travel experience.

Instead of simply taking photos, users are guided by an **AI Art Director** through iconic eras — from the elegance of the **1800s** to a **Cyberpunk future** — resulting in a professionally styled, AI-transformed digital souvenir delivered straight to their inbox.

---

## 🌟 Key Features

### 🎙️ AI Art Director (Voice Agent)
Powered by **Google Gemini** and **ElevenLabs**, a human-like voice agent acts as your personal photographer.

- Analyzes selected **era** and **group mode** (Single, Couple, Friends, Family)
- Suggests creative and natural poses for *each* shot
- Eliminates awkward “What do I do with my hands?” moments

---

### 🕰️ Time-Travel Photo Transformation
Using **Fal.ai (Flux / SDXL)** image-to-image technology:

- Preserves facial identity
- Re-renders clothing, background, lighting, and atmosphere
- Supports multiple eras:
  - 1800s
  - 1920s
  - 2000s
  - 2070s (Cyberpunk)

---

### 🎨 Customizable “Hongdae-Style” Photo Strips
After the session, users can:

- Select **4 out of 5** captured photos
- Customize frame colors:
  - Classic Black
  - Pearl White
  - Soft Pink
  - And more
- Apply aesthetic filters:
  - Noir
  - Retro
  - Vivid

---

### 💌 Automated Digital Delivery
Once finalized, the app:

- Bundles the high-resolution photo strip
- Sends it directly to the user’s email
- Powered by **Resend API**

---

## 🛠️ Tech Stack

| Layer | Technology |
|------|-----------|
| Mobile Framework | React Native (Expo SDK 52) |
| Routing | Expo Router (File-based) |
| AI (LLM) | Google Gemini 2.0 Flash |
| Voice Synthesis | ElevenLabs API (Rachel Voice) |
| Image Processing | Fal.ai (Flux General / Img2Img) |
| Email Service | Resend API |
| Graphics & Capture | React Native Animated API, ViewShot |

---

## 📲 User Journey

1. **Stage Entrance**  
   Enter your email and experience a theatrical red-curtain opening with a floating camera animation.

2. **The Setup**  
   Select your **Era** and **Group Mode**.

3. **The Session**  
   Follow real-time voice instructions from the AI Director.  
   The app counts down and captures **5 unique shots**.

4. **The Time Machine**  
   AI processes photos in the background, applying era-specific styling.

5. **Studio Edit**  
   Choose your favorite photos, frame color, and visual filter.

6. **Final Delivery**  
   Receive your high-quality digital photo strip via email.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/time-booth-ai.git
cd time-booth-ai
2️⃣ Install Dependencies
bash
Kodu kopyala
npm install
3️⃣ Environment Variables
Create a .env file in the root directory:

env
Kodu kopyala
EXPO_PUBLIC_FAL_KEY=your_fal_ai_key
EXPO_PUBLIC_ELEVENLABS_KEY=your_elevenlabs_key
EXPO_PUBLIC_RESEND_KEY=your_resend_key
EXPO_PUBLIC_GEMINI_KEY=your_gemini_key
4️⃣ Run the App
bash
Kodu kopyala
npx expo start -c
👤 Author

Developed by Sena
Bridging the gap between AI technology and nostalgic photography. ✨🎞️
