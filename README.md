# Remote Healthcare System

> [!WARNING]
> **Deprecated / No Longer Maintained**
>
> This project is no longer actively maintained and should be treated as **deprecated**. The repository has had no visible updates since **November 15, 2022**. It is preserved here for reference, learning, and archival purposes only.

A Python-based prototype for a **remote healthcare monitoring workflow** focused on senior citizens. The project combines webcam-based face detection, basic face recognition, pose detection, and schedule tracking into a CLI-style application intended to simulate assisted remote care scenarios.

## Table of Contents

- [Overview](#overview)
- [Current Status](#current-status)
- [Features](#features)
- [Repository Structure](#repository-structure)

## Overview

Remote Healthcare System is an experimental Python project that attempts to support assisted monitoring through:

- **Live webcam capture**
- **Face detection in images and video**
- **Face recognition using trained images**
- **Pose detection and pose classification**
- **Simple CSV-based activity scheduling**

The codebase suggests the project was intended to help monitor routine activity for elderly or dependent users, with future plans for emergency-response-style workflows.

## Current Status

This repository is **deprecated** and **no longer maintained**.

Reasons to treat it as archival software:

- No visible recent development activity
- Several functions appear incomplete or broken
- Some code paths reference missing or inconsistent functions
- Certain file paths are hardcoded for a specific local Windows machine
- Dependency setup is not packaged or pinned

Use this project as a **reference prototype**, not as production-ready healthcare software.

## Features

### Implemented / Partially Implemented

- Command-line home screen for selecting features
- Webcam-based face detection
- Image-based face detection
- Face recognition against locally trained images
- Webcam-based pose classification
- CSV schedule generation and viewing
- Simple camera capture utility that saves `Client.jpg`

### Planned / Incomplete

- User login and registration flow
- Face registration from user profiles
- Automated emergency response behavior
- Fully working schedule upload/update flow
- Stable log management and training flow

## Repository Structure

```text
Remote-Healthcare-System/
├── README.md
├── LICENSE
├── start.py
├── camera.py
├── face_detect.py
├── face_detect_2.py
├── pose_detect.py
├── schedule.py
├── schedule.csv
├── Giants.csv
├── test.py
├── test2.py
└── try.py
