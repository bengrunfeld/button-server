# Button Server

Server for the button game.

## To run locally

-   Clone site with `git clone`
-   `cd button-server`
-   `npm install`
-   `npm run now`


## Database access

In the project root, create a `.env` file and fill in the values. E.g.

```
MYSQL_HOST="hostUri"
MYSQL_USER="username"
MYSQL_PASSWORD="password"
MYSQL_DATABASE="dbName"
```

## Serverless Functions

### Incoming

- Add webhook info to DB
- Add User account info to DB
- Fetch current game info from DB
- If no current game exists, create new game in DB
- Send current game info to all webhook endpoints

### Outgoing

