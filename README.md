# Sign2Text - ASL Translation App
![Sign2Text](https://raw.githubusercontent.com/Maz-AX/Sign2Text-Demo/refs/heads/main/docs/screenshots/ic_launcher.png "Sign2Text")

## Overview
Sign2Text is an open-source American Sign Language (ASL) translation application that uses machine learning to convert sign language gestures into text in real-time. Built with Flutter and powered by PyTorch, it provides an accessible way for users to translate ASL signs through their mobile device's camera.

Currently, Sign2Text can only translate ASL Alphabet gestures.

## Features
- Real-time ASL gesture recognition
- Image capture and processing
- User authentication and profile management
- Dark/Light theme support
- Responsive design for various screen sizes
- Data collection module for continuous improvement

## Tech Stack
- **Frontend**: Flutter/Dart
- **Backend**: Python (FastAPI, Flask)
- **ML Framework**: PyTorch
- **Authentication**: Firebase
- **Cloud Infrastructure**: Google Cloud Run
- **CI/CD**: GitHub Actions

## Architecture
```
[Flutter App]
     │
     ├──► [Authentication Service]
     │
     ├──► [ML Inference Service]
     │
     └──► [Data Management Service]
```

## Screenshots
![Sign2Text](https://raw.githubusercontent.com/Maz-AX/Sign2Text-Demo/refs/heads/main/docs/screenshots/screenshot.jpg "Sign2Text" width="200" height="200")

## Demo

This repository contains documentation and demonstrations of the Sign2Text application. To request access to the APK for evaluation or research purposes, please contact:

**Email:** maaman@ucsc.com

Please include:
- Your name and organization
- Intended use case
- Research/Development purpose

### Requirements (Upon APK Access)
- Android 6.0 (API level 23) or higher
- Camera permission
- Internet connection for full functionality
- 100MB free storage

## Installation
1. Download the APK from the releases page
2. Enable installation from unknown sources in your device settings
3. Install the APK
4. Grant required permissions when prompted

## Contributing
While this is a demo version of a larger project, we welcome feedback and suggestions through issues.

---

# LICENSE

Copyright (c) 2024 Yeterly Software

## Terms of Use

This repository ("Software") and its documentation are protected by copyright law and international treaties. The Software is licensed, not sold, and is intended for demonstration and educational purposes only.

### 1. Permissions
Users are permitted to:
- View and study the public documentation
- Fork this repository for personal study
- Request access to the application binary (APK) through proper channels

### 2. Restrictions
Unless explicitly authorized in writing, users may not:
- Redistribute any part of the Software
- Create derivative works based on the Software
- Reverse engineer, decompile, or disassemble the Software
- Use the Software for commercial purposes
- Access or attempt to access the application binary without permission

### 3. APK Access
- The application binary (APK) is available only through direct request
- Access is granted on a case-by-case basis
- Usage terms will be provided with approved access
- Additional agreements may be required for APK access

### 4. Intellectual Property
- All intellectual property rights are retained by Yeterly Software
- No license to patents, trademarks, or other rights is granted by this document
- The Software's machine learning models and algorithms remain proprietary

### 5. Disclaimer
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

### 6. Limitation of Liability
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### 7. Contact
For permissions, access requests, or questions:
Email: maaman@ucsc.edu

### 8. Termination
Yeterly Software reserves the right to terminate any access or permission granted under this license at any time and for any reason.

This license is subject to change without notice. Continued use of the Software constitutes acceptance of such changes.

---
