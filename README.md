# LLM-Prompting-Asking 
I used this template from Langchain tutoriel for create  a full stack RAG application for asking questions, getting answers. 
This a monorepo from https://github.com/bracesproul/monorepo-template

## Development

This monorepo uses Turborepo to manage the two packages (web, api).
To build all packages run `yarn build` from root.

To build a specific package run `yarn build --filter=<PACKAGE_NAME>`

To start the API server run `yarn start:api`.
Similarly, to start the web server run `yarn start:web`.

The API is an Express.js server written in TypeScript.
It comes with out of the box support for Supabase.
If you are not developing with Supabase, delete the `gen:supabase:types` script.
If you are using Supabase, replace the `<YOUR_PROJECT_ID>` placeholder with your project ID.

The web project is a default Next.js app with Tailwind CSS and TypeScript.

# Ressource 
https://www.youtube.com/watch?v=rQdibOsL1ps&t=2341s

THANK FOR THIS AMAZING TUTORIEL 
