ANIME AI - PHONE DEPLOY VERSION

This version is prepared for Netlify. It does not need Termux to deploy.
After deployment, add these Netlify environment variables:
AI_API_KEY = your provider API key
AI_BASE_URL = your provider's OpenAI-compatible /v1 endpoint
AI_MODEL = your provider's model name

Keep API keys in Netlify environment variables, never in index.html.
