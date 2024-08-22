# YouTube Downloader

This is a PyQt6-based desktop application that allows you to download YouTube videos or entire playlists in MP4 format. The application provides a simple and intuitive user interface for managing downloads.

## Features

- Single Video Download: Download individual YouTube videos by entering their URL.
- Playlist Download: Download all videos from a YouTube playlist with a single click.
- Graphical User Interface (GUI): Built using PyQt6, offering a clean and user-friendly interface.
- Progress Display: The application displays the progress of the downloads within the interface.

## Requirements

The project requires the following Python packages:

- PyQt6
- pytubefix (or an equivalent YouTube download library)

These packages are listed in the requirements.txt file. To install them, use:

pip install -r requirements.txt
## Usage

1. Clone the repository:

git clone https://github.com/yourusername/youtube-downloader.git
cd youtube-downloader
2. Install the required dependencies:

pip install -r requirements.txt
3. Run the application:

python main.py
4. Enter the YouTube video or playlist URL in the text box, select the download mode (Single Video or Playlist), and click the "Download" button. The downloaded files will be saved in the downloads directory.

## Customization

- Download Directory: By default, the downloaded videos are saved in a downloads directory located in the same directory as the script. You can change the output_path in the download_video and download_playlist functions to customize the download location.

- UI Customization: The application uses a custom UI designed in Qt Designer (main.ui). If you wish to modify the UI, you can edit the .ui file and regenerate the Python code using pyuic6.
