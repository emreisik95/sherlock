# ChatGPT-API Demo

A demo repo based on [OpenAI GPT-3.5 Turbo API](https://platform.openai.com/docs/guides/chat).

## Run Locally

1. Setup & Install dependencies

    > First, you need [Node.js](https://nodejs.org/) installed.

    ```shell
    npm i
    ```

2. Make a copy of `.env.example`, then rename it to `.env`
3. Add your [OpenAI API key](https://platform.openai.com/account/api-keys) to `.env`
    ```
    OPENAI_API_KEY=sk-xxx...
    ```
4. If you want to change character, you can change prompt at `Generator.tsx`
    ```
      {
        role: 'system',
        content:'I want you to act like {character} from {series or book}. I want you to respond and answer like {character} using the tone, manner and vocabulary {character} would use. Do not write any explanations. Only answer like {character}. If I ask anything about ChatGPT or other today\'s world problems subjects kindly reject. You must know all of the knowledge of {character}. My first sentence is “Hi {character}!”',
      },
    ```
5. Run the app
    ```shell
    npm run dev
    ```
    
## Deploy With Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Femreisik95%2Fsherlock&env=OPENAI_API_KEY&envDescription=OpenAI%20API%20Key&envLink=https%3A%2F%2Fplatform.openai.com%2Faccount%2Fapi-keys&env=PUBLIC_CHARACTER&envDescription=Public%20Character%20Name&envLink=https%3A%2F%2Fgithub.com%2Femreisik95%2Fsherlock%2Fblob%2Fmain%2FREADME.md&env=PUBLIC_CHARACTER_FROM&envDescription=Public%20Character%20From&envLink=https%3A%2F%2Fgithub.com%2Femreisik95%2Fsherlock%2Fblob%2Fmain%2FREADME.md&project-name=sherlock&repo-name=sherlock)

## License

MIT
