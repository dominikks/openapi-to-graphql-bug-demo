This is a demo for a possible bug in [OpenAPI-to-GraphQL](https://github.com/IBM/openapi-to-graphql).
Run it with
```
npm run demo
```

The output, for me, is as follows:
```
OpenAPI-to-GraphQL creation event error:  Cannot process schema '{"$ref":"#/components/schemas/repo","description":"Is present when the repo is a fork. Parent is the repo this repo was forked from."}'. Cannot identify type of schema.
```