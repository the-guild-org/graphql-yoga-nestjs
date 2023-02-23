<div align="center">
  <br />

  <h3>
    <a href="https://the-guild.dev/graphql/yoga-server">GraphQL Yoga</a> plugin for <a href="https://nestjs.com">NestJS</a>
  </h3>

  <h6>Fully-featured GraphQL server as a plugin for the progressive Node.js framework.</h6>

  <br />
</div>

## Getting started

### Install

```shell
npm i @nestjs/graphql graphql-yoga graphql @graphql-yoga/nestjs
```

### Create application module

```typescript
import { YogaDriver, YogaDriverConfig } from '@graphql-yoga/nestjs'
import { Module } from '@nestjs/common'
import { GraphQLModule } from '@nestjs/graphql'

@Module({
  imports: [
    GraphQLModule.forRoot<YogaDriverConfig>({
      driver: YogaDriver
    })
  ]
})
export class AppModule {}
```

#### Code first

TODO

#### Schema first

TODO

## Contributing

If this is your first time contributing to this project, please do read our
[Contributor Workflow Guide](https://github.com/the-guild-org/Stack/blob/master/CONTRIBUTING.md)
before you get started off.

Feel free to open issues, pull requests and create discussions. Community support is always welcome!

## Code of Conduct

Help us keep Yoga open and inclusive. Please read and follow our
[ of Conduct](https://github.com/the-guild-org/Stack/blob/master/CODE_OF_CONDUCT.md) as adopted from
[Contributor Covenant](https://www.contributor-covenant.org/).
