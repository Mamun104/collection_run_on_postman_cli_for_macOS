# Collection Run On Postman Cli For macOS


## Technology and Tool Used
- Postman
- Visual Studio Code
- Terminal

## Prerequisites

- You must have installed Postman to your system
- Install Postman CLI

## Scenario of this project

- The user can create a user
- The user can create a user by id,name
- The user can get all users
- The user can get individual user by user id
- The user can update a user by user id
- The user can delete a user by user id

## API Documents

  https://documenter.getpostman.com/view/16548351/2s9Y5SWRC4

## what is postman cli

Postman CLI (Command Line Interface) is a tool that allows you to run Postman collections and environments from the command line, making it easy to automate and integrate API testing and monitoring into your development and CI/CD pipelines

## How to set up Postman CLI

### Step-1:

- Open the Postman
- Create a workspace
- Create a collection

### Step-2:

- Click the collection
  
  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/5ae3cde3-e3f8-492b-8ad8-58fb800a7fd9)

- then click the collection run button

  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/6ee1dab5-47e6-4fb8-87f5-d314543fa1fc)
- then click the automate run via cli

  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/2197efd6-e3ad-4022-ab71-02a7bb470b7c)
  
### Step-3

- then install postman cli from here

               https://learning.postman.com/docs/postman-cli/postman-cli-installation/#windows-installation

![image](https://github.com/Mamun104/collection_run_on_postman_cli_for_macOS/assets/78067017/e835d2f4-3db4-468c-96d5-363e081471ac)


- go to this location and copy and paste the mac intell instalation command

- open the terminal
- hit the commmand

          curl -o- "https://dl-cli.pstmn.io/install/osx_64.sh" | sh

- after postman cli install then generate a api key

![Screenshot 2023-08-21 at 10 37 00 AM](https://github.com/Mamun104/collection_run_on_postman_cli_for_macOS/assets/78067017/adf76bed-5cb2-434f-a9fb-8c82823c79c2)

- click the add api key and after generate api key then copy this api key 

- then login with this command in cmd

              postman login --with-api-key {{xyz}}
  
- after login successfully then hit this command in cmd

![Screenshot 2023-08-21 at 10 41 47 AM](https://github.com/Mamun104/collection_run_on_postman_cli_for_macOS/assets/78067017/494e5194-f340-48a2-9d9b-d6e5d0d479f5)



             postman collection run {{collection_key}}

  
  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/b05fae3a-3b00-48bb-b75c-4c59ed3de8b1)
