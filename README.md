# Shopify APIs Postman Collections (Updated 2024)

Updated Version for Postman Collection of the Shopify Admin API and the Shopify Storefront API

> [!WARNING]  
> Shopify is deprecating the REST Admin API as of October 1, 2024. You can still currently use their endpoints but you will need to eventually migrate to Graphql. [Follow this migration guide](https://shopify.dev/docs/apps/build/graphql/migrate).


## Table of Contents

- [Shopify APIs Postman Collections (Updated 2024)](#shopify-apis-postman-collections-updated-2024)
  - [Table of Contents](#table-of-contents)
  - [Web View](#web-view)
    - [Shopify Admin API](#shopify-admin-api)
    - [Shopify Storefront API](#shopify-storefront-api)
- [How to use it in Postman?](#how-to-use-it-in-postman)
  - [Web View Collections](#web-view-collections)
  - [Desktop View](#desktop-view)
  - [Fork it directly from the Web View collections.](#fork-it-directly-from-the-web-view-collections)
  - [Import it directly from this github repository.](#import-it-directly-from-this-github-repository)
  - [Download the collection files and import into Postman.](#download-the-collection-files-and-import-into-postman)
- [Where are my API Credentials?](#where-are-my-api-credentials)
- [Recommended GraphQL client for first-time users.](#recommended-graphql-client-for-first-time-users)
- [Collaboration](#collaboration)
- [Authors](#authors)

## Web View

### Shopify Admin API

| GraphQL\*                                                                                          | REST                                                                                                                    |
| -------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| [Collection](https://www.postman.com/muchisx/workspace/public/collection/6522230ecae43373c3e1a533) | [Collection](https://www.postman.com/muchisx/workspace/public/collection/30298405-b7b62c23-aab8-41fa-9721-c440548ae15b) |

### Shopify Storefront API

| GraphQL\*                                                                                          |
| -------------------------------------------------------------------------------------------------- |
| [Collection](https://www.postman.com/muchisx/workspace/public/collection/65317773ee1f5cf9a16a546d) |

<sub> \*_GraphQL not recommend to use via Postman Web. [I recommend this approach instead.](#recommended-graphql-client-for-first-time-users)_ </sub>

# How to use it in Postman?

These Collections [are using Collection Variables](https://learning.postman.com/docs/sending-requests/variables/), make sure to fill all the variables that you will use before launching requests!

For using it in your own Workspace you have multiple options:

## Web View Collections

As linked above, you can use these [Web View](#web-view) collections.

The variables that you define under the `Current value` input are stored only in your account, so you can safely use it from there.

> This will only work for the REST APIs for now, due to Postman only allowing GraphQL queries in the Desktop client.

## Desktop View

The variables that you define under the `Current value` input are stored only in your account, so you can safely use it from there.

## [Fork it directly](https://learning.postman.com/docs/collaborating-in-postman/using-version-control/forking-entities/) from the Web View collections.

Go to any collection in [Web View](#web-view) and click on fork. This should allow you to fork it directly into your Workspace.

> This will only work for the REST APIs for now, due to Postman only allowing GraphQL queries in the Desktop client.

## [Import it directly](https://learning.postman.com/docs/getting-started/importing-and-exporting/importing-from-git/) from this github repository.

> This will only work for importing the REST APIs for now, due to a Postman bug I haven't been able to export the GraphQL ones to add it here.

Go through the import process and it should automatically add it to your workspace.

## Download the collection files and import into Postman.

> This will only work for importing the REST APIs for now, due to a Postman bug I haven't been able to export the GraphQL ones to add it here.

The Postman Collection file is a JSON containing all information about each request.

Open Postman and import one of the files [from this folder:](/Postman%20Collections/)

- `Shopify Admin - REST.postman_collection.json`

# Where are my API Credentials?

In order to retrieve or create your private API Credentials, follow this link:

https://shopify.dev/docs/apps/auth/admin-app-access-tokens

# Recommended GraphQL client for first-time users.

If you're a first-time GraphQL user and just want to make mock requests to a store. I recommend you to start [here](https://www.shopify.com/partners/blog/getting-started-with-graphql).
In short, install the [GraphQL Shopify App](https://shopify-graphiql-app.shopifycloud.com/login?itcat=partner_blog&itterm=getting_started_with_graphql) in your store and do requests from there so you can learn the shape of the queries.

Alternatively, you can use Postman's GraphQL client in the Desktop version.

# Collaboration

Feel free to contribute if you believe there is something missing.

# Authors

Miguel Ángel (@muchisx)
