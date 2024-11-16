# Fitness Tracker App 🏃‍♂️🚴‍♀️  

A feature-rich fitness tracking application built with JavaScript that allows users to log and visualize their running and cycling workouts on an interactive map. The app leverages the browser's **Geolocation API** and **Leaflet.js** for map rendering, along with local storage to save workouts.

---

## 📋 Features  

- **Interactive Map:** Displays the user's current location and allows marking workout spots.  
- **Workout Logging:**  
  - Log running and cycling workouts with details like distance, duration, and cadence or elevation gain.  
  - Automatically calculates pace for running and speed for cycling.  
- **Custom Markers:** Adds markers to the map with activity-specific icons and pop-ups.  
- **Workout List:** Renders a detailed list of logged workouts.  
- **Persistent Storage:** Workouts are saved in the browser's local storage to retain data across sessions.  
- **Responsive UI:** Clean and intuitive interface optimized for different screen sizes.  

---

## 🛠️ Technologies Used  

- **JavaScript:** Application logic and DOM manipulation.  
- **Leaflet.js:** Map rendering and interaction.  
- **Geolocation API:** Fetching the user's current location.  
- **HTML & CSS:** UI structure and styling.  
- **LocalStorage API:** Data persistence.

## 📸 Screenshots  

![Capture](https://github.com/user-attachments/assets/6d4d1412-8cae-4443-8300-631b4e4e6052)


---

## 🚀 Getting Started  

### Prerequisites  
Make sure you have the following installed:  
- A modern web browser (Chrome, Firefox, Safari, etc.).  
- A text editor (like VS Code) for any code modifications (optional).  

### Installation  

1. **Clone the repository**  
   ```bash  
   git clone https://github.com/your-username/fitness-tracker-app.git  
   cd fitness-tracker-app
   ```
2. **Open the project**     
- Simply open the index.html file in your browser to run the app.

3. **Start tracking workouts!**     
- Allow location permissions in your browser.
- Click anywhere on the map to log your workout.

## 🚀 How to Use  

1. **Enable Location:**  
   You can allow location access when prompted by your browser.  

2. **Log a Workout:**  
   - Click anywhere on the map to mark a workout location.  
   - Select the workout type (running or cycling) and fill in the relevant details (distance, duration, etc.).  
   - Submit the form to log the workout.  

3. **View Workouts:**  
   - All logged workouts will be displayed below the map.  
   - Click on a workout to zoom in on its location on the map.  

4. **Reset Data:**  
   - Use the reset feature (if implemented in the UI) to clear all workouts from local storage and start fresh.  

---

## 🐛 Known Issues  

- Browser-specific permissions for location might vary. Please make sure that location services are enabled for proper function.  
- Refreshing the page may temporarily hide unsaved data if local storage is cleared manually.  

---



