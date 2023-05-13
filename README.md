# Aggregating_reviews
Aggregating reviews from multiple sources

General steps. We'll focus on APIs for this example, as they're more reliable and easier to work with. I'll use Python as the programming language, and we'll collect reviews from Google Maps and Bing Local Search.

Step 1: Setting up the environment

    Install Python (https://www.python.org/downloads/)
    Install required libraries: requests and pandas

    pip install requests pandas

Step 2: Register for API keys

    Google Places API: Follow the instructions here to enable the API and get an API key: https://developers.google.com/maps/gmp-get-started
    Bing Local Search API: Sign up for an API key here: https://portal.azure.com/#create/Microsoft.BingLocalSearch

Step 3: Collecting reviews

Create a Python script (e.g., aggregate_reviews.py) and add the Aggregating_reviews code:

Replace "YOUR_GOOGLE_API_KEY" and "YOUR_BING_API_KEY" with your respective API keys, and "Company Name" and "City, Country" with the target company's name and location.

Step 4: Run the script
Execute the script using the following command:

python aggregate_reviews.py
