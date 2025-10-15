# City-Population-Collector
## Configuration

Settings you can adjust before running the script:

```python
# CSV file with input cities. Must contain columns: "City" and "Country"
INPUT_FILE = "Cities.csv"

# CSV file to save results
OUTPUT_FILE = "Cities_with_population.csv"

# File used for caching already fetched city data
CACHE_FILE = "cache.db"

# User-Agent string for Wikidata requests (can include contact email or leave empty)
USER_AGENT = "CityPopulationCollector/1.0 (contact: none)"

# Minimum and maximum delay between requests (in seconds)
SLEEP_MIN = 0.3
SLEEP_MAX = 0.8

# Maximum number of retry attempts for network errors or API limits
MAX_RETRIES = 6
