# Education Templates

- **daily_student_motivation.json**: This workflow sends daily motivational messages to students. It uses a webhook to trigger the workflow, splits the text, creates embeddings using OpenAI, and stores them in Weaviate. It then uses an OpenAI chat model to generate the messages and appends the results to a Google Sheet.
- **quiz_auto_grader.json**: This workflow automatically grades quizzes. It uses a webhook to trigger the workflow, splits the text, creates embeddings using Cohere, and stores them in Pinecone. It then uses an OpenAI chat model to grade the quizzes and appends the results to a Google Sheet.
