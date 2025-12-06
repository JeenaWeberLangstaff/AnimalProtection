# Wildlife Protection: Anti-Poaching Audio Detection System
<h2 align="center"> An edge-deployed machine learning system that detects poaching-related sounds using audio classification. </h2>


### Overview:

This project uses TinyML to identify potential poaching activity in real-time by classifying environmental sounds. Designed for deployment on low-power edge devices in remote wildlife areas where connectivity is limited.

### Problem:

Poaching remains a critical threat to endangered species. Traditional monitoring methods are expensive, require constant human attention, and often detect incidents too late. An automated acoustic detection system can provide early warning when suspicious sounds occur.

### Solution:

A lightweight audio classification model trained to distinguish between:
ClassDescriptionGunshotFirearm discharge - primary threat indicatorFootstepsHuman activity detection for early warningNatureNormal wildlife and ambient sounds (baseline)Natural ElementsWeather sounds (rain, thunder, wind) to reduce false positives

### Technical Approach:

Platform: Edge Impulse
Feature Extraction: MFCC (Mel Frequency Cepstral Coefficients)
Window Size: 1,500 ms
Stride: 750 ms (50% overlap)
Sample Rate: 16,000 Hz
Dataset: 160 samples (40 per class)

### Edge Impulse Project:

#### Full Project: 


#### Slides:

https://www.canva.com/design/DAG6LgfcETI/LN0bIq9VcBk0MGgNhUMlFg/edit?utm_content=DAG6LgfcETI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

#### Presentation: 



### Audio samples sourced from:

Pixabay Sound Effects - Royalty-free sounds
BBC Sound Effects - Broadcast-quality audio
Freesound - Community audio library
 GFX Sounds - Sound effects and Animal Sounds
Quick Sounds - Sound effects library
Free Animal Sounds - Wildlife audio
Zapsplat - Sound effects
SoundDino - Animal sounds
ElevenLabs Sound Effects - AI-generated audio
African wild dog vocalizations from MP3.pm
EpicSoundEffects- Sound Effects
GFXSounds- Sound Effects
Distant gun shots with wind noise.wav by moosegravy -- https://freesound.org/s/435407/ 

### Deployment:

Current: MacBook Pro M2 (2023) - Testing and development
WebAssembly (WASM) - Browser-based live classification 

### Future Edge Deployment Options:

Raspberry Pi
Arduino Nano 33 BLE Sense
Solar-powered microcontrollers for remote wildlife reserves

### Future Improvements:

Expand dataset with more diverse samples
Add vehicle detection class
Integrate with alert notification system
Solar-powered deployment for remote areas
GPS integration for location tracking

### About:
Created by Jeena Weber Langstaff for the Edge Impulse 2025 Competition.
Inspired by conservation work experience in South Africa, this project aims to leverage AI technology to protect endangered wildlife.
