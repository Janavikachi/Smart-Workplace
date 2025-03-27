# Smart Workplace

Smart Workplace is an AI-powered productivity suite that combines voice-controlled application management with PowerPoint and Whiteboard integration.

## Features

### Nova AI Assistant
- Voice command support for launching and controlling applications
- Seamless integration with PowerPoint and Whiteboard
- Natural language processing for application control
- Process management and monitoring
- Voice-activated commands for presentations and whiteboard sessions

### PowerPoint Integration
- Launch PowerPoint presentations using voice commands
- Navigate through slides using voice control
- Close presentations with voice commands
- Process monitoring and management

### Whiteboard Integration
- Launch Microsoft Whiteboard using voice commands
- Control whiteboard sessions through voice
- Efficient process management for whiteboard sessions


## Installation

1. Clone the repository:
```bash
git clone https://github.com/Janavikachi/Smart-Workplace.git
cd Smart-Workplace
```

2. Create a virtual environment:
```bash
python -m venv venv
```

3. Activate the virtual environment:
```bash
.\venv\Scripts\activate
```

4. Install Python dependencies:
```bash
pip install -r requirements.txt
```

## Directory Structure

```
smart-workplace/
├── Nova/
│   ├── nova.py                 # Main AI assistant script
│   └── run_nova.bat           # Windows batch file to run Nova
├── PowerPoint/                 # PowerPoint integration module
├── whiteboard/                # Whiteboard integration module
├── requirements.txt
└── README.md
```

## Module Usage Instructions

### 1. Nova AI Assistant (Nova/nova.py)
- Start Nova using `run_nova.bat` or `python nova.py`
- Available voice commands:
  - "Launch PowerPoint" - Opens PowerPoint
  - "Close PowerPoint" - Closes PowerPoint
  - "Launch Whiteboard" - Opens Whiteboard
  - "Close Whiteboard" - Closes Whiteboard
  - "Stop Nova" - Terminates the AI assistant

### 2. PowerPoint Integration (PowerPoint/)
- Ensures proper communication between Nova and PowerPoint
- Handles process management for PowerPoint applications
- Manages presentation states and commands

### 3. Whiteboard Integration (whiteboard/)
- Manages communication between Nova and Microsoft Whiteboard
- Handles process management for Whiteboard sessions
- Controls whiteboard states and commands

## Voice Commands Reference

1. PowerPoint Commands:
   - "Launch PowerPoint" - Starts PowerPoint application
   - "Close PowerPoint" - Closes active PowerPoint instance
   - "Next slide" - Moves to next slide
   - "Previous slide" - Moves to previous slide

2. Whiteboard Commands:
   - "Launch Whiteboard" - Opens Microsoft Whiteboard
   - "Close Whiteboard" - Closes active Whiteboard session

3. System Commands:
   - "Stop Nova" - Terminates the AI assistant
   - "Status" - Reports current application states

## Troubleshooting

1. Voice Recognition Issues:
   - Ensure you're in a quiet environment
   - Speak clearly and at a moderate pace
   - Check microphone settings in Windows

2. Application Launch Issues:
   - Verify PowerPoint and Whiteboard are properly installed
   - Check process management permissions
   - Ensure no conflicting applications are running
 
 ## Authors

1. [Janavi Kachi](https://github.com/Janavikachi) - VU2S2223008
   - GitHub: [@Janavikachi](https://github.com/Janavikachi)
   - Email: vu2s2223008@pvppcoe.ac.in

2. [Prerana Patil](https://github.com/PreranaP09) - VU2S2223009
   - GitHub: [@PreranaP09](https://github.com/PreranaP09)
   - Email: vu2s2223009@pvppcoe.ac.in

3. [Nikhil Sable](https://github.com/Nikhilsable2405) - VU2S2223015
   - GitHub: [@Nikhilsable2405](https://github.com/Nikhilsable2405)
   - Email: vu2s2223015@pvppcoe.ac.in

4. [Aaditya Sharma](https://github.com/aadimatrix68) - VU2F2122050
   - GitHub: [@aadimatrix68](https://github.com/aadimatrix68)
   - Email: vu2f2122050@pvppcoe.ac.in
