# 🎬 Cinema Verse

### Explore, Enjoy & Review Cinema

Cinema Verse is a movie discovery website designed for movie lovers to explore trending titles, discover content across streaming platforms, view movie information, and browse upcoming releases. It features a cinematic interface with movie posters, animated visual elements, search functionality, and responsive layouts.

The project was developed as a frontend web development project to practice HTML, CSS, JavaScript, UI design, and website organization.

## ✨ Features

- 🏠 **Cinematic Landing Page** — A visually engaging homepage with animated movie posters and an introduction to Cinema Verse.
- 🔍 **Explore Movies** — Browse movie collections and discover different titles.
- 🔥 **Trending Movies** — Dedicated sections for trending and popular content.
- 📺 **Streaming Platform Collections** — Browse titles grouped by Netflix, JioHotstar, Amazon Prime Video, and MX Player.
- 🎞️ **Movie Details** — Explore movie information through sections for overview, cast, crew, audience meter, and user reviews.
- 🚀 **Upcoming Movies** — Discover upcoming movie releases.
- 👤 **Profile Page** — A dedicated user profile interface.
- ⚙️ **Settings Page** — An account settings interface.
- ℹ️ **About Page** — Learn about the purpose and features of Cinema Verse.
- 📱 **Responsive Layouts** — CSS media queries adapt key pages to different screen sizes.
- ✨ **Interactive UI** — JavaScript-powered interactions, search-related behavior, dropdown menus, and visual animations.

*Note: Features requiring persistent data, server-side authentication, or database storage depend on additional backend implementation and are not claimed as completed functionality here.*

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Layout, styling, animations, and responsive design |
| JavaScript | Interactive behavior and movie page functionality |
| Google Fonts | Cinematic typography |
| Font Awesome | Icons |
| Git & GitHub | Version control and repository hosting |
| GitHub Pages workflow | Static website deployment configuration |

## 📂 Project Structure

```text
cinema-verse-main/
│
├── .github/
│   └── workflows/
│       └── static.yml
│
├── Images/
│   ├── Logo/
│   ├── Netflix Images/
│   ├── Hotstar Images/
│   ├── Amezon Prime/
│   ├── Mx Player Images/
│   └── Movie poster and background images
│
├── Movie Database/
│   └── Movie-related assets and folders
│
├── index.html
├── explore.html
├── movie.html
├── upcoming.html
├── about.html
├── login page.html
├── profile.html
├── settings.html
│
├── cst.css
├── moviecss.css
├── script.js
├── jst.js
├── movie_js.js
│
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser such as Chrome, Firefox, or Edge.
- A code editor such as Visual Studio Code.
- Git, if you want to clone the repository.

### 1. Clone the repository

Replace `YOUR-USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR-USERNAME/cinema-verse-main.git
```

### 2. Open the project

```bash
cd cinema-verse-main
```

Open the project folder in Visual Studio Code.

### 3. Run the website

Open `index.html` in your browser, or use the **Live Server** extension in Visual Studio Code.

You can then navigate through the website using its navigation links.

**Important:** Some movie-page resources referenced by the HTML are not included in the uploaded ZIP. Verify that all referenced files, including `responsive.css` and `movie_database.js` where required, are present before running or deploying the complete project.

## 🔄 Website Workflow

```text
           Start
             |
             v
      Landing Page
        index.html
             |
             v
       Explore Movies
       explore.html
             |
       +-----+------+
       |            |
       v            v
 Movie Details   Upcoming Movies
  movie.html     upcoming.html
       |
       v
 Movie Information
 Overview / Cast / Crew
 Audience Meter / Reviews

 Additional Navigation:
 About | Profile | Settings
```

## 📸 Screenshots

Add screenshots of your actual website to a `screenshots/` directory in your repository.

For example:

```text
screenshots/
├── home.png
├── explore.png
├── movie-details.png
├── upcoming.png
└── profile.png
```

After adding the images, display them in this README using relative paths:

### Home Page

![Cinema Verse Home Page](screenshots/home.png)

### Explore Movies

![Cinema Verse Explore Page](screenshots/explore.png)

### Movie Details

![Cinema Verse Movie Details](screenshots/movie-details.png)

*Replace these example screenshot paths with your actual screenshots.*

## 🎯 Project Objectives

- Build a multi-page movie discovery website.
- Develop practical skills in HTML, CSS, and JavaScript.
- Organize and display movie posters and related visual assets.
- Create interactive website navigation and movie browsing experiences.
- Practice responsive web design and CSS animations.
- Understand the workflow of maintaining and deploying a static website with GitHub.

## 🔮 Future Improvements

- Integrate a movie API for dynamic movie information.
- Implement a working review and rating submission system.
- Add secure user authentication with a backend.
- Store user profiles, ratings, and reviews in a database.
- Improve movie search with genre filters and sorting.
- Add watchlists and favorite movies.
- Complete mobile responsiveness and accessibility improvements.
- Deploy and maintain a fully functional live demo.

## 👨‍💻 Authors

**Abhinav Dongrajkar & Shubham**

## 📄 License

This project is intended for educational and portfolio purposes. Add a `LICENSE` file if you wish to define formal permissions for reuse and distribution.

---

⭐ If you like Cinema Verse, consider starring the repository on GitHub.

**Cinema Verse — Explore, Enjoy & Review Cinema.**
