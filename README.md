# Code Dev Hub

I have created this project but some features are not working properly. so add some new extraorinary features. and lectures are not working so make lectures available in app only. and add 500 most important problems from easy to hard in all programming languages. and make Ai tutor responses mor natural and impressive. and app theme should be more attractive like new microsoft background and also made features app more proffesional. and also make placement hub more proffessional not any vague look and also roadmap should be extraordinary like from beginer to advanced more easy to understand and also add top 15 mock interviews with natural and more human like mock interview. can you generate app freely.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/1c66c147-f4fa-4491-9788-bfb31005e998).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```

## Deploy to Vercel

Vercel builds the app with `npm run build`; Nitro is configured to generate Vercel output.
Set these environment variables in the Vercel project for every environment you use:

- `VITE_SUPABASE_URL` and `VITE_SUPABASE_PUBLISHABLE_KEY` for browser sign-in and data access.
- `SUPABASE_URL` and `SUPABASE_PUBLISHABLE_KEY` for server-side database requests.
- `LOVABLE_API_KEY` for AI tutor, resume optimization, and voice-interview AI features.

Add the deployed Vercel URL to the allowed sign-in redirect URLs for your auth project, and ensure its Google sign-in provider is enabled. Never expose private keys as `VITE_` variables.
