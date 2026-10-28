# Live Sports Scoreboard

A live, multi-sport scoreboard that combines match ratings, scores, team logos, and TV listings to help identify the most interesting games to watch.

## View the Scoreboard

**[Open the Live Sports Scoreboard](https://blakeduncan25.github.io/)**

The website features a responsive, mobile-friendly interface with match ratings, live scores, team information, and available broadcast listings.

## Features

- **Live scores:** Retrieve live sporting events from TheSportsDB.
- **Match ratings:** Rank games by rating to highlight the most compelling matchups.
- **Score projections:** Incorporate model-generated projections into the data workflow.
- **TV listings:** Display available broadcast information alongside each matchup.
- **Automated updates:** Process and publish scoreboard updates through Python and the GitHub API.
- **Responsive design:** Dedicated HTML and CSS provide a more app-like experience on desktop and mobile.

## Technology

- Python and pandas
- TheSportsDB API
- Google Sheets
- GitHub Contents API
- GitHub Pages
- HTML and CSS

## How It Works

1. Fetch live sporting events.
2. Calculate or retrieve projections and ratings.
3. Process the results and TV listings through Google Sheets.
4. Generate a standalone HTML scoreboard.
5. Publish the updated page to GitHub Pages.

## Notes

Scores, ratings, and broadcast availability depend on the underlying data sources. TV listings may vary by region, and the scoreboard only displays the events returned by the data pipeline.

---

**[View the live scoreboard →](https://blakeduncan25.github.io/)**
