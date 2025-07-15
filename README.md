# HAMR Practice Tool

## Overview

This is a simple web-based practice tool for the Air Force High Aerobic Multi-Shuttle Run (HAMR) test. It simulates the HAMR test by playing beeps at the appropriate intervals based on official Air Force protocols, allowing users to practice their pacing and endurance. The app includes a 5-second countdown before starting, a progress bar for time remaining in each shuttle, and displays the current shuttle (e.g., 1-1, 1-2) and total shuttles completed.

This tool was created by Grok 4, built by xAI.

## Features
- **Countdown Start**: Begins with a 5-second countdown accompanied by beeps.
- **Beep Timing**: Plays beeps at exact intervals matching HAMR levels (up to level 21).
- **Progress Bar**: Visual timer showing time left for each shuttle.
- **Display**: Shows current shuttle (level-subshuttle), shuttles completed, and time left.
- **Stop/Reset**: Ability to stop the test at any time and view final score (total shuttles completed).
- **Responsive Design**: Mobile-friendly with a dark, futuristic theme inspired by Grok/xAI.

## How to Use
1. Open the app in any modern web browser (e.g., Chrome, Firefox, Safari).
2. Click "Start Test" to begin the 5-second countdown.
3. Run shuttles (20 meters each) in sync with the beeps.
4. The app will beep at the end of each interval; aim to reach the line before each beep.
5. Click "Stop Test" when finished or exhausted to see your total shuttles completed.

**Note**: This is for practice only and not an official testing tool. Audio must be enabled in your browser for beeps to play. If audio doesn't work, check browser permissions.

## Deployment
This is a single `index.html` file (with inline CSS and JS). To host it:
- Upload to GitHub and enable GitHub Pages for free public access.
- Or open locally in a browser by double-clicking the file.

## Technical Details
- Built with HTML, CSS, and vanilla JavaScript.
- No external dependencies; fully self-contained.
- Audio generated via Web Audio API for beeps.
- Data sourced from standard Air Force HAMR protocols.

## Credits
Created by Grok 4, powered by xAI. For questions or improvements, feel free to fork and contribute!
