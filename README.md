# 🌦️ Weather Forecast Scraper

## 📌 About  
**Weather-Forecast-Scraper** is a Python script that scrapes weather forecast data for a given location. It fetches real-time weather details and presents them in a structured format.

## 🖥️ Example Output  
If you want to scrape weather data for a specific location, the output may look like this:  
![Weather Forecast Example](https://github.com/user-attachments/assets/2ffc132a-704f-489a-be87-c795fbe1e6e1)

## 🚀 Features  
- 🌍 **Fetch real-time weather forecasts**  
- 📊 **Scrape temperature, humidity, and more**  
- 🔧 **Lightweight and easy to use**  
- 📌 **Customizable for different locations**

### ✂️ **CSS Selectors Used for Scraping**
The script identifies and extracts weather details using the following CSS selectors:

| Weather Data         | CSS Selector |
|----------------------|-------------|
| **Location Name**    | `div.panel-title` |
| **Forecast Period** (e.g., Tonight, Sunday) | `p.period-name` |
| **Weather Icon**     | `img.forecast-icon` (Extract `src` attribute) |
| **Temperature (High)** | `p.temp-high` |
| **Temperature (Low)** | `p.temp-low` |
| **Short Description** (e.g., "Mostly Cloudy") | `p.short-desc` |
| **Full Forecast** (Hover text on the image) | `img.forecast-icon[title]` (Extract `title` attribute) |

## 🏗 Tech Stack  
This project is built using the following technologies:  

| Technology        | Description                           |
|------------------|-----------------------------------|
| **🐍 Python**    | Core programming language used    |
| **🌐 Requests**  | Fetches HTML content from the web |
| **🍲 BeautifulSoup** | Parses HTML and extracts data |


## Pandas DataFrame looks as following:
<img src="https://github.com/user-attachments/assets/f634eec1-2f9a-4edd-bce8-05cfc795de6e" width="750">
