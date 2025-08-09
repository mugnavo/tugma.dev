# varo.dev

> [!IMPORTANT]  
> We're grateful to the Cebu tech community for recognizing this project's potential when it won the Cebu Hacktoberfest 2024 Hackathon. 
>
> As of August 2025, we've decided to discontinue varo.dev and will not be continuing development.
>
> While this project is no longer active, we encourage you to check out [oss.now](https://oss.now) (not affiliated with us), which shares a similar vision and already has an active community.
>
> Thanks for following along.

The AI-powered matchmaking platform for developers, open-source projects, and indie hackers.

Built with [Nuxt](https://nuxt.com), [Vue](https://vuejs.org), and [Vercel AI SDK](https://sdk.vercel.ai/).

## Development

> Node.js 20 or later is recommended.

1. Install [pnpm](https://pnpm.io/installation).
2. Install the necessary dependencies by running `pnpm install` in the root directory of the project.
3. Create a fill in your `.env` file based on the `.env.example` file.

    ```env
     NUXT_BASE_URL="http://localhost:3000"
     POSTGRES_URL=

     NUXT_GITHUB_CLIENT_ID=
     NUXT_GITHUB_CLIENT_SECRET=
     NUXT_GITHUB_REDIRECT_PATH="/api/auth/github"

     NUXT_SESSION_PASSWORD=
     NUXT_GOOGLE_GENERATIVE_AI_API_KEY=
    ```

4. Run the development server with `pnpm dev`.
5. You can now access the development server at `http://localhost:3000`.

## Contributing

Please read our [Contributing Guidelines](./CONTRIBUTING.md) before starting a pull request.

## License

[GPL-3.0](LICENSE)
