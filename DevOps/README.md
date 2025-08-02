# DevOps Templates

- **github_commit_jenkins.json**: This workflow triggers a Jenkins job on a GitHub commit. It uses a webhook to trigger the workflow, splits the text, creates embeddings using OpenAI, and stores them in Supabase. It then uses an OpenAI chat model to process the data and appends the results to a Google Sheet.
