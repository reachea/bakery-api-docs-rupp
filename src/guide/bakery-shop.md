# Bakery Shop

This is a step-by-step guide of our bakery shop api that we currently are using.

## List of Available Bakery Shops

In order to get all bakery shops, we need to use the api as follows:

```
/api/bakery-shops
```

## Detail of Specific Bakery Shop

In order to get a cetain bakery shop, we need to have a specific `:id` and use the api as follows:

```
/api/bakery-shop/:id
```

## Create a New Bakery Shop

In order to create a new bakery shop, we need to include params

`name`: type `string`

`thumbnail`: type `string`

`description`: type `string`

`phone_number`: type `string`

in the following api endpoint:

```
/api/bakery-shop/create
```

## Edit an Existing Bakery Shop

In order to edit an existing bakery shop, we need to have a specific `:id` and include params

`name`: type `string`

`thumbnail`: type `string`

`description`: type `string`

`phone_number`: type `string`

in the following api endpoint:

```
/api/bakery-shop/:id/update
```
