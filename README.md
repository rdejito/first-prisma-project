## Day 1 Learning Prisma

- Progress
  - Performed Basic CRUD Operation in Prisma
    1.  Created a user and a post using `create()`.
    2.  Read/Look for specific values using `findFirst`/`findMany()`.
    3.  Updated a specific users value using `update()`.
    4.  Deleted a value using `delete()`.

### How to use?

If you'd like to try, download the code above, zip it.
Or you can clone it in your local. Choose your pick.

After you've done it, run `npm install` to install the dependencies for the code.

```
  npm install
```

If you've ever encounter some problems. Feel free to read the official docs about Prisma

You can use `SQLite` or `PostgreSQL`.
_Note: For this you need PostgreSQL installed._

Then create an .env file with this inside:

```
DATABASE_URL="postgresql://username:randompassword@localhost:5432/mydb?schema=public"
```

`username`: your postgresql username
`randompassword`: the password of your username
`port`: the port of your database
`mydb`: name of your database

After `npm install`, you could try running the script.ts using:

```
npm run dev
```

Or maybe you want to change it? Feel free to edit your `package.json`.

After all of those, you need to install prisma
```
npm install prisma @types/pg --save-dev
npm install @prisma/client @prisma/adapter-pg pg dotenv
```

If you want start fresh? Refer to the official docs.
