# Wojak Tracker v2

**Wojak Tracker v2** is a real-time camera-based expression tracker that uses computer vision to detect your facial expression and determine which **Wojak expression** you are making.

Point your camera at yourself, make a face, and let the tracker decide which Wojak you are.

## Features

* 📷 **Real-time camera tracking**
* 🧠 **Facial expression recognition**
* 😐 Detects different Wojak-style expressions
* ⚡ Live expression updates
* 🖥️ Simple, interactive interface
* 🔒 Camera processing designed to run locally
* 🎭 Built around the classic Wojak meme expressions

## How It Works

Wojak Tracker v2 uses your webcam to analyse facial landmarks and expression characteristics in real time.

The general pipeline is:

```text
Camera
   ↓
Face Detection
   ↓
Facial Landmarks
   ↓
Expression Analysis
   ↓
Wojak Classification
   ↓
Live Wojak Result
```

The tracker analyses features such as:

* Eye position
* Eyebrow position
* Mouth shape
* Smile/frown intensity
* Eye openness
* Overall facial expression

These features are then mapped to a Wojak expression category.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/mundanedotzip/wojak-tracker-v2.git
cd wojak-tracker-v2
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the application

```bash
npm run dev
```

Open the local development URL shown in your terminal.

### 4. Allow camera access

When prompted by your browser, allow the application to access your webcam.

Look at the camera and start making Wojak faces.


## Wojak Expressions

The tracker can be expanded with different Wojak classifications, for example:

| Expression          | Description                |
| ------------------- | -------------------------- |
| 😐 NPC Wojak        | Neutral / emotionless      |
| 😭 Crying Wojak     | Sad / crying expression    |
| 😎 Chad Wojak       | Confident expression       |
| 😡 Angry Wojak      | Angry / frustrated         |
| 😰 Doomer Wojak     | Worried / distressed       |
| 😂 Laughing Wojak   | Strong smile / laughter    |
| 🤨 Suspicious Wojak | Raised eyebrow / skeptical |
| 🗿 Stoic Wojak      | Minimal expression         |

The classification system can be expanded with additional expressions and custom thresholds.

## Privacy

Wojak Tracker v2 is designed with privacy in mind.

The application uses your camera to analyse your facial expression. If processing is performed locally in the browser, camera footage does not need to be uploaded to a server.

> **Note:** Always check the implementation and browser permissions to verify how camera data is processed in your particular deployment.

## Development

To modify the tracker, install the dependencies and run the development server:

```bash
npm install
npm run dev
```

After making changes, test the tracker using different lighting conditions, camera angles, and facial expressions.

## Roadmap

* [ ] Improve expression classification
* [ ] Add more Wojak expressions
* [ ] Improve detection accuracy
* [ ] Add expression confidence scores
* [ ] Add Wojak score/history
* [ ] Add screenshots of detected expressions
* [ ] Add mobile camera support
* [ ] Add custom Wojak categories
* [ ] Improve UI/UX
* [ ] Add leaderboard / sharing functionality

## Contributing

Contributions, suggestions, and new Wojak classifications are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-expression
```

3. Make your changes
4. Commit your changes

```bash
git commit -m "Add new Wojak expression"
```

5. Push the branch

```bash
git push origin feature/new-expression
```

6. Open a Pull Request

## License

This project is provided for educational and entertainment purposes.

---

### 🗿 Become the Wojak

**Look into the camera. Make the face. Find out which Wojak you are.**
