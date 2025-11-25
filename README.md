## Overview Livehelper by JP Tech

This project is a cross-platform desktop application built with Electron that acts as a real-time AI copilot for interviews, meetings, and technical conversations. It captures audio from your microphone and/or system, transcribes speech in real time, and sends the final transcript to an AI model for analysis and responses.

## Key Features

- **Desktop app (Windows/macOS)**  
  - Native-feeling UI with global keyboard shortcuts for quick control.  
  - Runs alongside any video-conferencing tool (Teams, Zoom, Google Meet, etc.).

- **Real-time audio capture**  
  - **Microphone mode:** captures your own voice.  
  - **System mode:** captures what you hear (recruiter, interviewer, meeting audio).  
  - Clear in-app guidance to select the correct output device for system audio.

- **Live transcription and AI integration**  
  - Continuous transcription of the conversation.  
  - Sends the *final* transcript segment to an AI agent after a configurable delay (e.g. 2.5–10 seconds) to avoid partial or noisy prompts.
  - Language setting defines both transcription language and AI response language.

- **Interview-focused configuration**  
  - Presets for real-time technical interviews.  
  - Optional filter to ignore recruiter “small talk” and confirmations (“Okay”, “Great”, etc.), keeping only meaningful content in the transcript and prompts.

- **User experience and shortcuts**  
  - Global hotkeys:  
    - `CmdOrCtrl + Shift + Space` — Show/Hide the application window.  
    - `CmdOrCtrl + Shift + L` — Start/Stop listening.  
    - `CmdOrCtrl + ("+" | "-" | "0")` — Zoom controls for accessibility.

- **Account, sync, and privacy**  
  - Login / sign-up flow to sync configuration and conversations across devices.  
  - Conversations are encrypted before being stored and synced, prioritizing user privacy and data security.

## Use Cases

- Support during live coding and system design interviews.  
- Real-time coaching in recruiter/HR screens.  
- Meeting companion for taking structured notes and capturing decisions and action items.  

## Status

The project is under active development, experimenting with different AI providers and improving the quality of real-time audio capture, filtering, and interview-specific behaviors.

