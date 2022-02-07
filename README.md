# Automating Spotify playlist creation

This Python project utilises the BeauitfulSoup, Requests and Spotipy libraries to make requests to the Billboard Hot 100 and scrape the songs at a given date. Spotipy is then used to authenticate Spotify and allow access to third party applications (such as this Python program) without using the username and password associated with the account, instead using a unique client id and client secret. Once authentication is completed, the songs that were previously scraped from Billboard are searched for on Spotify and added to a new playlist. 



### Prerequisites

This project relies on the BeautifulSoup Requests and Spotipy libraries.

### Installing

The following command can be used to install the requests library

```
$ python -m pip install requests
```
The following command can be used to install the BeautifulSoup library

```
$ pip install beautifulsoup4
```

The following command can be used to install the Spotipy library

```
$ pip install spotipy --upgrade
```



## Built With

* [BeautifulSoup4](https://beautiful-soup-4.readthedocs.io/en/latest/#) - Used to scrape the Billboard Hot 100 songs 
* [Requests](https://pypi.org/project/requests/) - Used to make HTTP requests to the Billboard Hot 100 at a given date
* [Spotipy](https://spotipy.readthedocs.io/en/2.19.0/) - Used to authenticate third party applications and allow access to a user's Spotify account
