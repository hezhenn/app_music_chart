# 🎧 Music Chart Application

A simple **web application** that displays a **music chart** and allows users to **search** for **songs**.

**Built** as part of a web development **learning** project.

This application **combines** the following technologies: `HTML`, `CSS`, `JS`, and `Python`.

<br>

## 📦 Features

- **Music Chart** - View a list of top songs
- **Search Functionality** - Search for specific songs in the chart
- **Responsive Design** - Works on both desktop and mobile devices
- **Local Storage** - Saves song data in the browser's local storage

<br>

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/hezhenn/app_music_chart
cd app_music_chart
```

Run the application:

```bash
python src/main.py
```

Open your web browser and navigate to:

```
http://localhost:8080
```

<br>

## 📦 Project Structure

```
app_music_chart
├── src/
│   ├── static/
│   │   │
│   │   ├── css/
│   │   │   └── styles.css   # CSS styles
│   │   └── js/
│   │       └── script.js    # Client-side JavaScript
│   │
│   ├── templates/
│   │   ├── index.html       # Main page with music chart
│   │   ├── search.html      # Search page
│   │   └── error.html       # Error page
│   │
│   └── main.py              # Python HTTP server
│
├── gitignore
└── README.md
```

<br>

## 📦 Usage

**Viewing the Chart:**

- The main page displays a list of top songs
- Songs are loaded from the HTML and stored in the browser's local storage

**Searching for Songs:**

- Click on "Search The Song" to navigate to the search page
- Enter a song name in the search box
- Click the "Search" button to find matching songs

<br>

## 📦 Technologies Used

- **Backend**: `Python` (`http.server`)
- **Frontend**: `HTML5`, `CSS3`, `JavaScript`
- **Storage**: Browser Local Storage

---