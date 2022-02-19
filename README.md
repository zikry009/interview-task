# Interview Task

Here is the full problem statement link https://brick-trowel-748.notion.site/Interview-Task-17476cb16d6d413ab792fdec1de2a7fc.

# Problem  Statement Summary

1. Use the json file to display all the data in a table
    1. Filters should act like this
        1. First dropdown which contains all the column name of the table
        2. Second dropdown should contain the filter type (Equals, Includes etc.) 
            1. Filter type should change according to the type of the column i.e if I select string column filter type should change to string etc.
        3. Third text input - whatever I write will get matched with particular column I selected
        
2. Implement Filters to filter the data
    1. String Filters
        1. Here you are supposed to filter the user list by all the string fields using 2 matchers
            1. Equals
            2. Includes
    2. Numeric Filters
        1. Here you are supposed to filter the user list by numeric fields using 2 matchers
            1. Greater than
            2. Less than
    3. Date Filters
        1. Again
            1. Greater than
            2. Less than
            
    
    Notes: 
    
    - filters should be responsive, if I change value in any filter it should update all data
    - User can apply multiple filters, all filters will be applied with **AND** condition
        - Bonus points if user can switch between **AND** & **OR** filter type
    - Filters should be clearable, I can clear any filter
    


# Installation

```sh
npm install
```
# Run 

```sh
npm run serve
```
