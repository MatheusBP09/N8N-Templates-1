# Data Analytics Templates

- **competitor_price_scraper.json**: This workflow scrapes competitor prices. It uses a webhook to trigger the workflow, splits the text, creates embeddings using OpenAI, and stores them in Supabase. It then uses an Anthropic chat model to process the data and appends the results to a Google Sheet.
