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
      1. Set up paging
      1. Set up sorting
      1. Set up filtering
      1. Allow page size configuration(25, 50, 100)

    #####Tests
    
  ####Single

###Update
####Tasks
1. Validate before updating

####Tests
  1. Valid updates are persisted
  1. List view is also updated
  1. Changing data and then canceling does not affect the original data
  1. Validation is run before updates are saved

###Remove
####Tasks

####Tests

##Server
###Create
#### Tasks
  1. Validate before creating
  
#### Tests

###Get
####Tasks

####Tests

###Update
####Tasks

####Tests

###Remove
####Tasks
1. Confirm before removing

####Tests

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
    
