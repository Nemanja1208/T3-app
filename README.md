## T3 App using Prisma, tRPC, Next.js with Typescript, Github Auth, Supabase, DaisyUI and Tailwind

Steps you need to do in order to test this app : 

0. Clone repo and install deps ```npm i```

1. Register/Log in to Supabase
2. Create database
3. Add URI of the database it to the ```DATABASE_URL``` in .env
4. Go to github setting/developer settings and create oAuth app and add both ```GITHUB_CLIENT_ID``` and ```GITHUB_CLIENT_SECRET``` to the .env file
5. Generate random secret with this command ```openssl rand -base64 32``` and add to .env ```NEXTAUTH_SECRET```

6. Start it with ```npm run dev``` and enjoy
