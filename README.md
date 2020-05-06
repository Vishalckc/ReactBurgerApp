## REACT Burger Builder App Tutorial

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

## Project Demo:
![GitHub Logo](https://github.com/Vishalckc/ReactBurgerApp/blob/master/public/images/burger.PNG?raw=true)

![GitHub Logo](https://github.com/Vishalckc/ReactBurgerApp/blob/master/public/images/Burger-Mobile.PNG?raw=true)

![GitHub Logo](https://github.com/Vishalckc/ReactBurgerApp/blob/master/public/images/Burger-Mobile-SideDrawer.PNG?raw=true)

## Overview
- A reactive and playful Burger application. Give life to your website by using this baseline react app!!

* For PR/Feature request, create a new issue
## Booting the application
1) npm install (Node Package manager should be installed)
2) npm start (runs on default http://localhost:3000)

## Http Support Added
Get/Post in with Google Firebase backend 

## Error Handling Included
Using WrappedComponent higher order components for error handling

## Using Firebase as backend
1 Create a new project in Google firebase
2 Create a new db (set read, write rules to true)
3 After creating DB, use the firebase db url (e.g https://react-my-burger-dd884.firebaseio.com/) to replace post query in axios post method
4 Lastly import this JSON, or create your own json if necessary
---------------------------------------------------------------
{
  "ingredients" : {
    "bacon" : 0,
    "cheese" : 0,
    "meat" : 0,
    "salad" : 0
  },
  "orders" : {
    "-M6epqxNeujM7euan7e0" : {
      "customer" : {
        "address" : {
          "country" : "UK",
          "street" : "This street",
          "zipcode" : "000000"
        },
        "email" : "test@test.com",
        "name" : "Joe Hahn"
      },
      "deliveryMethod" : "fastest",
      "ingredients" : {
        "bacon" : 1,
        "cheese" : 0,
        "meat" : 0,
        "salad" : 1
      },
      "price" : 5.2
    }
  }
}
--------------------------------------------------------

