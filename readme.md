# PostgreSQL Storage for Dashboard

Install this module to use [PostgreSQL](https://postgresql.org) for data storage.

You will need to launch with additional configuration variables:

  STORAGE_ENGINE=@userdashboard/storage-postgresql
  DATABASE_URL=postgres://localhost:5432/database

To test this module use [Dashboard](https://github.com/userdashboard/dashboard)'s test suite configured with this storage engine.

# Dashboard

Dashboard is a NodeJS project that provides a reusable account management system for web applications. 

Dashboard proxies your application server to create a single website where pages like signing in or changing your password are provided by Dashboard.  Your application server can be anything you want, and use Dashboard's API to access data as required.

Using modules you can expand Dashboard to include organizations, subscriptions powered by Stripe, or a Stripe Connect platform.

- [Developer documentation home](https://userdashboard.github.io/developers/)
- [Administrator documentation home](https://userdashboard.github.io/administrators/)
- [User documentation home](https://userdashboard.github.io/users/)

#### Development

Development takes place on [Github](https://github.com/userdashboard/storage-postgresql) with releases on [NPM](https://www.npmjs.com/package/@userdashboard/storage-postgresql).

#### License

This is free and unencumbered software released into the public domain.  The MIT License is provided for countries that have not established a public domain.
