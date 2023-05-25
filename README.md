# PROJECT-switch-games

## SWITCHEROO, a Nintendo Switch Games recommender.
In this project, I have created an app to provide Nintendo Switch game recommendations.

The Nintendo eShop doesn't give an easy way to check games ratings or related games, so I thought it'd be nice to have a games database and a recommender to meet this need.

- In order to get the games list, as well as the critic, users score and genre I scraped the Metacritic site using BeautifulSoup4.
- Later, I clustered the games using an aggregated clustering machine learning model.
- In the final function, the user input the name of a Nintendo Switch game they like, selects which one in case there are more than one matches and then Switcheroo provides 3 recommendations of games are given based on the cluster of the user's chosen game.

You can find the requirements to run this app in the requirements archives.
Credit and sources can also be found on the slides. 

All the best.
