# Government & NGO Templates

- **public_form_auto_triage.json**: This workflow automatically triages public forms. It uses a webhook to trigger the workflow, splits the text, creates embeddings using Cohere, and stores them in Supabase. It then uses an Anthropic chat model to triage the forms and appends the results to a Google Sheet.
- **public_record_email_update.json**: This workflow sends email updates for public records. It uses a webhook to trigger the workflow, splits the text, creates embeddings using Cohere, and stores them in Pinecone. It then uses an OpenAI chat model to send the updates and appends the results to a Google Sheet.
