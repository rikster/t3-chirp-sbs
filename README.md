# T3 Stack

Messing with the [T3 Stack](https://create.t3.gg/) project bootstrapped with `create-t3-app`.

Original Github Repo: https://github.com/t3dotgg/chirp

Deployed version of this app: https://xn--uo8h.t3.gg/

- use Window - period to select emojis:  
    
        🪟 - .

Youtube Video: https://www.youtube.com/watch?v=YkOSUVzOAA4

## Tech used

- [Next.js](https://nextjs.org)
- [NextAuth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [Tailwind CSS](https://tailwindcss.com)
- [tRPC](https://trpc.io)

## Services deployed to
<p>All have great free-tears</p>

- Clerk [https://clerk.com/?utm_campaign=theo-dtc](https://clerk.com/?utm_campaign=theo-dtc)
- Planetscale [https://planetscale.com/?ref=theo](https://planetscale.com/?ref=theo)
- Upstash [https://upstash.com/?utm_source=theo_qstash](https://upstash.com/?utm_source=theo_qstash)
- Vercel [https://vercel.com/?ref=theo](https://vercel.com/?ref=theo)
- Axiom [https://www.axiom.co/?ref=theo](https://www.axiom.co/?ref=theo)
## Setting up and deploying
   
First scaffold the app:
  
    npx create-t3-app@latest

Choose:

 1. typescript
 2. skip nextAuth (will replace w/ Clerk)
 3. tailwind
 4. trpc

Run dev (locally)

*note: will not work w/o .env variables (DATABASE_URL, CLERK_SECRET_KEY, etc)
```
npm run dev
```
  

Build (goes into ./.next dir)

```
npm run build
```

Start the build
```
npm run start
```

Deploy

[Vercel Deployment](https://create.t3.gg/en/deployment/vercel) 



# Learn More

To learn more about the [T3 Stack](https://create.t3.gg/), take a look at the following resources:

- [Documentation](https://create.t3.gg/)
- [Learn the T3 Stack](https://create.t3.gg/en/faq#what-learning-resources-are-currently-available) — Check out these awesome tutorials

You can check out the [create-t3-app GitHub repository](https://github.com/t3-oss/create-t3-app) — your feedback and contributions are welcome!

## How do I deploy this?

Follow our deployment guides for [Vercel](https://create.t3.gg/en/deployment/vercel), [Netlify](https://create.t3.gg/en/deployment/netlify) and [Docker](https://create.t3.gg/en/deployment/docker) for more information.




