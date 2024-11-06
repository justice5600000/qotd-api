# qotd-api
A bash script that gets a random quote from the API Ninjas quote api.<br>
<br>
Get a free api key: https://api-ninjas.com/register <br>
# Features
- Counts api calls automatically so you dont have to go to the API Ninjas website <br>
- You can enter/edit your api key straight from the command line <br>
# Dependencies
qotd-api depends on: <br>
  - jq
  - curl
# Usage
qotd-api -h : Displays help. <br>
qotd-api -k : Displays prompt to enter/edit your api key. <br>
qotd-api -c : Displays counted api calls. <br>
qotd-api -r : Resets counted api calls. (do this every month) <br>
