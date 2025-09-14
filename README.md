🎮 Raja Rani Audiometry Game
A Unity-based interactive game that revamps the classic Indian Raja Rani and Hopscotch concepts into a fun audiometry test.
Players act as the Police, identifying the Thief by listening to pure tones at different decibel levels. This project combines traditional gameplay with a practical hearing assessment tool.

🚀 Features
🎵 Audiometry Integration – Pure tone audiometry simulated using Unity audio sources.

🧩 Role-based Gameplay – King, Queen, Minister, Soldier, Servant, and Thief each have tones mapped to them.

🎚 Threshold Sliders – Players set their hearing threshold for each frequency before starting.

⏱ Level System – 6 levels, each lasting 60 seconds, with increasing complexity.

📊 Results Summary – Displays the player’s threshold decibels for all tested frequencies at the end.

🎨 Revamped Classics – Inspired by traditional Raja Rani and Hopscotch games, reimagined in Unity.

🕹 Gameplay
At the start, use sliders to set your hearing threshold for each frequency (5–90 dB).

Tap on game objects (tiles/roles) to hear their assigned pure tone.

After 40 seconds in each level, you’ll be prompted to guess which tone matches your threshold.

After 60 seconds, the game automatically advances to the next level.

After 6 levels, you’ll see a summary of your hearing thresholds across all frequencies.

🛠 Tech Stack
Engine: Unity

Language: C#

Version Control: Git & GitHub

Audio: Pure tone .wav files (stored in Resources/Audio)

📂 Project Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/raja-rani-audiometry.git
Open the project in Unity Hub.

Make sure all tone audio files (tone_5.wav … tone_90.wav) are placed in:

arduino
Copy code
Assets/Resources/Audio/
Press Play in the Unity Editor to start the game.

📊 Future Improvements
🎵 Add smooth fade-in/out audio transitions.

🖼 Improved UI animations for pop-ups and results.

🌐 WebGL build for browser-based audiometry play.

📱 Mobile optimization for Android/iOS.

📜 License
This project is licensed under the MIT License – feel free to use, modify, and distribute with attribution.
