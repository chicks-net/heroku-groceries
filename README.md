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

### GET /lists

Return the lists that you currently have access to.

#### URL

`/lists.json`

#### endpoint metadata

Response formats | JSON

#### paramaters

none

#### example request

`/lists.json`

#### example response

TODO: fill in
