# Creative Content Templates

- **youtube_transcript_to_blog.json**: This workflow converts a YouTube transcript to a blog post. It uses a webhook to trigger the workflow, splits the text, creates embeddings using OpenAI, and stores them in Pinecone. It then uses an Anthropic chat model to generate the blog post and appends the results to a Google Sheet.
