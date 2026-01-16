<div align="center">

  <img src="https://placehold.co/1200x240/0f0f0f/8b5cf6?text=FRAMEFORGE&font=orbitron" alt="FrameForge" width="100%">

  <h3>— local text-to-video prototype —</h3>

  <br>

  <a href="https://github.com/yourusername/frameforge/releases/latest">
    <img src="https://img.shields.io/badge/Download%20v1.0-8b5cf6?style=for-the-badge&logo=github&logoColor=white" height="32">
  </a>

</div>

---

### What is this?

FrameForge is a research prototype that generates **simple vertical videos from text using only local AI models**. It runs entirely offline. No internet is required after installation. No data is sent anywhere.

This is **not a professional video tool**. It is a demonstration that privacy-respecting AI content generation is possible — even if limited.

---

### What it actually does

You type a short prompt:  
> "A robot explaining photosynthesis in a garden"

The app will:
1. Generate a short script (up to 5 sentences) using Phi-3-mini  
2. Synthesize speech using Coqui TTS (English, robotic voice)  
3. Generate **one static image per sentence** using Stable Diffusion Turbo  
4. Combine them into a 1080×1920 MP4 file with centered captions  

**Important**: Each image is generated independently. Characters, clothing, and backgrounds **will not match** between scenes. This is **not a coherent video** — it is a **slideshow with voiceover**.

---

### Performance

- On a modern laptop (16 GB RAM, GPU): ~12 minutes for a 30-second output  
- On Raspberry Pi 5: ~90 minutes for 30 seconds, 720p only  
- Output length capped at 45 seconds  

Voice quality is synthetic. Captions are basic text. There are no transitions, animations, or effects.

---

### What it is not

- Not a replacement for real video editing software  
- Not capable of generating consistent characters or realistic scenes  
- Not suitable for professional or commercial channels  
- Not a "viral video maker"  

---

### Why use it?

- You want to avoid cloud-based AI generators  
- You need to keep your prompts and projects private  
- You are a developer or student experimenting with local AI pipelines  
- You value transparency over convenience  

---

### Downloads

- Windows: [frameforge-win.exe](https://github.com/yourusername/frameforge/releases/download/v1.0/frameforge-win.exe)  
- macOS (Apple Silicon): [frameforge-mac-arm64.dmg](...)  
- Linux: [frameforge-linux.deb](...)

All binaries are built from this repository. No telemetry. No network calls.

---

### License

MIT License. You own all generated content.
