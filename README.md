# GestureWorks

**Touchless computer control through hand gestures and voice. Published as a research paper in a Springer book series (ISSN 2524-7565, 2524-7573).**

## The problem

Most everyday computing still assumes a mouse, a keyboard or a touchscreen. That is a barrier in settings where touching shared hardware is undesirable (healthcare, public kiosks) or physically difficult for the user. The Covid-19 years made the gap obvious.

## What we built

A single desktop application with two modules:

- **Gesture-controlled virtual mouse.** A webcam tracks the hand, and specific gestures map to cursor movement, clicks, scrolling and drag.
- **OS-level voice assistant.** Spoken commands open applications, search the web and run system tasks, with a chat-style interface.

Target applications include healthcare, gaming, entertainment and accessibility.

## Stack

Python, OpenCV and MediaPipe for hand detection and landmark tracking, a speech recognition layer for voice commands, and Eel for the desktop interface.

## Repository

| Path | Contents |
|---|---|
| `src/Gesture_Controller.py` | Virtual mouse and gesture mapping |
| `src/app.py` | Chat interface for the voice assistant |
| `src/Dragon.py` | Voice assistant logic |
| `GestureWorks_ResearchPaper_.pdf` | The published paper |

## Team

Team project at Bennett University, built jointly by Tanishq Agarwal, Pransh Gupta and Madhav Aggarwal.
