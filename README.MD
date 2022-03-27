# Simple API Project on Go with Redis

## Introduction

This is my first project in golang that i'm already finish and publish, of course followin
this tutorial

https://www.youtube.com/watch?v=WVx0xavR9c8

I recommend for people who is beginner like me!

Project is based in call [Nominatim](https://nominatim.org/release-docs/develop/api/Search/) API 
with parameter `query` (q=<query>) and save the result on redis. 


## Running

```
docker-compose up --build
```

## Validate

### Linux

```
curl http://localhost:8080/api\?q=<query> -v | jq
```

Instead of `query` you put your city.
