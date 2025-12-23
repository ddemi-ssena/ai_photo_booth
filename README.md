The Ultimate AI-Driven Time Travel Photo Experience
Time Booth AI is a cutting-edge mobile application built with React Native that transforms the traditional "Korean-style" photobooth into an interactive AI adventure.
Instead of just taking pictures, users are guided by an AI Art Director through various eras—from the elegance of the 1800s to a Cyberpunk future—resulting in a professional, AI-transformed digital souvenir delivered straight to their inbox.
🌟 Key Features
🎙️ The AI Art Director (Agent)
Powered by Google Gemini and ElevenLabs, a human-like voice agent acts as your personal photographer. It analyzes your chosen era and group mode (Single, Couple, Friends, or Family) to suggest creative, unique poses for every single shot. No more "what should I do with my hands?" moments!
🕰️ Time-Travel Transformation
Using Fal.ai (Flux/SDXL) image-to-image technology, the app takes your raw photos and "re-renders" them. It keeps your facial features intact but changes your clothing, background, and lighting to match your selected time period (1800s, 1920s, 2000s, or 2070s).
🎨 Customizable "Hongdae" Strips
After the shoot, users can:
Select 4 out of 5 photos to include in the final strip.
Change Frame Colors: Choose between Classic Black, Pearl White, Soft Pink, and more.
Apply Aesthetic Filters: Add the finishing touch with Noir, Retro, or Vivid presets.
💌 Automated Digital Delivery
Once the design is finalized, the app uses the Resend API to bundle the high-resolution strip and send it directly to the user's email address as a lasting memory.
🛠️ The Tech Stack
Layer	Technology Used
Mobile Framework	React Native (Expo SDK 52)
Routing	Expo Router (File-based)
Brain (LLM)	Google Gemini 2.0 Flash
Voice Synthesis	ElevenLabs API (Rachel Voice)
Image Processing	Fal.ai (Flux General / Img2Img)
Email Service	Resend API
Graphics	React Native Animated API & ViewShot
📲 How It Works (The User Journey)
Stage Entrance: Enter your email and watch the theatrical red curtains open with a "floating camera" animation.
The Setup: Select your Era (Time Travel destination) and your Group Mode (Who are you shooting with?).
The Session: Listen to the AI Director’s voice instructions. The app counts down and captures 5 unique shots.
The Time Machine: The AI processes your photos in the background, adding textures and clothing from the selected era.
Studio Edit: Pick your favorite shots, choose a frame color, and apply a filter.
Final Delivery: Hit "Send" and find your high-quality digital strip in your inbox!
⚙️ Installation & Setup
Clone the repository:
code
Bash
git clone https://github.com/yourusername/time-booth-ai.git
cd time-booth-ai
Install dependencies:
code
Bash
npm install
Configure Environment Variables:
Create a .env file in the root directory and add your API keys:
code
Env
EXPO_PUBLIC_FAL_KEY=your_fal_ai_key
EXPO_PUBLIC_ELEVENLABS_KEY=your_elevenlabs_key
EXPO_PUBLIC_RESEND_KEY=your_resend_key
EXPO_PUBLIC_GEMINI_KEY=your_gemini_key
Run the app:
code
Bash
npx expo start -c
Developed by [Sena]
Bridging the gap between AI technology and nostalgic photography. ✨🎞️
