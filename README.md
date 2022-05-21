<div align="center"><h1>HP Probook 640 G8</h1></div>

This is a proof-of-concept, "it *kind of* works" type of EFI. This is my first attempt at *"hackintosh-ing"* something, and there are loads of things that could be removed and it would still work. **Tested only on Big Sur**, but with some changes probably would work on all versions starting with Snow Leopard.

# 👷🏼 WHAT DOESN'T WORK?
The list is real big, but here are some that absolutely do not work for whatever reason..:
- the ethernet port??? (weird..?)
- audio
- trackpad
- gpu acceleration (of course, 'cause Iris Xe)

## 🖥️ My hardware

|||
|-:|:-|
| **CPU** | Intel i3-1115G4 |
| **GPU** | Intel Iris X(e) |
| **RAM** | 8Gb of  2666Mhz |
| **Screen** | 1080p  |
| **SSD** | SSSTC CL1-8D256 256gb M.2 |
| **WiFi & Bluetooth** | Intel AX201 |

## 🤔 Why?
The main driving force was boredom, but also because I wanted to do something with a laptop that I've been given, with which, to be honest, I absolutely have nothing to do with.
## 📝 What now?
The first and easiest thing to get working will be the LAN port. After that I'll probably get the trackpad or audio working and wait around until somebody/Apple starts working on supporting Tiger Lake iGPUs. If even a year later, there's still no support in sight, I'll probably just try and hack together something, or maybe get an eGPU.
