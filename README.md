# node-express-sequelize-mongoose

This repository is a comparative and similarities between mongoose and sequelize.

Notes
Whenever we have a middleware, we need to use the "next()" method in order to prevent our application from stalling.

Authentication & Authorizations
Authentication is to ensure that a user that is signing in has already signed up on our application and his data is already in our database based on his unique email & password.

Authorization is use to protect certain routes which requires a user to be authenticated first before accessing a resource. This is good for business reasons/logic.

## HOW SEQUELIZE IS SIMILAR TO EXPRESS

Sequelize is similar to express and just express support many database engines such as mongodb, sequelize also support many database engines such as sqlite and postgres.
