# ChatGPT-API Demo
It is act like Sherlock Holmes and you can chat with him. It is created with using [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) and [ChatGPT-API](https://platform.openai.com/docs/guides/chat). You can change character name and character from in `.env` file.

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
4. If you want to change character, you can change it in `.env`
    ```
    PUBLIC_CHARACTER=Sherlock Holmes
    PUBLIC_CHARACTER_FROM=BBC Sherlock
    ```
5. Run the app
    ```shell
    npm run dev
    ```
    
## Deploy With Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Femreisik95%2Fsherlock&env=OPENAI_API_KEY&envDescription=OpenAI%20API%20Key&envLink=https%3A%2F%2Fplatform.openai.com%2Faccount%2Fapi-keys&env=PUBLIC_CHARACTER&envDescription=Public%20Character%20Name&envLink=https%3A%2F%2Fgithub.com%2Femreisik95%2Fsherlock%2Fblob%2Fmain%2FREADME.md&env=PUBLIC_CHARACTER_FROM&envDescription=Public%20Character%20From&envLink=https%3A%2F%2Fgithub.com%2Femreisik95%2Fsherlock%2Fblob%2Fmain%2FREADME.md&project-name=sherlock&repo-name=sherlock)

## License

MIT
