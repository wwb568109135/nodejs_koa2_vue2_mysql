# nodejs_koa2_vue2_mysql

A fullstack demo used Vue2 & Koa2(nodejs_koa2_vue2_mysql)

:sunny: Easy to setup and learn

:100: Api test coverage

:rocket: Instant feedback 


![Todolist](http://7xog0l.com1.z0.glb.clouddn.com/vue-koa-demo/todolist-5.gif 'todolist')

### Install（安装相关）
`git clone `

`npm install`

`mysql config`

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

### Run（运行）

> Node.js support. **You need to create a `.env` file as above**.

### Node.js（环境）

Beacuse of using Koa2, `Node.js >= v7.6.0` is needed.

#### Development（开发环境） 

`npm run dev`
`npm run server`

open browser: `localhost:8080`

> tips: login password is 123

#### Production（生产环境）

`npm run start` 

open browser: `localhost:8889`

> tips: login password is 123


## License（协议）

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2018 Jerry


