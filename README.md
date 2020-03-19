## USDA Market Scraper

This tool scrapes the USDA Community Supported Agriculture database of [farmer's markets](https://search.ams.usda.gov/farmersmarkets/) and [on-farm markets](https://search.ams.usda.gov/onfarmmarkets/). The results are merged into either CSV or JSON.

Pre-scraped copies of the data are [available here](https://abrie.github.io/usda-csa-scraper).

## Requirements

jq, yarn, python3, curl, make

## Run

- `source bin/activate` : Activate python3 virtual environment.
- `yarn install` : Install dependencies.
- `make all`: Scrape, process, and merge.
- Results are stored in `out/merged/merged.csv` and/or `out/merged/merged.json`
