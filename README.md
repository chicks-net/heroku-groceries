# heroku groceries

shared grocery list to run in Heroku

## purpose

We are just trying to learn more python and databases so 
don't expect to run millions of grocery lists with this code.

## data model

*family* contains *list* which contain *item*

* family
  * contains *list*
  * has attributes
    * email addresses
* list
  * contains *item*
  * has attributes
    * name
* item
  * has attributes
    * name
    * quantity

## REST API 

as yet undefined:

* adding items to lists
* marking items off of lists
* creating lists
* deleting lists


### GET /lists

Return the lists that you currently have access to.

#### URL

`/lists.json`

#### endpoint metadata

| item | details |
| ------- | ------- |
| Response formats | JSON |
| Requires authentication? | Not yet! |

#### paramaters

none

#### example request

`/lists.json`

#### example response

TODO: fill in


### GET /items

Return the items for a given list

#### URL

`/items.json`

#### endpoint metadata

| item | details |
| ------- | ------- |
| Response formats | JSON |
| Requires authentication? | Not yet! |

#### paramaters

`list =` *listid*

Which list do you want items for?

#### example request

`/items.json?list=1234`

#### example response

TODO: fill in


### GET /db_initialize

Initialize the database

#### URL

`/db_initialize.json`

#### endpoint metadata

| item | details |
| ------- | ------- |
| Response formats | JSON |
| Requires authentication? | Not yet!  Oh no! |

#### paramaters

None

#### example request

`/db_initialize.json`

#### example response

TODO: fill in
