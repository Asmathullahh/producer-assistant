# 🎧 AntiGravity AI Producer Assistant

An elegant, completely browser-based web application that acts as your personal AI audio engineer. Upload any two tracks, describe the vibe of the mashup you want to create, and the application will instantly provide a mathematical roadmap for your DAW (Ableton, FL Studio, Logic Pro).

## 🚀 Features

*   **Zero Dependencies:** Built entirely with Vanilla HTML, CSS, and JavaScript. No Node.js, Python, or backend servers required.
*   **Local Audio Engine:** Uses the built-in Web Audio API to decode and analyze MP3/WAV files entirely on your local machine. Your music is never uploaded to the cloud.
*   **BPM Detection:** Implements a custom peak-detection algorithm to accurately estimate the tempo of uploaded tracks.
*   **Harmonic Mixing (Camelot Wheel):** Algorithmically maps the audio's root key to the industry-standard Camelot Mixing Wheel (e.g., 8A, 5B) so you know exactly which tracks clash and which blend perfectly.
*   **Producer Roadmap Generator:** Compares the metadata of your base layer and overlay tracks, producing step-by-step instructions for tempo stretching, semitone transposition, and EQ filtering based on your specific vibe.

## 💻 Tech Stack

*   **HTML5**
*   **CSS3** (Premium Dark Mode, Glassmorphism, CSS Grid/Flexbox)
*   **Vanilla JavaScript** (ES6+, Web Audio API)

## 🛠️ Installation & Usage

Because the app is built without a backend framework, you can run it instantly!

1.  Clone this repository.
2.  Open the folder in your terminal.
3.  Start a basic static server. If you have Ruby installed on your Mac, run:
    ```bash
    ruby -run -e httpd . -p 8000
    ```
    *(Alternatively, you can use `python3 -m http.server 8000` or `npx serve`)*
4.  Open `http://localhost:8000` in your web browser.
5.  Upload two audio files, type your vision, and click **Analyze & Generate Roadmap**.

## 🎨 Interface Preview

The UI features a stunning dark aesthetic with vibrant accent gradients (`#f97316` and `#8b5cf6`), glassmorphic cards, and dynamic state transitions.

## 📝 License
Created by AntiGravity.
