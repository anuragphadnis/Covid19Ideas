# COVID-19 Stats API

> Coronavirus Statistics Overview

This free API uses publicly available data about current confirmed cases, deaths, and recoveries of the COVID-19 virus AKA Coronavirus compiled by Johns Hopkins University. Accepts: country as filter parameter, otherwise returns all stats.

[See More here](https://rapidapi.com/KishCom/api/covid-19-coronavirus-statistics)

## Usage

```python
import requests

url = "https://covid-19-coronavirus-statistics.p.rapidapi.com/v1/stats"

querystring = {"country":"Canada"}

headers = {
    'x-rapidapi-host': "covid-19-coronavirus-statistics.p.rapidapi.com",
    'x-rapidapi-key': "SIGN-UP-FOR-KEY"
    }

response = requests.request("GET", url, headers=headers, params=querystring)

print(response.text)
```

> for usage in more languages kindly refer API page Code Snippet Section
