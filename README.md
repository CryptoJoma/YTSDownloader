<h2 align="center">
  YTSDownloader - v0.0.1
</h2>
<p align="center">Imagine downloading all the Shorts from your channel or profile and personalising them with a unique watermark. YTSDownloader makes this a reality!<br>
This advanced tool lets you download and customize YouTube Shorts and Instagram Reels in bulk, ensuring that each video showcases your identity and protects your content.</p>

<br/>

<div align="center">

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com) &nbsp;
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) &nbsp;
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://forthebadge.com) &nbsp;
![GitHub Repo stars](https://img.shields.io/github/stars/CryptoJoma/CyberPunk-Portfolio?color=blue&logo=github&style=for-the-badge) &nbsp;
![GitHub forks](https://img.shields.io/github/forks/CryptoJoma/CyberPunk-Portfolio?color=blue&logo=github&style=for-the-badge)

</div>

<h3 align="center">
    🔹
    <a href="https://github.com/CryptoJoma/YTSDownloader/issues">Report Bug</a> &nbsp; &nbsp;
    🔹
    <a href="https://github.com/CryptoJoma/YTSDownloader/issues">Request Feature</a>
</h3>

## TL;DR

You can fork this repo to modify and make changes of your own. Please give me proper credit by linking back to [CryptoJoma](https://github.com/CryptoJoma/YTSDownloader). Thanks!

# Features
- Bulk Download: Easily download all Shorts from any YouTube channel or Reels from any Instagram with just a few clicks.
- Custom Watermark: Add a unique image as a watermark to your videos to safeguard your content and enhance your brand.
- Content Protection: Ensures your content is recognized and safeguarded against unauthorized use.
- User-friendly Interface: Provides a graphical user interface (GUI) built with PyQt6, making it easy for users to interact with the application.
- Progress Tracking: Displays progress bars for both download and merge processes, allowing users to track the progress of each task.
- Logging: Logs the status of each task, providing users with detailed information about the download and upload operations.
- Error Handling: Handles errors gracefully and provides informative messages to users in case of download or upload failures.
- Customization: Allows users to customize the behavior of the application by configuring parameters in the source code.
- Simple Configuration: Easily specify the database names to download.

# Installation
1. Clone the repository to your local machine:
```rb
git clone https://github.com/CryptoJoma/YTSDownloader.git
```
2. Install the required Python packages:
```rb
pip install -r requirements.txt
```
3. Add your information to the variables in config.ini

# Usage
1. Run the script:
```rb
python main.py
```
2. Enter the output_folder in the provided input field.
3. Enter the YT Channel or IG Profile in the provided input field.
4. Click the "Start" button to initiate the download and merge process.
5. The progress bars will indicate the progress of the download and merge processes.
6. Upon completion, the log will display the status of the tasks.

# Dependencies
- Python 3.x
- PyQt6
- yt-dlp
- numpy
- moviepy
- pillow
- configparser

Ensure the script can access the required URL and the "output_folder" folder is writable.

You also need to ensure that ffmpeg is installed on your PC.
