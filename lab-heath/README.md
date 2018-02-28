# LAB 32: Budget Tracker Continued

---
### Installing and How to use.

To install this program, place fork and 'git clone' this repo to your computer. From the terminal, navigate to  `lab-heath`. once there, install NPM but typing in , `nmp install` and after that, you will neex to install all the dependencies. do this by typing in `npm i`. 

next you need to have these scripts adjusted in your package.json file.

```javascript
"scripts": {
    "test": "jest",
    "watch": "webpack-dev-server --inline --hot"
  },
  ```

from there, you can go to your terminal and type, 

```javascript
node run build
```
this will build out a it builds the app by packaging it all up into a simple file for us to use later on.

to get a preview of your app. you need to run this command also.

```javascript
node run watch
```
once you have done that. you can go to your localhost:8080 and see your project in the browser.

---
## How to use

you have 2 input boxes that will take in a strings. this is a `title` and a `price`. you will have a button below that will submit the data into the app that will return an list item that will have the title, data made, and price.

you have a input area for a expense that you can enter in a title of a expense and a value of it. it will then create an new item that goes inside of that catagory. here you can a few different expense that will take away from the grand total of the catagory.

--- 


### Updating data
double clicking on the grey box of the category or the dark grey of the expense will open up that item so you can update the item.
--- 

### delete button
Just hit the delete button on either of the category or the expense it will remove that item from storage.

## test...

we have done testing for the 

* category-action file
* category-form file
* category-reducer file
* expense-action file
* expense-form file
* dashboard file




