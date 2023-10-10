.env

```
DATABASE_URL=postgres://localhost/<DB_NAME> // URL of your database
TOKEN_SECRET=<SECRET> // Signature for signing JWT's
CLIENT_SECRET=<CLIENT_SECRET> // Facebook app secret
CLIENT_ID=<CLIENT_ID> // Facebook client ID
FACEBOOK_APP_ID=<FACEBOOK_APP_ID> // Facebook app ID
```
```
$ npm install
$ npm install -g knex // database connection wrapper - you probably don't have this
```
```
$ knex migrate:latest
```

```
$ npm run dev
```

#### Docker

```
TOKEN_SECRET=<SECRET> // Signature for signing JWT's
CLIENT_SECRET=<CLIENT_SECRET> // Facebook app secret
CLIENT_ID=<CLIENT_ID> // Facebook client ID
FACEBOOK_APP_ID=<FACEBOOK_APP_ID> // Facebook app ID
```

```
$ docker-compose up
```
