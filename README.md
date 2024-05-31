
# Unriddle Take Home Test 1 Version 2

This is a Note Taking Text Editor App powered with AI. I've used NextJS App Router, MongoDB for storing the notes, Pinecone DB for vector embedding, Vercel AI SDK for streeaming text response in the chat, Clerk for authenticate the application, TailwindCSS for beautiful UI layout. Finally, I used TypeScript to write this app.

Using ShadcnUI, it also has dark and light theme. Zod and React-Hook-Form for form validation.



## Deployment

To deploy this project run:

```bash
  npm run install
  npm run dev
```


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file.

`DATABASE_URL=`

`NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=`
`CLERK_SECRET_KEY=`
`NEXT_PUBLIC_CLERK_SIGN_IN_URL=`
`NEXT_PUBLIC_CLERK_SIGN_UP_URL=`
`NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=`
`NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=`

`OPENAI_API_KEY=`

`PINECONE_API_KEY=`


