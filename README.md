# MLS Dome Ball Scoresheet

A web-based baseball scoresheet application for tracking games for the Backyard Baseball Club.

## Features

- **Interactive Scoresheet**: Track up to 12 players across 7 innings
- **Real-time Scoring**: Record hits, outs, walks, and runs for each player
- **Opponent Tracking**: Track opponent runs by inning
- **Outs Counter**: Keep track of outs per inning
- **Base Runners**: Mark which bases have runners
- **Statistics**: Automatic calculation of H/AB/R for each player
- **Auto-save**: Game data automatically saves to browser localStorage
- **PDF Export**: Generate professional PDF scoresheets with:
  - BBC logo
  - Team names and date
  - Full scoreboard
  - Batting table with all innings
  - Complete statistics legend

## How to Use

1. Download the `scoresheet_app.html` file
2. Open it in any modern web browser
3. Enter opponent name and date
4. Click on player cells to record at-bats
5. Use the +/- buttons to adjust runs and outs
6. Click "Save PDF" to export your scoresheet

## Baseball Statistics Legend

- **GP**: Games Played
- **AB**: At Bats
- **R**: Runs
- **H**: Hits
- **2B**: Doubles
- **3B**: Triples
- **HR**: Home Runs
- **RBI**: Runs Batted In
- **BB**: Walks
- **SO**: Strikeouts
- **SF**: Sacrifice Flies
- **E**: Errors
- **AVG**: Batting Average
- **OBP**: On Base Percentage
- **SLG**: Slugging Percentage
- **XBH**: Extra Base Hits

## Recording Results

Available results to record:
- **SO**: Strikeout
- **FO**: Flyout
- **FC**: Fielder's Choice
- **E**: Error
- **1B**: Single
- **2B**: Double
- **3B**: Triple
- **HR**: Home Run
- **BB**: Walk
- **SAC**: Sacrifice
- **HBP**: Hit by Pitch

## Technical Details

- Pure HTML/CSS/JavaScript - no dependencies except jsPDF for PDF generation
- Works offline after initial load
- Data persists between sessions using localStorage
- Responsive design works on desktop and mobile

## Browser Compatibility

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Created for the Backyard Baseball Club (BBC)

---

**Note**: This is a single-file application. All you need is the `scoresheet_app.html` file to run it.
