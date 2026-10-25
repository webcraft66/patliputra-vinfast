PATLIPUTRA VINFAST WEBSITE

Open index.html in Chrome to preview (internet needed for the 3D libraries).
Chat: rule-based answers work everywhere. The AI answers need the api/ folder deployed on Vercel.

Deploy on Vercel
1. Upload this whole folder (index.html, images/, api/) to a GitHub repository.
2. vercel.com > Add New > Project > import it. Framework: Other. No build command.
3. Project Settings > Environment Variables: add ANTHROPIC_API_KEY (from console.anthropic.com). Redeploy.
4. Set a monthly spend limit in the Anthropic console. Each AI answer costs a small amount.
Keep the facts in api/chat.js in sync with index.html (prices, offers, contact).
