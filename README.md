# saveCategoryBasedFeed

## Description:
savecbf(Save category based feed) is Blogger label based json feed collector.
Main purpose of this project is saving json data by category in the server to use it for blogger widgets(gadgets).

## Notice
This repository is not going to be maintained. However you are welcome to create a pull request and improve the project.

## Feature:
This script works for more than 150 posts feed. It labels the file name by 4 digits(eg. 0000) index numbering. Which mean 0001 will be first 150 posts data and 0002 will be 151~300 posts feed data. This script generates a directory itself to store json files. Which means you don't have to worry about creating a directory for json files.

## Requirements:
1. Web server
2. PHP

## Setting up:
1. Change blog address in savecbf.php file.
2. Upload savecbf.php to web server.
3. Use task scheduler(eg. crontab in linux) to run the script hourly or daily.

## Problems & Solve:
1. Why are we using files instead of database?:
  * Files are quicker, database is slower. Json files are good enough for blog data.
2. The name of json file is ugly.. why does it have to use urlencode?
  * To support other languages.
3. Why PHP? PHP is so bad..
  * You can build same script with other language.

## License:
MIT, Simply just use it. I have built it for blogger widgets(gadgets).

