# Server

#### Using Apollo + GraphQL + MongoDB + Express

install dependencies

`yarn`

Start MongoDB Server

`mongod`

Start project server

`node app.js`

Open GraphQL Explorer on http://localhost:8080/graphiql

Try submitting a query:
```
query {
  president(name: "George Washington") {
    name
    term
    party
  }
}

```


# Client

install dependencies

`yarn`

run project

`react-native run-ios` or `react-native run-android`
