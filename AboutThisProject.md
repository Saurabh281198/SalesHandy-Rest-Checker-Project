### Introduction
In this project, a lightweight automation framework has been built to write API Automation test cases fast and assert them easily. 

### Directory & File structure 
In this project, it has one directory that contain all the endpoints in the form of `.json` as described below. 

├── api-automation
│   ├── endpoints               → directory which contains all the endpoints  
|   │   ├── getUsers.json       → Request json file to get all the users endpoint 
|   │   ├── getSingleUser.json  → Request json file to get a single user endpoint 
|   |   └── createUser.json     → Request json file to create a  new user 

Example endpoints json files are attached under the `endpoints/` directory. 

 
### Framework

- This Framework is able to test all the endpoint one by one under the `endpoints/*` directory.
- Every assertions mentioned in `endpoints/**.json` file has been asserted and tested.
- Framework is able to generate request **dynamically** based on the configuration mentioned under `endpoints/**.json` file >> `request` key.
- If a new configuration file will be added under `endpoints/*` framework it will automatically run the assertions as per mentioned in the configuration without writing an additional line of code.
- It has been made sure that every line of code is clean, well-commented, and self-explanatory. Code is scalable & maintainable in the long run.
