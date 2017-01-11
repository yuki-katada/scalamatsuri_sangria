# ScalaMatsuri Sangria
Sample Application for GraphQL in Scala (ScalaMasturi 2017), using GraphQL Scala Library "Sangria".

![thumbnail/aja_logo_color_bk.png](thumbnail/aja_logo_color_bk.png)

# Usage
```
> git clone git@github.com:yuki-katada/scalamatsuri_sangria.git
> cd scalamatsuri_sangria
> sbt run
```
Access to `http://localhost:1234/graphql` to check server is properly started.

# API

### Host (Single Endpoint)
```[POST] http://localhost:1234/graphql```
### Header
```Content-Type: application/json```

### Sample Request Body
```
{
   "query": "{ user(id: 1) { id name  } }"
}
```

# Slide
I will upload my slide after ScalaMasturi 2017.
