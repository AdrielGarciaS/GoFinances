# GoFinances

> Web application to financial control of incomes and outcomes values.

![client](https://github.com/AdrielGarciaS/GoFinances/blob/master/screenshot.png "Client")

## :computer: How Run

1 - Clone repository

```
git clone https://github.com/AdrielGarciaS/GoFinances.git

cd GoFinances\backend

yarn
```

2 - Configure server

```
server\ormconfig.json

"host": "YOUR_POSTGRES_HOST",
"port": YOUR_POSTGRES_PORT,
"username": "YOUR_POSTGRES_USERNAME",
"password": "YOUR_POSTGRES_PASSWORD",
"database": "NAME_YOUR_DATABASE"
```

3 - Run server: on folder GoFinances\backend
```
yarn dev:server
```

4 - With server running now let's start the client. On folder GoFinances\web:
```
yarn

yarn start
```

5 - Enjoy


Did by Adriel with :heart:
