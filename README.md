# React Digital Clock App

This project is a React-based Digital Clock application that displays the current time in a sleek and stylish interface. The clock automatically updates every second and shows the time in a 12-hour format with AM/PM indicators.

## Features

- **Real-Time Clock**: The clock updates every second, displaying the current time accurately.
- **12-Hour Format with AM/PM**: The time is displayed in a 12-hour format with AM/PM notation.
- **Responsive Design**: The application is designed to be responsive and looks great on any device.
- **Beautiful Background**: The clock is displayed over a scenic background with a blurred backdrop, enhancing the visual appeal.

## Technologies Used

- **React**: For building the user interface and handling state management.
- **JavaScript**: Core logic for managing time and updating the clock.
- **CSS**: Styling for the application, including responsive design, text shadows, and a background image.

## How It Works

1. **State Management**: The app uses React's `useState` and `useEffect` hooks to manage the current time state.
2. **Time Formatting**: The time is formatted to a 12-hour format with leading zeros added to hours, minutes, and seconds as needed.
3. **Background and Design**: The clock is displayed over a scenic background image, with a blurred overlay to ensure the time is easy to read.

## How to Use

1. Clone the repository or download the source code.
2. Install dependencies using `npm install`.
3. Run the app locally with `npm start`.
4. The app will open in your browser, displaying the current time.

## Files

- `App.jsx`: The main component that renders the Digital Clock.
- `DigitalClock.jsx`: The core component responsible for displaying and updating the time.
- `index.css`: The CSS file with styles for the app, including background image and clock design.
- `index.js`: The entry point that renders the React app.

## Customization

- **Background Image**: The background image can be easily changed by replacing the image file in the `assets` directory and updating the `background-image` property in the CSS.
- **Clock Style**: The clock's font size, color, and shadows can be customized through the `clock` class in the CSS.
