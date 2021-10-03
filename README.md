# Project SunShine

A cross-platform application developed with flutter to keep track of solar power data, calculating electricity output and recommending solar panel 


## Icon
<a href="http://www.feedbooks.com/"><img src="images/SUnSHine.svg" width="200"/></a>
<br>

## Brief Introduction
<a href="http://www.feedbooks.com/"><img src="images/Page1.svg" width="500"/></a>
<br>

## Product Summary
<a href="http://www.feedbooks.com/"><img src="images/Page2.svg" width="500"/></a>
<br>
## Product Tour


### Log in Page
<a href="http://www.feedbooks.com/"><img src="images/Loginpage.svg" width="500"/></a>
<br>
Log in with your Google or Facebook account to keep track of your solar data and sync across mutiple devices!
### Location Service (with Google Map!)
<a href="http://www.feedbooks.com/"><img src="images/page5.gif" width="500"/></a>
<br>

### Main Home Page
<a href="http://www.feedbooks.com/"><img src="images/page4.gif" width="500"/></a>
<br>



## Features
<a href="http://www.feedbooks.com/"><img src="images/page6.gif" width="500"/></a>
<br>

### Solar Data Display
This Historical Data Tracker includes an interactive page to adjust parameters to view the data. Thanks to NASA Power API, we are able to request the latest data for different parameters, so there is no need to update our database frequently
### Output Calculator
This novel Solar power output calculator helps our homeowners to gauge and get amazed by how much energy solar power can save. Equipped with a simple algorithm, our calculator can compute the output of the solar panel on a particular period. By just inputting your location, we can calculate your electricity bills saved with your local rate!
### Solar Panel Recommendation
Connected with local e-commerce platforms, users can compare the prices from different merchants and even get recommendations from our ends. 
### Data Monitoring (Daily and Monthly)
### Settings
<a href="http://www.feedbooks.com/"><img src="images/setting.gif" width="500"/></a>
<br>

## Requirements

- Any Operating System (ie. MacOS X, Linux, Windows)
- Any IDE with Flutter SDK installed (ie. IntelliJ, Android Studio, VSCode etc)
- A little knowledge of Dart and Flutter

## Features

- [x] Monitor Solar Data
- [x] Calculate Solar Output
- [x] Get recommendation of solar panels 

## Tools

| Name                                                    | Usage                                               |
| ------------------------------------------------------- | --------------------------------------------------- |
| [**FLutter**](https://flutter.dev/)                     | Crafting natively compiled applications             |
| [**Object DB**](https://pub.dev/packages/objectdb)      | NoSQL database to store Favorites & Downloads       |
| [**XML2JSON**](https://pub.dev/packages/xml2json)       | Convert XML to JSON                                 |
| [**DIO**](https://pub.dev/packages/dio)                 | Network calls and File Download                     |
| [**EPub Viewer**](https://pub.dev/packages/epub_viewer) | A flutter plugin for Folioreader to read ePub files |

## Author(s)

-Roger Wong Sie Yang<br />
-Wesley Chiang Yong Jie<br />
-Ryan Lin Xiao Wei<br />

## Appreciation
Special Thanks to NASA Power API for supplying the data and making this possible!

Sources of Dataset:
NASA POWER Web Portal
https://power.larc.nasa.gov/

Monthly historical Dataset
https://power.larc.nasa.gov/api/temporal/monthly/point?parameters=QV2M,WS2M,TS,CLOUD_AMT&community=RE&longitude=111.8305&latitude=2.2873&format=JSON&start=2019&end=2020
Parameters obtained:
earth skin temperature, specific humidity at 2 meters, wind speed at 2 meters, cloud amount






