# Cake Category

This is a step-by-step guide of our cake category api that we currently are using.

## List of Available Cake Categories

In order to get all cake categories, we need to use the api as follows:

```
/api/cake-categories
```

## Detail of Specific Cake Category

In order to get a cetain cake category, we need to have a specific `:id` and use the api as follows:

```
/api/cake-category/:id
```

## Create a New Cake Category

In order to create a new cake category, we need to include params

`name`: type `string`

`description`: type `string`

in the following api endpoint:

```
/api/cake-category/create
```

## Edit an Existing Cake Category

In order to edit an existing cake category, we need to have a specific `:id` and include params

`name`: type `string`

`description`: type `string`

in the following api endpoint:

```
/api/cake-category/:id/update
```
