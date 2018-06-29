## About ##
This project takes advantage of my [React-Redux-Router Start Kit](https://github.com/LegoGao/boilerPlate). Setting up full react / redux / react-router structure takes less than one minute. Front end uses React+Redux+React-Router+Fetch. Back end uses Express(A Node.js framework) to mock REST APIs. There are more than 10 page routers and more than 20 react components. User is able to locate current city, login, browse restaurants, search for restaurants, save a restaurant, add to cart, and write comments for restaurants. This is a relatively complete front end project.

## Features ##
- User Login / Logout
- Locate your city
- Change city
- Browse restaurants
- Infinitely load more restaurants
- Search by category
- Search by key words
- Restaurant details page
- Save restaurant
- Add restaurant to cart
- Write review/ comment to a restaurant you purchased

## Tech Stack ##
- [React-Redux-Router Start Kit](https://github.com/LegoGao/boilerPlate)
- React to structure project with react components
- Redux to manage react states
- React Router for page routing
- Fetch to handle backend REST API
- Express to set up back end server
- Webpack for module bundler
- Less to write organized CSS code

## Demo


## Run locally
```
Run server first:

git clone https://github.com/LegoGao/React-Yelp.git

cd React-Yelp

npm install --save

npm run mock
```

```
Run client:

cd React-Yelp

npm start

Visit http://localhost:8080
```

# Project Structure

```
.
├── app                            后端接口
|    ├─ actions                       运行配置
|    ├─ components                            静态资源
|    ├─ config
|    ├─ constants
|    ├─ containers
|    ├─ fetch
|    ├─ reducers
|    ├─ router
|    ├─ static
|    ├─ store
|    ├─ util
|    ├─ index.jsx
├── mock                      全局组件
|    ├─ detail
|    ├─ home
|    ├─ orderList
|    ├─ search
|    ├─ server.js
├── test                         路由
├── .babelrc                           vuex
├── package.json                        全局样式
├── webpack.config.js                           页面
.

```
