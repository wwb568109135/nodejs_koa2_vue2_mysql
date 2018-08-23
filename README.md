# vue-koa-demo

A fullstack demo used Vue2 & Koa2

:sunny: Easy to setup and learn

:100: Api test coverage

:rocket: Instant feedback 



![Todolist](http://7xog0l.com1.z0.glb.clouddn.com/vue-koa-demo/todolist-5.gif 'todolist')


`git clone `

`npm install`

Also you need to install MySQL & create a database named `todolist`,and execute 2 sql files `list.sql` & `user.sql`.Their are in `sql/`

After that, create a `.env` file and set the database username & password:

```env
# your database username
DB_USER=XXXX
# your database
DB_PASSWORD=YYYY 
# Koa is listening to this port
PORT=8889
```

If you want to run the test for the Project, please create a `.env.test` file to face this situation:

```env
# your database username
DB_USER=XXXX
# your database
DB_PASSWORD=YYYY 
# The port which is listened by koa in the test environment
PORT=8888
```

### Run

> Node.js & Docker support. **You need to create a `.env` file as above**.

### Node.js

Beacuse of using Koa2, `Node.js >= v7.6.0` is needed.

#### Development: 

`npm run dev`
`npm run server`

open browser: `localhost:8080`

> tips: login password is 123

#### Production:

`npm run start` 

open browser: `localhost:8889`

> tips: login password is 123


## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2018 Jerry


