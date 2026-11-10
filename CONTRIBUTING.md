# Contributing to Pooler

Thanks for wanting to help! Pooler is a small, solo-maintained carpooling app, and every issue, idea and pull request is genuinely welcome. You don't need to be an expert. Beginners are encouraged.

## Getting started

Fork this repo and clone your fork. Install dependencies with `npm install --legacy-peer-deps`. Create a `.env` file using the environment variables listed in the README. Sync the database with `npx prisma generate` followed by `npx prisma db push`. Then start the dev server with `npm run dev` and open http://localhost:3000.

Prefer containers? Run `docker-compose up --build` and everything starts together, including the database.

## Finding something to work on

Look for issues labelled "good first issue". If you have a new idea, please open an issue first so we can talk about it before you spend time on code.

## Making a pull request

Create a branch from main, for example `fix/ride-search-bug`. Keep each pull request small and focused on one thing. Run `npm run lint` before you push. In the PR description, explain what you changed and why, and add a screenshot if the UI changed.

## Reporting bugs

Please include what you did, what you expected, what happened instead, and your browser or Node version. Screenshots help a lot.

## Be kind

Be respectful and patient with each other. We are all here to learn and build something useful.
