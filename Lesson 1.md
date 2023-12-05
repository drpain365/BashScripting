# Symbols in Bash

These allow you to redirect, modify, and change the output of your commands

## Symbols mean things in programming

  - `!` means `NOT`

  - `=` means `EQUAL`

Symbols can be put together as well.

  - `!=` means `NOT EQUAL`

## Arithmetic Operations

Here are some of the basics:

  - `+` means `PLUS`

  - `-` means `MINUS`

  - `/` means `DIVIDE`

  - `*` means `MULTIPLY`

  - `>` means `GREATER THAN`

  - `<` means `LESS THAN` 

  #### Example
  
  - if `3>=1` then
      - Means if 3 is `GREATER OR EQUAL TO`
   
## Bash symbols are unique in the sense that they are often used with a command...

and its called...

# echo

The `echo` command is 90% of your scripting career.  

echo is essentially a command to take text and put it somewhere.

### Command Breakdown
- `echo "content" (method) [location]`

## Content

Just a string/content

**Example :**  `potato hihihihihihi`

## Location

Just a filepath

**Example :**  `/home/cork/test.txt`

## Methods (SPECIFICALLY FOR ECHO)

darn.txt will be a file that we use to demonstrate the effect of different methods.

### **darn.txt:**
  - ```
     I EAT
     potato cronch
     cramming for essays
    ```


`>` put into file AND REPLACE EVERYTHING. 

  - **_Example:_** `echo "hihi" > darn.txt`
    
    **darn.txt:** becomes

    ```
    hihi
    ```

`>>` add to the END of a file. 

  - **_Example:_** `echo "hihi" >> darn.txt`
    
    **darn.txt:** becomes

    ```
     I EAT
     potato cronch
     cramming for essays
     hihi
    ```

