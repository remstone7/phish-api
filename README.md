# Phish API Python Wrapper


## Instructions

`pip install phish`

`from phish.api import Phish`

### you can get an api key from here: https://api.phish.net/

`phish_api = Phish(API_KEY)`

## accessible methods

```
# returns list of phish artists
phish_api.artists()

returns attendancefor specific shows
phish_api.attendance()

# blog posts from phish.net 
phish_api.blog()


```