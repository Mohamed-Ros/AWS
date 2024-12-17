# AWS Course Playlist

This project is designed to display a collection of AWS course videos in Arabic, with a simple, responsive UI using HTML, CSS, and JavaScript. The page contains a video player and a playlist of videos hosted on Google Drive. Users can easily navigate through the courses by clicking on the playlist items, and the video player will load the selected video.

## Features

- **Video Player**: Displays course videos in a responsive player.
- **Playlist**: List of AWS course videos, including:
  - Cloud Concepts Part (1) In Arabic
  - Cloud Concepts Part (2) In Arabic
  - Cloud Security Part (1) In Arabic
  - Cloud Security Part (2) In Arabic
  - Compute In Arabic
  - Storage Database In Arabic
  - Cloud Architecture In Arabic
- **Responsive Design**: The page adjusts to fit different screen sizes, making it user-friendly on both desktop and mobile devices.
- **Video Protection**: Prevents users from right-clicking on the page and accessing developer tools (using custom JavaScript).

## Technologies Used

- HTML5
- CSS3 (Flexbox)
- JavaScript

## How to Use

1. Clone the repository or download the files.
2. Open the `index.html` file in your browser.
3. Click on any video in the playlist to play it in the video player.
4. The page will automatically load the selected video.

## Customization

You can easily add or remove videos from the playlist by updating the list in the HTML file. Each video is represented by a `li` element with a `data-src` attribute pointing to the video URL.

To add a new video, simply copy one of the existing `li` elements and modify the `data-src` and text as needed.

Example:
```html
<li class="video-item" data-src="new_video_link_here">New Course Title</li>
