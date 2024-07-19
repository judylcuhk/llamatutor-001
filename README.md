<a href="https://www.LlamaTeacher.com">
  <img alt="Llama teacher" src="./public/og-image.png">
  <h1 align="center">Llama Teacher</h1>
</a>

<p align="center">
  An open source AI personal tutor. Powered by Llama 3 70B & Together.ai.
</p>

## Tech stack

- Llama 3 from Meta for the LLM
- Together AI for LLM inference
- Next.js app router with Tailwind
- Serper for the search API
- Helicone for observability
- Plausible for website analytics

## Cloning & running

1. Fork or clone the repo
2. Create an account at [Together AI](https://dub.sh/together-ai) for the LLM
3. Create an account at [SERP API](https://serper.dev/) or with Azure ([Bing Search API](https://www.microsoft.com/en-us/bing/apis/bing-web-search-api))
4. Create an account at [Helicone](https://www.helicone.ai/) for observability
5. Create a `.env` (use the `.example.env` for reference) and replace the API keys
6. Run `npm install` and `npm run dev` to install dependencies and run locally
