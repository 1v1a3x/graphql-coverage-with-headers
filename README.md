# graphql-coverage-with-headers
!!! It's The fork of repository [graphql-coverage](https://github.com/IvanGoncharov/graphql-coverage) 


## Install

    npm install -g graphql-coverage-wh
or

    yarn global add graphql-coverage-wh


## TL;DR

Show which resolvers are triggered by your GraphQL queries:

    graphql-coverage-wh <URL to your API> <Header Name> <Header value>

Example:

    graphql-coverage-wh https://graphql.com/graphql x-api-key s3cr37
