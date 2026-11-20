# 🕌 Syrian Prayer Times

A responsive web application that displays daily prayer times for Syrian governorates using the Aladhan API.

## 🚀 Overview

Syrian Prayer Times is a single-page web application designed to provide users with accurate daily prayer times for different governorates across Syria.

The application displays the prayer times for Damascus by default and allows users to select another Syrian governorate through a dropdown menu.

It retrieves prayer time data from the Aladhan API and presents it through a simple and user-friendly interface.

## ✨ Features

### 🕌 Prayer Times

- Display the five daily prayer times (Fajr, Dhuhr, Asr, Maghrib, and Isha).
- Display sunrise time.
- Show the current Gregorian date.
- Display the current day in Arabic.
- Retrieve daily prayer timings from the API, accounting for day-to-day changes.

### 📍 Governorate Selection

- Damascus is selected by default.
- Select different Syrian governorates using a dropdown menu.
- Update prayer times based on the selected governorate.
- Change the selected governorate at any time.

### 🔗 API Integration

- Integrated with the Aladhan API to retrieve prayer time data.
- Used Axios to send HTTP GET requests.
- The country is fixed to Syria, while the selected governorate determines the requested location.

### 🛡️ Error Handling

- Handle API request failures.
- Handle network connectivity issues.
- Provide appropriate feedback when prayer time data cannot be retrieved.

### 📱 Responsive Design

- Responsive interface for desktop and mobile devices.
- Single-page application.
- Simple and clear user interface.

## 🧪 API Testing with Postman

- Used Postman to explore and test the API endpoints provided by Aladhan.
- Inspected API requests and responses to understand the required parameters and returned prayer time data.
- Used the tested endpoints as a reference when integrating the API into the application with Axios.

## 🛠️ Technologies Used

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,bootstrap,vite,postman" alt="HTML, CSS, JavaScript, Bootstrap and Vite,postman" />
</p>

- **HTML5:** Structuring the application.
- **CSS3:** Styling and responsive layouts.
- **JavaScript (Vanilla JS):** Implementing application functionality and dynamic interactions.
- **Bootstrap:** Building responsive interface elements.
- **Vite:** Development server and production build tool.
- **Axios:** Sending HTTP requests and retrieving data from the API.
- **Postman:** Exploring and testing API endpoints.

## 🔗 API Reference

This application uses the Aladhan API to retrieve prayer times.

- API Provider: [Aladhan](https://aladhan.com/)
- API Documentation: [Aladhan API Documentation](https://aladhan.com/prayer-times-api)

## ⚙️ Getting Started

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/OMAR-SATTOUT/syrian-prayer-times.git
   ```

2. Navigate to the project directory:

   ```bash
   cd syrian-prayer-times
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL provided by Vite in your browser.

## 🏗️ Production Build

To generate an optimized production build, run:

```bash
npm run build
```

Vite generates the production files inside the `dist` directory.

## 🌐 Live Demo

[View Syrian Prayer Times](https://prayertimes-sy.netlify.app/)

## 👨‍💻 Author

**Omar Sattout**

Software Engineering | Aspiring Full-Stack Web Developer

- GitHub: [Omar Sattout](https://github.com/OMAR-SATTOUT)
- Email: [omar.sattout.ite@gmail.com](mailto:omar.sattout.ite@gmail.com)

---

⭐ Thanks for visiting this project!
