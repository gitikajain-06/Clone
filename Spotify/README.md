# 🎵 Spotify Clone

A **Spotify-inspired web player interface** built using **HTML and CSS**. This project recreates the visual layout of the Spotify Web Player with a dark-themed sidebar, navigation bar, library section, music cards, featured charts, and a bottom music-player interface.

> 🎧 This project is created for **front-end development practice and UI recreation** using HTML and CSS.

---

## 📌 Project Overview

This project is a **front-end Spotify clone** designed to recreate the appearance and layout of a modern music streaming platform.

The interface includes:

* Home navigation
* Search navigation
* Your Library
* Create Playlist section
* Browse Podcasts section
* Back navigation
* Forward navigation
* Explore Premium button
* Install App button
* User icon
* Recently Played section
* Trending Now Near You section
* Featured Charts section
* Music-player interface
* Playback progress bar
* Dark Spotify-inspired design

The project focuses on the **visual design and layout** of a music streaming interface rather than implementing a complete music streaming service.

---

## ✨ Features

### 🏠 Sidebar Navigation

The sidebar contains:

* **Home**
* **Search**

Font Awesome icons are used for the navigation elements.

---

### 📚 Your Library

The library section includes:

* **Your Library**
* Add icon
* Arrow icon
* **Create your first playlist** card
* **Browse podcasts** card

The playlist and podcast sections are presented as separate cards with action buttons.

---

### 🧭 Sticky Navigation

The main content contains a sticky navigation bar with:

* Back navigation icon
* Forward navigation icon
* Explore Premium button
* Install App button
* User icon

---

### 🎧 Recently Played

The **Recently Played** section contains a music card with:

* Cover artwork
* Playlist title
* Description

The current project displays the **Top 50 - Global** card in this section.

---

### 🔥 Trending Now Near You

The project contains a **Trending Now Near You** section with multiple music cards.

Each card contains:

* Music artwork
* Title
* Description

---

### 📊 Featured Charts

The **Featured Charts** section contains chart cards including:

* **Top Songs - Global**
* **Top Songs - India**
* **Top 50 - Global**

The card artwork is loaded from the project's `Image` folder.

---

### 🎵 Music Player Interface

A music-player interface is positioned at the bottom of the page.

It contains:

* Previous control
* Play/pause-style control
* Next control
* Additional player controls
* Current time display
* Progress bar
* Total duration display

The current implementation provides the **visual player interface**. It does not implement actual music playback through JavaScript or a streaming API.

---

### 📱 Responsive Design

The stylesheet includes responsive behavior for smaller screen sizes.

A media query is used at:

```css
@media (max-width: 1000px)
```

Some navigation elements are hidden at smaller widths to improve the layout.

---

## 🛠️ Technologies Used

| Technology             | Purpose                                   |
| ---------------------- | ----------------------------------------- |
| **HTML5**              | Structure of the web page                 |
| **CSS3**               | Styling, layout, responsive design and UI |
| **Font Awesome 7.0.1** | Interface icons                           |
| **Google Fonts**       | Montserrat and Poppins typography         |

---

## 🔤 Fonts

The project uses the following Google Fonts:

* **Montserrat**
* **Poppins**

These fonts are imported directly in `index.html`.

---

## 🎨 Design

The project follows a **dark music-streaming interface** inspired by Spotify.

### Main Interface Colors

| Color     | Usage                               |
| --------- | ----------------------------------- |
| `#000000` | Dark interface elements             |
| `#121212` | Main dark background                |
| `#232323` | Cards and library sections          |
| `#FFFFFF` | Primary text and interface elements |

The CSS also uses different shades and opacity values to create contrast between the sidebar, cards, navigation, and player sections.

---

## 📂 Project Structure

```text
Spotify/
│
├── Image/
│   ├── backward_icon.png
│   ├── card1img.jpeg
│   ├── card2img.jpeg
│   ├── card3img.jpeg
│   ├── card4img.jpeg
│   ├── card5img.jpeg
│   ├── card6img.jpeg
│   ├── forward_icon.png
│   ├── library_icon.png
│   ├── logo.png
│   ├── play_musicbar.png
│   ├── player_icon1.png
│   ├── player_icon2.png
│   ├── player_icon3.png
│   ├── player_icon4.png
│   └── player_icon5.png
│
├── index.html
├── style.css
└── README.md
```

---

## 📄 File Description

### `index.html`

Contains the complete HTML structure of the project.

It includes:

* Sidebar navigation
* Home and Search
* Your Library
* Playlist section
* Podcast section
* Sticky navigation
* Recently Played
* Trending Now Near You
* Featured Charts
* Footer
* Music-player interface

---

### `style.css`

Contains the complete styling for the Spotify clone.

It controls:

* Page layout
* Sidebar
* Navigation
* Library
* Cards
* Buttons
* Sticky navigation
* Footer
* Music player
* Progress bar
* Typography
* Colors
* Spacing
* Responsive behavior
* Hover effects

---

### `Image/`

Contains the images and icons used by the project.

The folder includes:

* Logo
* Library icon
* Back and forward navigation icons
* Music card images
* Player control icons
* Music-player related images

---

## 🚀 How to Run

### 1. Clone the Repository

Open your terminal and run:

```bash
git clone https://github.com/gitikajain-06/Clone.git
```

### 2. Open the Spotify Folder

```bash
cd Clone/Spotify
```

### 3. Open the Website

Open the following file in your browser:

```text
index.html
```

The Spotify Clone will then open in your browser.

---

## 💻 Run Using Visual Studio Code

You can also run the project using **Visual Studio Code**.

1. Open the `Spotify` folder in Visual Studio Code.
2. Open `index.html`.
3. Install the **Live Server** extension if required.
4. Right-click `index.html`.
5. Select **Open with Live Server**.
6. The project will open in your default browser.

---

## 🖥️ Interface Layout

The project is organized into three main areas:

```text
┌─────────────────────────────────────────────────────┐
│                 Sticky Navigation                   │
├────────────────┬────────────────────────────────────┤
│                │                                    │
│   Sidebar      │            Main Content            │
│                │                                    │
│   Home         |  Recently Played                   │
│   Search       │                                    │
│                │  Trending Now Near You             │
│   Library      │                                    │
│                │  Featured Charts                   │
│   Playlist     │                                    │
│   Podcasts     │                                    │
│                │                                    │
├────────────────┴────────────────────────────────────┤
│              🎵 Music Player Interface              │
└─────────────────────────────────────────────────────┘
```

---

## 🎯 Learning Objectives

This project helps in understanding and practicing:

* HTML5 structure
* CSS3 styling
* CSS Flexbox
* CSS positioning
* Sticky positioning
* Fixed positioning
* Responsive design
* Card-based layouts
* Sidebar layouts
* Navigation design
* Typography
* Google Fonts
* Font Awesome icons
* Image handling
* UI recreation

---

## 🔗 External Resources

The project uses the following external resources:

### Font Awesome

Font Awesome is used for interface icons such as:

* Home
* Search
* Plus
* Arrow
* User
* Install App

### Google Fonts

The project uses:

* Montserrat
* Poppins

Both resources are included directly in `index.html`.

---

## ⚠️ Current Project Limitations

This project is currently a **front-end UI clone**.

It does not currently include:

*  JavaScript-based music playback
*  Spotify API integration
*  User authentication
*  Database
*  User registration/login
*  Backend server
*  Real-time search
*  Dynamic playlist creation
*  Real Spotify account connection
*  Online music streaming

The music-player section is currently a **visual interface created with HTML and CSS**.

---

## 🔮 Future Improvements

The project can be extended in the future by adding:

* [ ] JavaScript music playback
* [ ] Functional Play/Pause button
* [ ] Next and Previous song functionality
* [ ] Functional progress bar
* [ ] Search functionality
* [ ] Dynamic playlists
* [ ] User authentication
* [ ] Spotify Web API integration
* [ ] Real music data
* [ ] Volume control
* [ ] Like/Favorite functionality
* [ ] Interactive library
* [ ] Improved mobile navigation

---

## 🎓 Purpose

The main purpose of this project is to practice **front-end web development** and understand how a modern music streaming interface can be structured.

The project demonstrates the use of:

**HTML + CSS + Images + Icons + Web Fonts**

It is intended as a learning and portfolio project.

---

## 📂 Repository

This Spotify Clone is available inside the `Spotify` folder of the GitHub repository:

**GitHub Repository:**
https://github.com/gitikajain-06/Clone

**Project Folder:**
https://github.com/gitikajain-06/Clone/tree/main/Spotify

---

## 📜 Disclaimer

This project is a **Spotify-inspired educational clone** created for learning and front-end development practice.

Spotify and its associated trademarks, logos, branding, and intellectual property belong to Spotify AB.

This project is **not affiliated with, endorsed by, or officially connected to Spotify**.

---



