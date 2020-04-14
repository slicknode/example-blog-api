# Multi-User Blog CMS

This is a multi-user blogging application with a serverless GraphQL API powered by [Slicknode](https://slicknode.com). 

## Installation

To launch the backend in the Slicknode cloud, clone the repository and deploy it
with the [Slicknode CLI](https://github.com/slicknode/slicknode) (`npm install -g slicknode@latest`):

```shell script
git clone https://github.com/slicknode/example-blog-api.git
cd ./example-blog-api

slicknode deploy
```

To add content via the CMS, open the console from within the project directory:

    slicknode console

To explore the GraphQL API:

    slicknode playground

## Connecting a Client

You can connect any client application to this backend via the GraphQL API. (React, Vue, Angular, iOS etc.)

[Setup your Client](https://slicknode.com/docs/client-setup/)

## Customization

To learn how to extend and customize this backend, checkout the [Slicknode documentation](https://slicknode.com/docs/).

You can for example just change the schema of the blog (`modules/blog/schema.graphql`) and redeploy
the changes to the cloud:

    slicknode deploy

Some more pointers for getting started:

-   [Data Modeling](https://slicknode.com/docs/data-modeling/introduction/)
-   [Writing Extensions](https://slicknode.com/docs/extensions/)
