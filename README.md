# NBA Live Score Tracker

A self-contained web application for real-time NBA game tracking and season-long performance analysis.

## Overview

NBA Live Score Tracker is a lightweight, browser-based tool designed to deliver live scores, dynamic win probability estimates, and comprehensive season trend analysis. Developed as a single-file application, it requires no installation or backend infrastructure, making it immediately accessible across modern web browsers.

## Key Features

- **Real-Time Score Updates** — Automatically refreshes live game scores with intelligent auto-refresh functionality during active matches.
- **Live Win Probability Model** — Provides dynamic win probability calculations that update in response to in-game developments.
- **Full Season Trend Analysis** — Enables loading and visualization of complete 2025–26 season data through interactive charts, including scoring trends and point differentials.
- **Comprehensive Team Coverage** — Supports analysis for all 30 NBA teams.
- **Advanced Filtering Capabilities** — Includes filters for game status (Live, Upcoming, Final) and team-based search functionality.
- **Historical Data Access** — Allows review of games from previous dates via an integrated date selector.
- **Modern User Interface** — Features a clean, dark-themed design optimized for clarity and efficient information consumption.

## Technical Details

The application is implemented as a single HTML file utilizing vanilla JavaScript, Tailwind CSS, and Chart.js. All data processing occurs client-side, ensuring zero setup requirements and broad compatibility.

Primary data is sourced from ESPN’s public APIs, with direct links provided to Basketball-Reference and NBA.com Stats for extended historical and advanced analytics.

## Usage Instructions

1. Open the `nba-live-tracker.html` file in any modern web browser.
2. Live scores update automatically during active games.
3. Access the **Trends** section to analyze season-long team performance and visualizations.
4. Use the date picker to explore historical game data.

No additional software or server configuration is required.

## Data Sources

- **ESPN** — Primary source for live scores and real-time game information.
- **Basketball-Reference** — Recommended for comprehensive historical statistics and advanced player metrics.
- **NBA.com Stats** — Official source for advanced team and player tracking data.

## Author

**Lee Long Kwan (Felix)**  
Department of Electrical and Electronic Engineering  
The University of Hong Kong

*June 2026*