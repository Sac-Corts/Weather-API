# 🌦️ Weather API
This project is a simple weather application that allows users to check the weather of any city by entering the city and country. It provides real-time weather updates using the OpenWeatherMap API and is built with modern web technologies to ensure performance and responsiveness.

## :star2: Features
- **City Weather Search:** Search for the weather in any city by entering the city name and country.
- **Loading Spinner Animation:** A spinner animation is displayed while waiting for the API to respond.
- **Error Handling:** Displays error messages if the city is not found or if there are other issues with the API request.
- **Responsive Design:** The app is fully responsive, ensuring a seamless experience across devices.

## :pushpin: Technologies Used
- **React (with TypeScript)** for building a scalable and maintainable user interface.
- **Vite** as the build tool for faster development and optimized production builds.
- **CSS Modules** for scoped and modular styling, ensuring no conflicts in styles across components.

## :ok_hand: Performance Optimization

To optimize performance and maintain clean, organized code, I implemented:

- **Zustand** – Used for state management due to its simplicity and minimal boilerplate, ensuring lightweight and fast reactivity when handling weather data.
- **Zod** – Applied for schema validation to ensure that the API responses conform to expected structures, enhancing error handling and data integrity.
- **Custom Hook (useWeather)** – A custom React hook was created to encapsulate the logic for fetching weather data from the API. This makes the component code cleaner and easier to maintain, while also improving reusability across the app.

## :globe_with_meridians: Site
**Site:** https://weather-api-sac.netlify.app/

## 🚀 Getting Started

To run this project locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/Weather-API.git
```
### 2. Navigate to the project folder
```bash
cd Weather-API
```
### 3. Install dependencies
```bash
npm install
```
### 4. Start the application
```bash
npm run dev
```
### 5. Build the application
```bash
npm run build
```