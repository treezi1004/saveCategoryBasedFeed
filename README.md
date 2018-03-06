# saveCategoryBasedFeed

## Description:
savecbf(Save category based feed) is Blogger label based json feed collector.
Main purpose of this project is saving json data by category in the server to use it for blogger widgets(gadgets).

## Feature:
This script works for more than 150 posts feed. It labels the file name by 0000 index numbering. Which mean 0001 will be first 150 posts data and 0002 will be 151~300 posts feed data. This script generate directory itself to store json files. Which means you don't have to worry about creating directory for json files. This script supports other languages too.

## Requirement:
1. Web server: There's nothing free! At least this script is free.
2. PHP in Web server: Only testing and debugging in 7.1xx therefore better go with the same version however it wouldn't really make a problem.

## Setting up:
1. Upload savecbf.php to web server.
2. Use task scheduler(eg. crontab) to run in hourly or daily.

## Problems & Solve:
1. Why not using database?:
  * Duh.... files are quicker, database slower. Json files are good enough for blog data.
2. The name of json file is ugly.. why does it have to use urlencode?
  * To support other languages in any OS. Well i haven't done testing other than Windows but it should be working on linux because i have used similar script on debian server.

## License:
MIT, Simply just use it. I have built it for blogger widgets(gadgets).

## Author:
* Name: Chanil Park
* VUW Computer Science student
* E-mail: treezi1004@gmail.com
* Blog: https://victorcpark.blogspot.com/

