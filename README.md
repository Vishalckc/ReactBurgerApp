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
Get/Post using axios instance along with Google Firebase as a backend 

## Error Handling Included
Using WrappedComponent (higher order components) for error handling

## Dynamic checkout form added

## Using Firebase as backend
1. Create a new project in Google firebase https://console.firebase.google.com/u/0/
2. Go to cloud firestore and create a new db (set read, write rules to true)
3. After creating DB, use the firebase db-url you get (e.g https://react-my-burger-dd884.firebaseio.com/) to replace the POST query in the burger-app POST method

4. Also Import this json file in your firebase DB:
```
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


```
