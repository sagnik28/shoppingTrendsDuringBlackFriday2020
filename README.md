# shoppingTrendsDuringBlackFriday2020
Exploring the trends in shopping during Black Friday 2020 using tweets.


Data was obtained using "snscrape". 
To use snscrape, ensure your system has snscrape installed and then from your command line, enter:
snscrape --jsonl --progress --max-results 30000 --since 2020-11-26 twitter-hashtag "BlackFriday until:2020-11-28"  BlackFridaytweets.json
