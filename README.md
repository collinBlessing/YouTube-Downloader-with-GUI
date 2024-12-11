
# YouTube Downloader with GUI

A simple Python-based YouTube downloader that allows users to download videos or audio from YouTube using the `yt-dlp` tool. The application provides a graphical user interface (GUI) built with `tkinter`, making it easy to download media files directly to your computer.

## Features
- **Download Audio (MP3)**: Extract and download the audio in MP3 format.
- **Download Video (MP4)**: Download videos along with audio in MP4 format.
- **Progress Display**: View real-time download progress and logs in the GUI.
- **Cancel Download**: Option to cancel the ongoing download process.
- **Cross-platform**: Works on Windows, Linux, and macOS (ensure dependencies are installed).

## Requirements
- Python 3.6 or higher
- `yt-dlp` (the main video downloader tool)
- Required Python libraries:
  - `tkinter` (for the GUI)
  - `json` (for parsing JSON data from `yt-dlp`)
  - `subprocess` (to run commands)
  - `pathlib` (for handling file paths)
  - `threading` (to run the download process in the background)
  - `scrolledtext` (for displaying download progress in a scrollable text box)

### Installation

1. **Install Python 3.6+**  
   Ensure that Python 3.6 or higher is installed on your system. You can download Python from the official site: [python.org](https://www.python.org/).

2. **Install yt-dlp**  
   `yt-dlp` is a command-line tool for downloading videos and audio from YouTube and other websites.

   To install `yt-dlp`, open a terminal or command prompt and run:
   ```bash
   pip install yt-dlp
   ```

3. **Clone or Download the Repository**  
   You can either clone the repository using Git or download the ZIP file directly from GitHub.

   To clone the repository:
   ```bash
   git clone https://github.com/yourusername/yt-downloader.git
   cd yt-downloader
   ```

4. **Install Dependencies**  
   The script uses tkinter, which is usually included with Python. If you’re on Linux, you may need to install it manually:
   ```bash
   sudo apt install python3-tk
   ```

### Usage

#### Run the Application

To start the application, run the `yt_downloader.py` script:
```bash
python yt_downloader.py
```

#### Enter a YouTube URL
1. Open the application window.
2. Paste the YouTube URL of the video you wish to download into the "URL" field.
3. Select the download type (Audio or Video).

#### Start the Download
1. Click the "Download" button to start the download process.
2. The download progress will be shown in the text box.

#### Cancel the Download (Optional)

If you wish to cancel the download, click the "Cancel" button. The current download process will be terminated.

#### Clear URL

You can clear the URL input field by clicking the "Clear" button.

### Example

Here’s a brief walkthrough of how the GUI looks:
- **URL Entry**: Paste the YouTube URL.
- **Download Type**: Choose between "Audio Only (MP3)" or "Video (MP4)".
- **Progress**: The download progress and logs will appear in the text area.
- **Buttons**: "Download" to start downloading, "Cancel" to stop the download, and "Clear" to reset the URL input.

### Notes

- Ensure you have a stable internet connection for downloading videos.
- The output file will be saved in the Downloads folder in your home directory by default.
- The video title is sanitized to create a valid filename (replacing invalid characters with underscores).

### License

This project is licensed under the MIT License - see the LICENSE file for details.

---

# Clone or Download the Repository

You can either clone the repository using Git or download the ZIP file directly from GitHub.

## To clone the repository:

```bash
git clone https://github.com/yourusername/yt-downloader.git
cd yt-downloader
```

## Install Dependencies

### Windows Users

For Windows users, you can download the precompiled executable file from the following link:

[Download Windows Executable]([https://github.com/collinblessing///yourfile.exe](https://github.com/collinBlessing/YouTube-Downloader-with-GUI/tree/main/YTdownloader(WINDOWS)))

### Linux Users
[Download Executable File](https://github.com/collinBlessing/YouTube-Downloader-with-GUI/tree/main/YTdownloader(LINUX))

The script uses `tkinter`, which is usually included with Python. If you’re on Linux, you may need to install it manually:

```bash
sudo apt install python3-tk
```

# Usage

## Run the Application

To start the application, run the `yt_downloader.py` script:

```bash
python yt_downloader.py
```

## Enter a YouTube URL

1. Open the application window.
2. Paste the YouTube URL of the video you wish to download into the "URL" field.
3. Select the download type (Audio or Video).

## Start the Download

1. Click the "Download" button to start the download process.
2. The download progress will be shown in the text box.

## Cancel the Download (Optional)

If you wish to cancel the download, click the "Cancel" button. The current download process will be terminated.

## Clear URL

You can clear the URL input field by clicking the "Clear" button.

# Example

Here’s a brief walkthrough of how the GUI looks:
- **URL Entry**: Paste the YouTube URL.
- **Download Type**: Choose between "Audio Only (MP3)" or "Video (MP4)".
- **Progress**: The download progress and logs will appear in the text area.
- **Buttons**: "Download" to start downloading, "Cancel" to stop the download, and "Clear" to reset the URL input.

# Notes

- Ensure you have a stable internet connection for downloading videos.
- The output file will be saved in the Downloads folder in your home directory by default.
- The video title is sanitized to create a valid filename (replacing invalid characters with underscores).

# License

This project is licensed under the MIT License - see the LICENSE file for details.


### More Advanced Version - Another REPO
[YOUTUBE Downloader](https://github.com/collinBlessing/YoutubeVIdeoDownloader.git)
