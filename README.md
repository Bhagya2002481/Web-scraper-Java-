# 🌐 Java Web Scraper – COVID-19 Tracker

This is a Java-based GUI application that fetches **real-time COVID-19 statistics** (Total Cases, Deaths, and Recoveries) for any given country using **web scraping** via the `JSoup` library. The data is extracted from [Worldometer](https://www.worldometers.info/coronavirus/) and presented in a simple **Java Swing interface**.

## 📌 Features

- ✅ Fetches live data for any country
- ✅ Simple and intuitive GUI using Swing
- ✅ Real-time HTML parsing using JSoup
- ✅ Responsive input & error handling
- ✅ Lightweight Maven project setup

## 🛠️ Technologies Used

- **Java** (JDK 17+ recommended)
- **Swing & AWT** – for GUI
- **JSoup** – HTML parsing and scraping
- **Maven** – Project management
- **IntelliJ IDEA / NetBeans** – IDEs for development


## 🚀 Getting Started

### Prerequisites
- JDK 17 or later
- Maven installed
- Internet connection (to fetch live data)

## 🧠 How It Works

- Takes country name input from the user (e.g., `india`, `china`, `us`).
- Builds the URL: `https://www.worldometers.info/coronavirus/country/{country}/`
- Parses the HTML using JSoup.
- Selects DOM elements with the ID `#maincounter-wrap`.
- Displays the result in a styled Swing window.

## 📃 License

This project is open-source and free to use for learning purposes.
