# 🎧 Spotify Music Analysis Power BI Dashboard

Welcome to the **Spotify Music Analysis** project! This Power BI dashboard is your one-stop tool for exploring Spotify music data. With it, you can dive into the details of your favorite songs, artists, and playlists, uncover trends in your music taste, and even see how different playlists stack up against each other—all through interactive visuals!

## 📌 What This Project Is All About

This Power BI dashboard helps you:
- Analyze unique song attributes, like tempo, energy, and danceability.
- Discover patterns in your music library, including your top artists, genres, and playlists.
- Compare playlists side by side based on audio features, giving you insights into their distinct vibes.
- Track how your music tastes change over time, whether it’s by artist, genre, or track.

## 🛠️ What You’ll Find in the Dashboard

Here’s what you can explore:
- **Audio Feature Analysis**: Get to know the specific characteristics of your favorite tracks—like loudness, acousticness, and more.
- **Playlist & Genre Comparisons**: See how different playlists or genres vary in terms of key audio features.
- **Your Listening Insights**: Dive into your top tracks, artists, and genres, with visuals that make it easy to spot trends.
- **Interactive Visuals**: Take advantage of Power BI’s interactive filters to drill down into specific playlists, genres, or time periods.

## 🚀 Getting Started

### 1. Prerequisites

- **Power BI Desktop**: Make sure you have Power BI Desktop installed to open and explore the dashboard.
- **Spotify API Credentials** (if you want to update or refresh the data):
  - Sign up on the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/) and create an app to get your **Client ID** and **Client Secret**.

### 2. Open the Power BI Dashboard

1. Download or clone this repository.
2. Open **Spotify Music Analysis.pbix** in Power BI Desktop.

### 3. (Optional) Update Data

Want to bring in fresh data from your Spotify account? Here’s how:
1. Use the included Python scripts (`audio_feature_extractor.py`, `user_insights.py`, `playlist_data.py`) to pull new data from Spotify.
2. Load the new CSV files into Power BI by refreshing the data connections in the dashboard.

### 4. Explore the Dashboard

Once you’re in, you’ll find multiple pages packed with insights and visuals:
- **Feature Distributions**: Visualize song features like energy, tempo, and danceability with histograms and scatter plots.
- **Top Artists & Genres**: Find out who you listen to the most, and what genres dominate your library.
- **Playlist Comparisons**: Compare multiple playlists with radar charts to see how they differ in audio features.
- **Trends Over Time**: Track shifts in your music tastes over time, like changes in your preferred genres or artists.

## 📊 Key Sections in the Dashboard

Here’s a quick rundown of the main pages you’ll see in Power BI:

- **Overview Dashboard**: A summary of key stats and highlights from your music library.
- **Audio Features**: A detailed look at the specific audio characteristics of selected songs or playlists.
- **Top Artists & Genres**: Engaging visuals of your top-played artists and genres.
- **Playlist Comparisons**: Choose and compare multiple playlists by audio features to see their unique profiles.

## 📈 Tips for Customizing and Exploring

- Apply filters to focus on specific time frames or playlists.
- Drill down into certain artists or genres for more granular insights.
- Use slicers on the **Playlist Comparison** page to contrast multiple playlists at once.

## 💡 Contributing

We’d love to see your contributions! If you have ideas for improvements or new features:
1. Fork this repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them.
4. Push the branch (`git push origin feature-branch`).
5. Open a pull request.
