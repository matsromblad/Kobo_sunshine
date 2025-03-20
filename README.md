# Kindle_WeatherCN
Kindle WeatherCN, Chinese calendar system
Principle: Built-in browser accessing H5 pages

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/00-JustSoso.jpg)

# Important first step: Disable screen sleep mode
Click the magnifying glass, enter in the search box: ~ds then press Enter

Operation reference: https://bookfere.com/post/150.html

## Test sites
Test site: https://0111.github.io/Kindle_WeatherCN

Test site: https://0111.github.io/Kindle_WeatherCN/config.html

You can copy this short URL to the Kindle browser for testing: https://dwz.win/a2Cy

Chrome simulation of 600*700 display effect (similar to Kindle 7th generation)

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/05-Chome_WebView.png)

# Method One (No jailbreak required)
## Step 1: Download and extract the Kindle_WeatherCN script

## Step 2: Publish the www directory to a web site

## Step 3: Access http://website in the native browser
![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/03-WebVist_127-0-0-2.png)

## Step 4: Customize your city location
Visit the page http://website/config.html

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/04-Setting_City.png)

After correct configuration, select "Apply Configuration"

After the new page loads, save the bookmark.

# Method Two (Jailbreak + Python3 + Kindle_WeatherCN script)

## Step 1: Jailbreak
https://bookfere.com/post/970.html

## Step 2: Install MRPI and KUAL plugins
https://bookfere.com/post/311.html

## Step 3: Install Python3 plugin
https://bookfere.com/post/311.html#p_8

## Step 4: Copy the Kindle_WeatherCN script
Download, extract, and copy the Kindle_WeatherCN script

Copy to the extensions folder

Directory structure as follows:
```
Kindle disk
└── extensions
    └─── KindleWeatherCN
        ├── bin
        └── www
```

## Step 5: Run "Kindle_WeatherCN" in KUAL
### Run the KUAL tool

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/01-Run_KUAL-Plugin.png)

### Launch the Kindle_WeatherCN service

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/02-Start_KWService.png)

## Step 6: Access http://127.0.0.2 in the native browser
![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/03-WebVist_127-0-0-2.png)

## Step 7: Customize your city location
Visit http://127.0.0.2/config.html

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/04-Setting_City.png)

After correct configuration, select "Apply Configuration"

After the new page loads, save the bookmark.