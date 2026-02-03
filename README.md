# 🎬 CinePicks | Cinema Club IIT Roorkee

**CinePicks** is a responsive, frontend web interface designed for the Cinema Club of IIT Roorkee. It serves as a movie recommendation platform where users can browse, search, and filter a curated list of films.

## ✨ Features

* **Responsive Design:** Fully responsive grid layout that adapts to desktop, tablet, and mobile screens.
* **Live Search:** Real-time search functionality to filter movies by title instantly.
* **Genre Filtering:** Filter movies by specific categories (Drama, Sci-Fi, Action, Romance, Thriller).
* **Dark/Light Mode:** Integrated theme toggler (Dark Mode by default) for comfortable viewing.
* **Interactive Rating:** Users can interact with the star rating system on movie cards.
* **Smooth Animations:** Hover effects and smooth transitions on cards and buttons.

## 🛠️ Tech Stack

* **HTML5:** Semantic structure.
* **CSS3:** Custom properties (variables), Flexbox, CSS Grid, and Media Queries.
* **JavaScript (Vanilla):** DOM manipulation for search, filtering, and event handling.
* **Fonts:** Google Fonts (Poppins).

## 🚀 How to Run

Since this project relies entirely on frontend technologies with no build steps or backend dependencies, running it is very simple:

1.  **Download** the `index.html` file.
2.  **Open** the file directly in any modern web browser (Chrome, Firefox, Edge, Safari).
   OR
just go to  https://cinepicks-iitr.netlify.app/

Alternatively, you can host it via **VS Code Live Server** or GitHub Pages.

## 📂 Project Structure

```text
/
└── index.html  # Contains all HTML, CSS, and JS logic

```

## 📝 Customization

To add more movies to the grid, simply duplicate the `.movie-card` div inside the `movies-container` section in the HTML:

```html
<div class="movie-card" data-genre="YourGenre" data-title="movie title">
    <img src="URL_TO_POSTER_IMAGE">
    <div class="movie-info">
        <h3>Movie Title</h3>
        <span>Genre | Year</span>
        <p>Short description of the movie...</p>
        
        <div class="rating">
           </div>

        <a href="YOUTUBE_LINK" class="trailer-btn" target="_blank">
          Watch Trailer
        </a>
    </div>
</div>

```

*Note: Ensure the `data-genre` matches the filter buttons and `data-title` is lowercase for better search compatibility.*

## 🎨 Color Palette

| Color | Hex Code | Usage |
| --- | --- | --- |
| **Primary** | `#0f172a` | Dark Background |
| **Card** | `#020617` | Card Background |
| **Accent** | `#2563eb` | Buttons & Highlights |
| **Text** | `#ffffff` | Primary Text |

## 👤 Author

* Developed by: @unfunnyhemant on IG

## 📄 License

This project is created for educational and community purposes for IIT Roorkee.
