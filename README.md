<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Smart Vision Aid – My Reader</title>
</head>
<body>

  <h1>🕶️ Smart Vision Aid – My Reader</h1>
  <h2>Assistive Glasses for the Visually Impaired</h2>

  <h3>📌 Overview</h3>
  <p><strong>Smart Vision Aid</strong> (My Reader) is a wearable assistive device designed to help visually impaired individuals read printed text and improve their independence. This low-cost, offline solution uses a combination of camera input, Optical Character Recognition (OCR), and Text-to-Speech (TTS) technology to convert printed content into speech. It also includes an obstacle detection system to enhance safety while moving.</p>

  <h3>🎯 Features</h3>
  <ul>
    <li>📷 Captures printed text using a camera</li>
    <li>🔍 Extracts text using Tesseract OCR</li>
    <li>🔊 Converts text to speech via eSpeak TTS</li>
    <li>🚶 Obstacle detection using ultrasonic sensors</li>
    <li>🔔 Buzzer alert for nearby objects (40–150 cm)</li>
    <li>🧠 Runs on Raspberry Pi 4</li>
    <li>🌐 No internet required</li>
    <li>⚙️ Lightweight and wearable design</li>
  </ul>

  <h3>🧰 Technologies Used</h3>
  <ul>
    <li><strong>Hardware:</strong> Raspberry Pi 4, Camera Module, Ultrasonic Sensor, Buzzer, Earphones</li>
    <li><strong>Software:</strong> Python, Tesseract OCR, eSpeak TTS, EAST Text Detector</li>
  </ul>

  <h3>🏗️ How It Works</h3>
  <ol>
    <li>The user faces printed text.</li>
    <li>Camera captures the image.</li>
    <li>OCR (Tesseract) extracts text from the image.</li>
    <li>Text is converted to speech using eSpeak.</li>
    <li>Audio is delivered through earphones.</li>
    <li>Ultrasonic sensor monitors distance to detect obstacles.</li>
    <li>If an object is nearby, a buzzer triggers and image is captured for potential text.</li>
  </ol>

  <h3>🚀 Future Improvements</h3>
  <ul>
    <li>Multi-language support</li>
    <li>Real-time video text detection</li>
    <li>Integration of GPS for tracking</li>
    <li>Home automation features</li>
    <li>Directional guidance and voice alerts</li>
  </ul>

  <h3>🧪 Results</h3>
  <p>The prototype accurately reads text and processes it within 30 seconds per word. It enhances daily reading, safety, and autonomy for the user.</p>

  <h3>📚 References</h3>
  <ul>
    <li><a href="https://www.healthgrades.com/right-care/eye-health/vision-loss" target="_blank">Healthgrades – Vision Loss</a></li>
    <li>AlZubaid & Bashar, “Smart Glasses for Blind People”, 2018</li>
    <li>Kumar et al., “Smart Glasses for Visually Impaired Person”, 2021</li>
  </ul>

</body>
</html>
