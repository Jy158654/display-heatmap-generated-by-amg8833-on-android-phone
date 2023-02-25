# heatmap-generator-using-esp32-and-amg8833
A first step in transforming energy management in buildings ⚡

## 🟠 What is this project about?
• This project uses **ESP32**, **ST7789 TFT Display**, and **AMG8833 Thermal Sensor** to generate heatmap based on temperature detection of two-dimentional area: 8x8 (64 pixels). It can be run by Arduino IDE.

## ST7789 TFT Display Connection with ESP32
• Vin 3V3  
• GND GND  
• TFT_MOSI 23  
• TFT_SCLK 18  
• TFT_CS 3  
• TFT_DC 2  
• TFT_RST 4  

## AMG8833 Thermal Sensor Pin Connection with ESP32
• Vin 3V3  
• GND GND  
• SCL SCL  
• SDA SDA  

## Required Libraries
• TFT_eSPI & TFT_eSPI_Setups (refer to this [blog](https://arduino-er.blogspot.com/2020/07/esp32-13-inch-240x240-ips-lcd-st7789.html) to download and modify User_Setup.h inside the library)  
• Adafruit_AMG88xx (download from Arduino IDE)

## ⭐ What's coming next?
• Heat-map generator using ESP32 and AMG8833 sensor is a first step to our project in using these heatmaps to recommend optimized configurations for ACMV system and light fittings as the heatmaps represent the activity level of spaces with the people.  
  
• Our next step involves an extensive collection of heatmaps data to be used in an AI recommendaton model.  
Stay tuned!🔥

## 🛠️ Other applications
• Healthcare  
  
• Retail analytics  
  
• Hospitality 
