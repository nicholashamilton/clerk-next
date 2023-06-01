# Clerk Next 

### Set Up 

Install dependencies 
```
npm install
``` 

Run dev server 
```
npm run dev
``` 

Preview production build 
```
npm run build && npm run start
``` 

### Create `.env.local` from `.env.local.example` 

```
cp .env.local.example .env.local
```

### Clerk Configuration 

Replace variables with [clerk configuration](https://clerk.com/docs/nextjs/get-started-with-nextjs) 

`NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=` 

`CLERK_SECRET_KEY=` 

`NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in` 

`NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up` 

`NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/` 

`NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/` 
