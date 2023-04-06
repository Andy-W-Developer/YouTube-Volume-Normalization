# YouTube-Volume-Normalization
A browser extension to normalize YouTube volumes across videos.

# Contents
- Supported Browsers
- How This Extension Works
- Limitations

# Supported Browsers
- Firefox
- Chrome

# How This Extention Works
- Wait for the advertisement/s to finish
- Simulate two mouse clicks to open the "Stats for nerds" info panel
- Read the "content loudness" dB value
- Adjust the volume to a user specified dB level (defaults to 0dB) using the "content loudness" dB value
- Close the "Stats for nerds" window

# Limitations
- Does not work for livestreams
- Will only increase volumes by a maximum of 15dB as a safety feature
