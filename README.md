# fresh project

### Usage

Start the project:

```
deno task start
```

This will watch the project directory and restart as necessary.


### Set up your Application
> deno run -A --unstable npm:prisma init


### Create the database schema
Change db connection string in .env

> deno run -A --unstable npm:prisma db push

### Generate a Prisma Client for Data Proxy
> deno run -A --unstable npm:prisma generate --data-proxy
