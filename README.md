# Garrett's Portfolio — Data Science & Engineering @ UConn

An ultra-clean, minimalist personal portfolio inspired by the signature aesthetic of [reysu.io](https://reysu.io), tailored for **Garrett**, a **Data Science & Engineering major at the University of Connecticut (UConn)**.

---

## ✨ Key Features & Aesthetic Details

- **Minimalist Tokyo / Linear Tech Design**: Clean typography (Inter + JetBrains Mono), tight margins, centered 768px layout (`max-w-3xl`).
- **Dark-Theme-First with iOS Switch**: Smooth sliding theme toggle that toggles between dark slate (`#1f1f23`) and clean light mode (`#fafafa`), persisted via `localStorage`.
- **Live Storrs, CT Real-Time Status**: Automatically computes the live time in Storrs, CT (`America/New_York` timezone) with dynamic status:
  - 🟢 **Online / In Lab** (Daytime: 6 AM – 6 PM) with animated pulsing ping indicator
  - 🌙 **Evening Study** (Evening: 6 PM – 11 PM)
  - 💤 **Offline / Resting** (Night: 11 PM – 6 AM)
- **Interactive Neko Pixel Cat**: Authentic pixel-art companion in the footer that sleeps during the night, idles/yawns/itches during the day, and perks up alert when clicked!
- **Infinite Skills Marquee**: Smooth GPU-accelerated ticker with edge gradient masks showcasing Python, PyTorch, SQL, Spark, Scikit-Learn, Docker, AWS, UConn DSE, etc.
- **Dynamic Relative Dates**: Computes live relative timestamps (e.g., *"3 days ago"*, *"2 weeks ago"*) so projects never look stale.
- **Interactive Data Science Playground**: An embedded HTML5 canvas visualizing non-linear probabilistic decision boundaries in real time.
- **Complete Page Suite**:
  - `index.html`: Hero, Marquee, Latest Project Spotlight, Featured Engineering Projects, ML Visualizer, UConn Curriculum, Mentions, Footer.
  - `about.html`: Detailed bio, systems + ML philosophy, daily gear & hardware setup, reading influences.
  - `projects.html`: In-depth project showcase with architecture breakdowns, benchmarks, and GitHub links.
  - `2026.html`: The iconic `reysu.io/2026` yearly log of builds, papers read, and current tools.
  - `blog.html`: IDE-style minimalist post list with interactive modal article reader.
  - `contact.html`: Clean contact form with UConn campus location in Storrs, CT.

---

## 🚀 How to Preview Locally

### Option 1: Open Directly
Double-click `index.html` in your file browser (Finder) to open it in Safari or Chrome.

### Option 2: Local HTTP Server
Run the following in your terminal inside the project folder:
```bash
python3 -m http.server 8000
```
Then visit [http://localhost:8000](http://localhost:8000).

---

## 🌐 How to Deploy to GitHub Pages (Free)

1. Create a new repository on GitHub named `yourusername.github.io` (or `portfolio`).
2. Initialize git and push the files:
   ```bash
   cd /Users/garrett/.gemini/antigravity/scratch/garrett-portfolio
   git init
   git add .
   git commit -m "Initial portfolio release"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```
3. Your site will immediately be live at `https://yourusername.github.io`!

---

## 🎨 Customization Guide

- **Profile Picture**: Replace `images/avatar.svg` with your own picture (e.g. `images/garrett.jpg`) and update the `src` attribute in `index.html`.
- **Social Handles**: Update links to your GitHub, LinkedIn, Kaggle, and personal email in `index.html` and the other HTML files.
- **Resume**: You can add your `resume.pdf` into the root directory and link to it from the hero action buttons.

# AI-Club-10-6
# AI-Club-10-6
