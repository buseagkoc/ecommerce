# ecommerce
This repository uses web scraping, data cleaning, and analytics to analyze Mondelez brand performance and customer trends. It includes scraping brand info, matching it to receipt data, tracking growth trends, and exploring customer retention. Ideal for retail analysts, data scientists, or anyone studying consumer behavior and brand insights.

 I built a Python scraper to grab brand names and descriptions directly from Mondelez’s website. The scraper digs into the site’s structure, pulls out the details, and cleans it up so it’s ready to use. 

I tackled matching items in messy receipt data to brands with a systematic approach—cleaning up brand names, dealing with abbreviations and variations, and matching them to receipt items without relying on error-prone fuzzy matching. I built pattern-learning tools to catch tricky cases and filter out unrelated stuff like non-food items.

I calculated growth trends for product categories, smoothed out seasonal noise, and focused on what’s really growing. Using normalized metrics and a 6-month moving average, I highlighted which product types (like candy or baking ingredients) are rising stars and which ones are steady revenue-makers.

Retention rates tell the story of customer loyalty. I tracked repeat purchases for the top 10 items to see which products keep customers coming back month after month. This is all about understanding what drives repeat engagement.

I explored how NLP techniques (like named entity recognition and semantic similarity) could make brand matching smarter and more flexible. There’s room to grow with better handling of package sizes, edge cases, and seasonal variations.
