
# Momochi

🌟 **Momochi** is a versatile file conversion application developed in Python with PyQt5, allowing users to convert images, videos, and audio files into various formats. Featuring an intuitive user interface, Momochi provides a simple and efficient conversion experience with customizable resolution options for videos.

## Features

✨ **Image Conversion**: Convert images between formats such as PNG, JPEG, BMP, and GIF.
🎥 **Video Conversion**: Convert videos into popular formats like MP4, AVI, MOV, and MKV. Choose the output resolution as desired.
🎵 **Audio Conversion**: Convert audio files into formats such as MP3, WAV, AAC, and FLAC.

## Installation

📋 **Requirements**: Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

### Steps to Install Dependencies and run the programmes.

1. **Install Dependencies**: Double-click the `installD.bat` file to install all the required Python packages listed in `requirements.txt`.

2. **Start the Program**: After installing the dependencies, double-click the `start.bat` file to launch the application.

### Main Window

When you open Momochi, you'll see the main window with the following components:

- **Select File Button**: Click to choose the file you want to convert.
- **Convert File Button**: Click to start the conversion process after selecting the file and format.
- **Stop Conversion Button**: Click to stop the ongoing conversion process (only for video conversion).
- **Format Combobox**: Choose the desired output format for your file.
- **Resolution Combobox**: Select the output resolution for video files (if applicable).
- **Progress Bar**: Displays the progress of the video conversion.

### Steps to Convert a File

1. Click on the "Select File" button to choose the file you want to convert.
2. Once selected, choose the desired output format from the format combobox.
3. For video files, you can also select the desired resolution from the resolution combobox.
4. Click on the "Convert File" button to start the conversion.
5. If needed, you can stop the conversion process by clicking on the "Stop Conversion" button.

### Supported Formats

- **Images**: PNG, JPEG, BMP, GIF
- **Videos**: MP4, AVI, MOV, MKV
- **Audio**: MP3, WAV, AAC, FLAC

## Code Overview

The main components of the application are:

- **install_packages**: Ensures all required packages are installed.
- **custom_resize**: Resizes video clips to the specified resolution.
- **VideoConverter**: A QThread class that handles video conversion with progress updates.
- **MainWindow**: The main interface of the application with buttons and comboboxes to manage the conversion process.

## Contributing
Feel free to fork this repository and submit pull requests. Any contributions to improve Momochi are welcome! 

## License
MIT License

Copyright (c) 2024 Ciel

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice, this permission notice, and the following attribution 
notice shall be included in all copies or substantial portions of the Software:

    This product includes software developed by Ciel.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
