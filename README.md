![Logo of the project](https://github.com/MagalhaesDev/Criando-um-hook-de-carrinhos-de-compras/blob/master/src/assets/images/logo.svg)

# Tennis Store

This application was developed in order to build a tennis store, with a shopping cart for selected items. Using react, typescript, and other cutting edge technologies.

## Technology 

Here are the technologies used in this project.

* React 17.0.1
* Typescript 4.1.2
* Styled-Components 5.2.1
* JSON-Server 0.16.3
* Axios 0.21.1

## Services Used

* Github.

## Getting started
 
1 - Run the command yarn in the terminal to download the dependencies.

2 - Run the command yarn server in the terminal, to start API

3 - Run the yarn start command in the terminal, to start the APP

## Functionalities

### 1 - This is the main page of the project <3 

![Homepage image](https://github.com/MagalhaesDev/Criando-um-hook-de-carrinhos-de-compras/blob/master/src/readme/home.png)

### 2 - Cart 

This cart component has the intention of storing the selected items and their quantity, all this integration is done with a communication from the client with the server where the search for the selected items and their stock is done, having several rules to be applied,  as the quantity not being greater than the stock, if the item really exists, among others.

![Cart](https://github.com/MagalhaesDev/Criando-um-hook-de-carrinhos-de-compras/blob/master/src/readme/cart.png)

### Show todos

* This functionality is of type GET and will display to the client the lists created by the user, passing through a middleware that will check if it is an existing account, if not it will return the status 404(not found).

### Update todo

* allows you to update the name and end date of todo. giving the code 400 (bad request) if the user is non-existent, and returning a JSON if everything is fine.

### Completed task

* This feature will set the todo to completed, returning the JSON of the task.

### Delete todo 

* This functionality of the HTTP delete method, will delete an existing todo, if all goes well it will return a JSON with the todo that remain, otherwise a 404 (Not Found) if the user does not exist.

## Links
  - Repository: https://github.com/MagalhaesDev/Todo-nodeJs
    - In case of sensitive bugs like security vulnerabilities, please contact
      mateusmagalhaesemidio@gmail.com directly instead of using issue tracker. We value your effort
      to improve the security and privacy of this project!

  ## Versioning

  1.0.0.0


  ## Authors

  * **Mateus Magalhaes Emidio** 

  Please follow github and join us!
  Thanks to visiting me and good coding!
