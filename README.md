# my dash board and you can teamplate it

A simple, single-page website designed to be a landing page for social media creators. It allows you to share all of your social links, showcase your stats, and provide a brief bio in one clean, responsive hub.

## Features

* **Clean and Responsive Design:** A modern, single-page layout that looks great on both desktop and mobile devices.
* **Dark & Light Mode:** A built-in toggle for users to switch between dark and light themes.
* **Multilingual Support:** The dashboard includes content translations for both English and Arabic.
* **Customizable Content:** Easily update your profile information, social media links, and stats directly in the HTML file.
* **Live Previews:** Make changes in your code and see them instantly by refreshing the page in your browser.

## Technologies Used

* **HTML:** The core structure of the page.
* **Tailwind CSS:** A utility-first CSS framework for rapid styling.
* **JavaScript:** Manages interactive features like the dark mode and language toggles.
* **Font Awesome:** Provides the social media icons.

## How to Use

To set up your own creator dashboard, follow these simple steps:

1.  Clone or download the project files.
2.  Open `index.html` in your favorite web browser to see the dashboard.
3.  Open the `index.html` file in your code editor (like VS Code) and start customizing.

### Customization

You can personalize the dashboard by editing the following sections in the `index.html` file:

* **Profile Picture:** Replace the placeholder `src="./images/your-photo.jpg"` in the `<img id="profile-image">` tag with the path to your own image file. For best results, keep the image as a square.

* **Profile Details:** Change your name, title, and bio by editing the content inside the `<h1 id="user-name">`, `<p id="user-title">`, and `<p id="user-bio">` tags.

* **Social Links:** Update the `href` attributes for the `<a>` tags with your own social media URLs. You can also edit the visible text for each link in the JavaScript `translations` object at the bottom of the file.

* **Stats:** Update your subscriber count by editing the content of the `<p id="subscribers-count">` tag.

## File Structure

The project has a simple and easy-to-follow file structure:
