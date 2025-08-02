# Healthcare Templates

- **appointment_whatsapp_notify.json**: This workflow sends a WhatsApp notification for an appointment. It uses a webhook to trigger the workflow, splits the text, creates embeddings using OpenAI, and stores them in Supabase. It then uses an OpenAI chat model to generate the notification and appends the results to a Google Sheet.
