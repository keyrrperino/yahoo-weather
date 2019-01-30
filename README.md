# Yahoo Weather New API
Yahoo new weather api python wrapper

## Sample Usage

```python
import yahooweather

app_id = ''
client_id = ''
client_secret = ''


yahooweather = YahooWeather(app_id, client_id, client_secret)

response = yahooweather.request(params={
    'location': 'sunnyvale,ca',
    'format': 'json',
})

print response
```

