# Python-Weather
Simple Python script to fetches weather :sunny: data from [Open Weather Map](http://openweathermap.org/).
* Written by Mohammad Laif [Mzdhr](http://www.Mzdhr.com).
* Licensed under The [MIT License](../blob/master/LICENSE).

***

## Version
**0.1**
>*Still in Beta, while learning Python :heart_eyes: & Git in my sparetime!*

***

## Requirement
* API: obtain it from here:
http://openweathermap.org/appid
* Your City ID: get it from:
http://bulk.openweathermap.org/sample/city.list.json.gz

***

## Install
*not yet done, but you can clone it*
git clone https://github.com/mzdhr/weather.git

***

## Usage from Terminal
For the first time:
$ python3 weather.py --config
1. Add your city ID, then hit enter.
2. Add your API key, then hit enter.
3. Type your preferred unit, then hit enter.

![Terminal Weather](../blob/master/img/img01.png "Terminal Weather")

Then when you want to check the weather type:
$ python3 weather.py

![Terminal Weather](../blob/master/img/img02.png "Terminal Weather")

***

## Usage from PyCharm IDE
1. Create 'weather_config.ini' inside weather directory. that contains:
```
[DEFAULT]
prefer_unit = metric
user_api = ******************************
city_id = ******
```
2. Run the script from PyCharm.

![Terminal Weather](../blob/master/img/img03.png "Terminal Weather")

***

## To Do:
- [ ] add icons.
- [ ] setup.py.
- [ ] argparse library for argv.
- [ ] __main__.py.
- [ ] __init__.py.
- [ ] refactor.
- [ ] generate documentation with Sphinx.

***

### This readme file created with:
* [Online Markdown Editor](http://dillinger.io/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links)
* [Basic writing and formatting syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
* [EMOJI CHEAT SHEET](http://www.emoji-cheat-sheet.com/)
