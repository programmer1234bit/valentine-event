

# 💖 Love Hub & NAFSI: The Sovereign Soul

A high-end, cinematic web ecosystem for emotional expression. This project allows users to create and send "Vibe-based" messages to loved ones via **Love Hub**, or forge powerful self-oaths in the royal-themed **NAFSI** sanctuary.

---

## 🌟 Features

### 1. Universal Love Hub (`index.html`)

* **Vibe Selection:** Choose between Romantic, Bestie, Healing, or Family themes.
* **Dynamic UI:** Each vibe changes the background gradients and falling particles (hearts, stars, leaves, etc.).
* **Anonymous Mode:** Option to send messages as a "Secret Admirer."

### 2. NAFSI: The Kingdom Within (`soul.html`)

* **Royal Dark Mode:** A cinematic "Gold on Midnight" aesthetic.
* **Rising Embers:** Custom particle system representing inner strength.
* **Royal Decrees:** Create a formal oath to yourself, "signed by the soul."

### 3. AI & Premium Libraries (`message.html` & `library.html`)

* **Message Generation:** Integration with external library logic to suggest poetic messages.
* **Quick-Fills:** Pre-written templates for Strength, Peace, and Glory.

### 4. Interactive Receiving (`receiver.html`)

* **Unboxing Experience:** A "Locked" overlay that requires user interaction to play music and reveal the message.
* **Reactions:** Recipients can react with emojis directly on the card.

---

## 📂 Project Structure

```bash
├── index.html      # Main Hub & Message Creator
├── soul.html       # NAFSI (Self-Love/Empowerment)
├── library.html    # Static message collection
├── message.html    # AI-powered message suggestions
└── receiver.html   # The page the recipient sees

```

---

## 🛠️ Technical Implementation

* **Styling:** Tailwind CSS for rapid, responsive design.
* **Graphics:** [html2canvas](https://html2canvas.hertzen.com/) used to convert HTML/CSS "Decrees" into downloadable PNG images.
* **Data Handling:** Uses `URLSearchParams` to pass messages via links and `localStorage` to move data between the library and the creator.
* **Audio:** Custom audio controllers to handle browser autoplay restrictions via "Sanctuary" entry points.

---

## 🚀 Deployment

This project is optimized for **GitHub Pages**.

1. Push these files to a GitHub repository.
2. Go to **Settings > Pages**.
3. Select the **main** branch and click **Save**.
4. Your site will be live at `https://yourusername.github.io/your-repo-name/`.

---

## 📝 License & Attribution

Designed with 💖 in Dar es Salaam.

* **Fonts:** Cinzel, Montserrat, Dancing Script, Poppins (Google Fonts).
* **Icons:** Emoji-based particle systems.

---
