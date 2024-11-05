# Battery Level Indicator Percentage

This project is a Live Battery Indicator built using HTML, CSS, and JavaScript. It provides a real-time display of your device's battery level, visually representing the percentage with gradient colors and animations. The interface also shows whether the device is charging or has a low battery status.

## Features

- Displays battery percentage.
- Indicates whether the battery is full, charging, or low.
- Dynamic color changes based on battery level:
  - Red for low battery (≤ 20%)
  - Orange for medium battery (≤ 40%)
  - Yellow for higher battery (≤ 80%)
  - Green for a full battery (≥ 80%)
- Animation for charging and low battery status.
- Responsive design for all screen sizes.

## Project Structure

```
├── assets
│   ├── css
│   │   └── styles.css       # CSS styles for the battery indicator
│   └── js
│       └── main.js          # JavaScript to fetch and display battery status
└── index.html               # Main HTML file
```

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/live-battery-indicator.git
   ```
2. **Open the project**:
   Navigate to the project folder and open the `index.html` file in your browser.

3. **View the battery status**:
   The page will automatically display your current battery level along with visual cues for charging or low battery status.
