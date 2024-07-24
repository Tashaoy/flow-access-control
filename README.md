# Access Control on Flow

## Description
This is a project done on Flow. It explains the areas where different variables and functions can be accessed.

## Getting Started
### Structure
- Contracts : This folder contains the "Contract.cdc" contract, the contract contains four variables that can be read and modified in different areas, it also contains three functions that can be called in different areas.
- Scripts: This folder contains the "script.cdc" script

### Code Walkthrough
    - Variable a
        - Read Area 1,2,3,4 - Write Area 1,2,3,4
    - Variable b
        - Read Area 1,2,3,4 - Write Area 1
    - Varaiable c
        - Read Area 1,2,3 - Write Area 1
    - Varaiable d
        - Read Area 1       - Write Area 1
    - function publicFunc
        - Can be called in  Area 1,2,3,4
    - function ContractFunc
        - Can be called in Area 1,2,3
    - function PrivateFunc
        - Can be called in Area 1
 ## Authors
    Owoloko Joy
 ## License
    This project is Licensed under the MIT License
        

  
