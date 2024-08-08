# YTSDownloader
Imagine downloading all the Shorts from your channel or profile and personalising them with a unique watermark. YTSDownloader makes this a reality!<br>
This advanced tool lets you download and customize YouTube Shorts and Instagram Reels in bulk, ensuring that each video showcases your identity and protects your content.

# Features
- Bulk Download: Easily download all Shorts from any YouTube channel or Reels from any Instagram with just a few clicks.
- Custom Watermark: Add a unique image as a watermark to your videos to safeguard your content and enhance your brand.
- Content Protection: Ensures your content is recognized and safeguarded against unauthorized use.
- User-friendly Interface: Provides a graphical user interface (GUI) built with PyQt5, making it easy for users to interact with the application.
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
3. Place your Google Drive service account credentials in a file named credentials.json in the project directory.
4. Add your API information to the variable in config.ini

# Usage
1. Run the script:
```rb
python main.py
```
2. Enter the output_folder in the provided input field.
3. 2. Enter the YT Channel or IG Profile in the provided input field.
4. Click the "Start" button to initiate the download and merge process.
5. The progress bars will indicate the progress of the download and merge processes.
6. Upon completion, the log will display the status of the tasks.

# Dependencies
- Python 3.x
- PyQt5
- yt-dlp
- numpy
- moviepy
- pillow
- pyqt5
- configparser

Ensure the script can access the required URL and the "output_folder" folder is writable.
