# HR Templates

- **new_job_application_parser.json**: This workflow parses new job applications. It uses a webhook to trigger the workflow, splits the text, creates embeddings using OpenAI, and stores them in Pinecone. It then uses an OpenAI chat model to parse the applications and appends the results to a Google Sheet.
- **notion_job_board_poster.json**: This workflow posts jobs to a Notion job board. It uses a webhook to trigger the workflow, splits the text, creates embeddings using OpenAI, and stores them in Supabase. It then uses an OpenAI chat model to post the jobs and appends the results to a Google Sheet.
