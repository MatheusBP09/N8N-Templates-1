# Productivity Templates

- **morning_briefing_email.json**: This workflow sends a morning briefing email. It uses a webhook to trigger the workflow, splits the text, creates embeddings using Cohere, and stores them in Supabase. It then uses an Anthropic chat model to generate the email and appends the results to a Google Sheet.
