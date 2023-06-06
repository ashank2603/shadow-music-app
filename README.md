# Shadow Music App

How to run:

- Clone the repository.
- Open the directory in a terminal and run <code>npm install</code>
- Create a supabase instance by following this [doc](https://supabase.com/docs/guides/getting-started/tutorials/with-nextjs).
- Create a .env.local file and put the following in it:
```bash
NEXT_PUBLIC_SUPABASE_URL = "<YOUR_SUPABASE_INSTANCE_URL>"
NEXT_PUBLIC_SUPABASE_ANON_KEY = "<YOUR_SUPABASE_ANON_KEY>"
SUPABASE_SERVICE_ROLE_KEY = "<YOUR_SUPABASE_SERVICE_ROLE_KEY>"
```
- Now run <code>npm run dev</code> in the terminal.

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Screenshots

Login/Signup Page
![image](https://github.com/ashank2603/shadow-music-app/assets/61231703/9b4be917-4aca-4b5d-bae0-c0e3f8bd7e6a)

Home Page
![image](https://github.com/ashank2603/shadow-music-app/assets/61231703/16f56879-a7f0-4a5d-b2e0-7f051a0b325b)
