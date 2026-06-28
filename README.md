# **🤖 The Wild Engineer Reader & Writer Hub**

A responsive, single-file starlit application featuring an interactive log book reader, a voice broadcast narrative deck, starlit illustration blueprints, and a **dynamic generative Muse Console** allowing you to extend the lore in real-time.

## **✨ Features Installed**

* **📖 Adaptive Log Book Reader:** Page-by-page rendering of Unit AX-12's chronicle with highlighted text block active selections.  
* **📻 Communication Array (TTS):** Generative vocalization powered by lightweight CDN streaming and Gemini's flash-preview-tts systems.  
* **🍰 Custom Theme Switcher:** Features multiple custom layout colors including standard **Stone Paper**, **Deep Space**, and your favorite **Birthday Cake** theme (sprinkled pink and purple cream layout).  
* **✍️ Dynamic Muse Console:** Write custom descriptions and click "Draft Sequence" to let the Gemini 2.5 API draft complete, logically integrated new chapters (including ASCII art and text arrays) directly into your reader in real-time.  
* **⚓ Historical Appendix:** Links seamlessly to the Interactive Report Dashboard in your repository filetree (./dashboard.html) and the chronicle news piece that inspired the lore.

## **🚀 How to Launch on Your PC**

Due to browser security protocols on local file systems (file:///), calling APIs require a simple HTTP loop.

### **Option A: The Live Server Method (Recommended for VS Code)**

1. Install the **Live Server** extension (by Ritwick Dey) in VS Code.  
2. Open index.html in your editor.  
3. Click the **"Go Live"** button in your bottom status bar.  
4. Your browser will instantly mount the secure connection at http://127.0.0.1:5500/index.html.

### **Option B: Quick Terminal Python Server**

If you have Python installed, open your command console inside the project folder and run:

python \-m http.server 8000

Then navigate to http://localhost:8000 in your web browser.

## **🎨 Creative Themes Map**

Switch layouts dynamically on the left Comm Deck panel:

* **🪨 Stone Paper:** Clean warm slate and crisp pages for comfortable reading.  
* **🌌 Deep Space:** High-contrast tactical mode for starlit nightly operation.  
* **🍰 Birthday Cake:** Delicious soft-cream background accented by strawberry pink boundaries and deep lavender typography.

## **⚙️ Setting Up Your Free API Key**

To execute live voice broadcasts and write new starlit chapters dynamically:

1. Obtain a free API key at [Google AI Studio](https://aistudio.google.com/).  
2. Paste the key directly into the secure key field in your local reader's Communication panel. *(Note: This key remains locally in your browser memory and is never committed to GitHub).*