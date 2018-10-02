# LucidCV

<img align="right" title="CV" src="./lucidcv.png">

LucidCV is a simple CV maker which collects data from the user and creates a CV for the user.
You can select the CV theme that you need and after creating the CV you can download a copy of it.
Those who wish to contribute are welcome :smile: .

## How to setup locally

* Install nodejs and npm
* run `git clone https://github.com/aswinzz/LucidCV.git`
* Enter into the cloned folder
* run `sudo npm install`
* run `sudo npm start`
* Go to `localhost:3000` in your browser

## How It Works

The user enters the data and after the form is submitted a json file is created and depending on the selected theme and the json data CV is prepared.

- File Structure :
  * The folder `Public` contains the css,javascripts and images needed for the website
  * The folder `Views` contains the code of homepage and cv templates,they are in ejs format(embedded javascript). 
    - index.ejs : contains the code for homepage which contains the form that takes the details of the users.I have used materialize css as the frontend framework.
    - resume.ejs : What this code does is, format the json data obtained from the user into a CV.
  * The folder `routes` contains a file `index.js` this file creates the json file when the user submits the form using a POST request and formats the resume.ejs file.

## TODO

* See todo.md for features to be added

## Contributors
Are you Interested in Making Contributions to this project? Checkout set of Instructions to about [contributing](https://github.com/aswinzz/LucidCV/blob/master/how_to_contribute.md)

Happy Contributing 😊 

