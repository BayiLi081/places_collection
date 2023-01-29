## Common Map Services

### Google Map API

1. Go to the [Google Maps Platform  | Google Developers](https://developers.google.com/maps)
2. Log in with Your Google Account
3. If using for first time, you need to tie to a billing account
4. Currently, trial tier is \$300, after trail, it will be \$200 per month (So after every scrape, check the billing report to make sure you don't exceed the free credits)
5. Go to the API keys, you might need to create a project in the first time

## Scraper 01: Collecting All the KFCs in Singapore

Before running the script, you might need to create a API which enables Places API, and copy the key number to replace the variable in the Python script.

```bash
api_key = "<__Your Google API Key__>" # Put your API key here
```

Run the KFCs_SG_scraper.ipynb with Python.