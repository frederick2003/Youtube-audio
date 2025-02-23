# YouTube Audio Downloader

## Description
This script allows you to download the audio from a YouTube video and convert it into an MP3 file using `yt-dlp` and `ffmpeg`.

## Requirements
Ensure you have the following dependencies installed:

- Python 3.x
- `yt-dlp` (YouTube downloader tool)
- `ffmpeg` (for audio conversion)

You can install the required dependencies using:
```sh
pip install yt-dlp
```

For `ffmpeg`, install it using:
- **Windows**: Download from [FFmpeg official site](https://ffmpeg.org/download.html) and add it to your system `PATH`.
- **Mac (Homebrew)**:
  ```sh
  brew install ffmpeg
  ```
- **Linux (Debian/Ubuntu)**:
  ```sh
  sudo apt install ffmpeg
  ```

## Usage
1. Run the script using:
   ```sh
   python download_to_mp3.py
   ```
2. Enter the YouTube video URL when prompted.
3. The audio will be downloaded and saved as an MP3 file in the `Desktop` folder by default.

## Custom Output Folder
By default, the script saves the MP3 file to the `Desktop` folder. If you wish to change this, modify the `output_folder` parameter in the `download_youtube_audio` function.

## Example
```sh
Enter YouTube video URL: https://www.youtube.com/watch?v=dQw4w9WgXcQ
```
The audio will be downloaded and saved as an MP3 file.

## License
This project is licensed under the MIT License.

