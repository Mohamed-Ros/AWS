AWS Course Playlist
This project is an interactive course playlist built for the AWS Course using HTML, CSS, and JavaScript. It provides a simple and user-friendly interface for users to watch AWS-related content with an embedded video player and a list of course videos.

Features
Embedded Video Player: Users can watch videos directly on the page.
AWS Course Playlist: A list of AWS course topics with videos in Arabic.
Logo Overlay: The logo is overlaid on the top of the background image.
Responsive Design: The layout adapts for different screen sizes.
Interactive Playlist: Clicking on a playlist item updates the video player with the corresponding video.
Prevent Right-Click and Inspect Tools: Protection against right-click and browser developer tools.
Structure
1. HTML:
The main structure of the page contains:
A background image representing the course content.
An overlay logo to display branding.
A video player that shows course videos.
A playlist with a list of video links.
Footer displaying copyright information.
2. CSS:
Styling is provided to:
Give the page a clean, modern look with rounded corners, shadow effects, and soft colors.
Ensure responsiveness for different screen sizes using media queries.
Provide hover effects for playlist items to improve interactivity.
3. JavaScript:
Video Player: Handles loading and changing videos when playlist items are clicked.
Event Listeners:
Click: Changes the video source based on the clicked playlist item.
Keyboard and Context Menu Restrictions: Prevents the user from inspecting or accessing browser developer tools (e.g., F12 or right-click).
Auto-Start: Automatically starts the first video when the page is loaded.
