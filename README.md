# WhatTheCrud

## Naming
Create, Get, Update, Remove

##Client

###Create
####Tasks
1. Validate before creating

####Test

###Get

####Search
#####Tasks
1. Create search view
1. Create search controller
1. Set up paging
1. Set up sorting
1. Set up filtering
1. Allow page size configuration(25, 50, 100)

#####Tests

###Update
####Tasks
1. Create update controller
1. Validate before updating
1. Update list view with the changed data

####Tests
  1. Valid updates are persisted
  1. List view is also updated
  1. Changing data and then canceling does not affect the original data
  1. Validation is run before updates are saved

###Remove
####Tasks
Confirm before deleting
Remove from list view after deleting

####Tests

##Server
###Create
#### Tasks
  1. Write the CreateMessage
  1. Write the CreateHandler
  1. Write validation
  
#### Tests

###Get
####Tasks

####Tests

###Update
####Tasks
  1. Write the UpdateMessage
  1. Write the UpdateHandler
  1. Write validation
  1. Check RowVersion before updating

####Tests

###Remove
####Tasks
  1. Write the RemoveMessage
  1. Write the RemoveHandler
  1. Write validation
  1. Check for dependent records
  1. Check RowVersion before removing

####Tests

##Database
###Tasks
1. Create entity
1. Write migration script

##Features

###Concurrency
  1. Last in wins
  1. Optimistic Concurrency

###Editing
  1. In-line
  1. Form

###Validation
  1. sync
  1. async
    
