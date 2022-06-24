# Cake

This is a step-by-step guide of our cake api that we currently are using.

## List of Available Cakes

In order to get all cakes, we need to use the api as follows:

```
/api/cakes
```

## Detail of Specific Cake

In order to get a cetain cake, we need to have a specific `:id` and use the api as follows:

```
/api/cake/:id
```

## Create a New Cake

In order to create a new cake, we need to include params

`name`: type `string`

`thumbnail`: type `string`

`description`: type `string`

`price`: type `integer`

`bakery_shop_id`: type `integer`

`cake_category_id`: type `integer`

in the following api endpoint:

```
/api/cake/create
```

## Edit an Existing Cake

In order to edit an existing cake, we need to have a specific `:id` and include params

`name`: type `string`

`thumbnail`: type `string`

`description`: type `string`

`price`: type `integer`

`bakery_shop_id`: type `integer`

`cake_category_id`: type `integer`

in the following api endpoint:

```
/api/cake/:id/update
```
