### Install Shopify CLI

[Shopify CLI](https://shopify.dev/docs/api/shopify-cli)

### Create a shopify.theme.toml and add this code.( This is when you have the theme just in shopify so you need to downloaded first for that follow the next steps.)

```
[environments.development]
store = "https://sophytoys.myshopify.com/"
```
and run this command
```
shopify theme pull -e development
```

to run on local
```
shopify theme dev -e development
```

