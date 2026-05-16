# KeyFlow 📞⌨️

A DTMF (Dual-Tone Multi-Frequency) and T9-style text converter with real-time translation and audio playback.

🔗 Repo: https://github.com/jhlassen17/KeyFlow

---

## 🚀 Overview

**KeyFlow** is a utility that bridges classic phone keypad input and modern text processing.

It allows you to:
- Convert **DTMF keypad input → text (T9-style)**
- Convert **text → DTMF sequences**
- Hear **authentic DTMF tones** as you type

Perfect for learning, experimenting, or building telecom-inspired workflows.

---

## ✨ Features

- 📱 **DTMF → Text (T9-style)**
  - Interpret numeric keypad sequences into readable text

- 🔤 **Text → DTMF**
  - Convert text into keypad sequences

- 🔊 **Real-time tone playback**
  - Hear DTMF tones when typing numbers/symbols

- ⚡ **Instant conversion**
  - Real-time processing as you type

- 🧠 **Classic keypad logic**
  - Supports traditional multi-tap/T9-style input

---

## 🧑‍💻 Use Cases

- Learning how phone keypads encode text
- Telecom or signal processing experiments
- Debugging or generating DTMF sequences
- Nostalgic T9-style typing tools
- Educational demos

---

## 🔁 Example Conversions

### Text → DTMF

```
HELLO → 4433555 555666
```

### DTMF → Text (T9-style)
```
7777 33 555 555 666 → HELLO
```

---

## 🔊 Audio Playback

- Plays authentic DTMF tones for each key press
- Helps simulate real telephone keypad behavior
- Useful for:
  - Learning tone patterns
  - Debugging signal flows
  - Interactive demos

---

## ⚙️ How It Works

1. User inputs text or keypad numbers  
2. Input is parsed using T9/DTMF mapping  
3. Output is generated in real time  
4. Optional audio feedback plays corresponding tones  

---

## 🛠️ Tech Stack

- C#
- .NET
- Audio generation (DTMF tone synthesis)
- Event-driven input handling

---

## 📦 Installation

```bash
git clone https://github.com/jhlassen17/KeyFlow.git
cd KeyFlow
dotnet build
▶️ Usage
Run the application:

bash

dotnet run
```

Then:

Enter numbers to hear tones and convert to text
Enter text to generate DTMF sequences

---

## ⚠️ Notes
- Tone playback depends on system audio capabilities
- Timing and spacing affect T9 interpretation
- Behavior may vary slightly depending on implementation details

---

## 🔮 Future Enhancements
- Adjustable tone duration and frequency visualization
- T9 predictive text mode
- GUI improvements
- Export tone sequences as audio files
- Support for pause/delay symbols 
- Waveform display


---

## 🤝 Contributing
Contributions are welcome!

- Open issues for bugs or ideas
- Submit pull requests for improvements


---

## 📄 License
This project is licensed under the MIT License.

See the full license in the LICENSE file.

---

## 👨‍💻 Author

**Jeffrey Lassen**  
Version: `1.0.1.2`  
Last Updated: `05/16/2026`

https://github.com/jhlassen17

---

## ☕ Support

If you find this useful:  
👉 https://buymeacoffee.com/hanf

---