Easy Youtube video downloader to use on **Google Colab only**

Implements pytube library  

Enter the link of the youtube video in the links section  

Add multiple videos by spereating the links with a comma  

For example: links = ["https://www.youtube.com/link_1", "https://www.youtube.com/link_2"]  

To run on local machine, change **d_video.download('/content', filename='your_video_file.mp4')**  
to **d_video.download(SAVE_PATH, filename='your_video_file.mp4')** where **SAVE_PATH is a valid path** to directory on your machine  

and then **remove files.download('/content/your_video_file.mp4')** from the file  

To run the program:  

Install Dependencies:

Make sure you have pytube installed. You can install it using:
  
'''pip install pytube'''  

Run the Script:

Save the script to a file (e.g., youtube_downloader.py) and run it using Python:

python youtube_downloader.py

