#  Movie Explorer (MoviePlayer App)

Movie Explorer is an iOS application built using **SwiftUI** following the **MVC architecture**, which lets users discover and explore movies using **The Movie Database (TMDB) API**. It supports category browsing (Now Playing, Popular, Top Rated, Upcoming) and allows users to save their favorite movies to a personal list.

---

##  Features

- 🔍 Browse movies from multiple categories (Now Playing, Popular, Top Rated, Upcoming)
- 🎥 View full movie details with poster, rating, and description
- 💾 Save your favorite movies to "My List"
- ✅ SwiftUI UI with horizontal and vertical scrolling sections
- 🌐 Uses real data from [TMDB API](https://developer.themoviedb.org/)
- 🧠 MVC architecture with clear separation of concerns
- 🧩 Error handling and fallback data support


---

##  Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/MoviePlayer.git
   cd MoviePlayer



# Architecture (MVC)
MoviePlayer/
├── Model/
│   ├── Movie.swift
│   └── MovieService.swift
├── View/
│   ├── HomeView.swift
│   ├── MovieSectionView.swift
│   ├── MovieRowView.swift
│   ├── MovieDetailView.swift
│   └── MyListView.swift
├── Controller/
│   └── MovieController.swift
└── MoviePlayerApp.swift


#  Technologies Used

Swift 5
SwiftUI
MVVM-ready MVC base
URLSession networking
UserDefaults for local storage
Xcode 15+

# Fallback Data

If the API is unreachable, static fallback JSON can be injected (available in the project for demo mode).

# Author

Parth Sharma
iOS Developer, Swift Enthusiast
