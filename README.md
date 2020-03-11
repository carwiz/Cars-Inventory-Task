# Cars Inventory Task
Welcome to the Cars Inventory application exam. This app is simple web application that allows customers to manage their cars inventory, with an easy, user friendly interface.

Your technological stack will be:
* Frontend: React.js
* Backend: Node.js
* Database / Persistent storage solution of your choice

You can use any general purpose libraries, however, please note, you will be required to add additional functionality after you finish the project, when choosing libraries, keep that in mind.

Example of things you can (only if you _like to_, it's just an example) use:
[express](https://expressjs.com/),
[axios](https://github.com/axios/axios),
[material-ui](https://material-ui.com/)

And of course - any boilerplate you want. for example:
[create-react-app](https://github.com/facebook/create-react-app)


# Instructions

You're required to build a Web-Application with the pages below.

## List of Pages
 * [Cars List Page](#cars-list-page)
 * [Car Upload Page](#car-upload-page)
 * [Car Edit Page](#car-edit-page)

### Cars List Page
This page will include a list of all cars in the inventory.

In addition, the page will include a link to upload a new car.

The list of cars is a table with the following columns:
 1. Car id
 2. Manufacturer Name (Ex. Hyunday, Nissan, Etc.)
 3. Model Name (I10, I20, Micra, Etc.)
 4. Year 
 5. Price 
 6. A column with an Edit Car Page (next to each car's row)
 7. A link to Car Upload Page.

List Example:

| Car Id | Manufacturer Name | Model Name | Year | Price| Edit |
|:-------:| --------------- | ------------- | ------------- | ------------- | ------------- |
| 1       | Hyundai   | i10 | 2011 | 42,000 | [Edit](#car-edit-page) |
| 2       | Toyota   | Yaris | 2014 | 55,000 | [Edit](#car-edit-page) |
| 3       | Mazda   | 2 | 2012 | 122,000 | [Edit](#car-edit-page) |


### Car Upload Page
In this page the user will fill a form with all the car details. The field types are:
* Car id - string
* Manufacturer Name - string
* Model Name - string
* Year - integer
* Price - integer


### Car Edit Page
In this page, the user can edit his inventory. The allowed operations are:
1. Change car's price
2. Delete car from inventory


## Before Submitting
* Make sure to use clean code.
* The website should be responsive
* Make use of tools that will help you with standtard [formatting](https://prettier.io/) and [linting](https://eslint.org/).
* Your data should be presistent and well structured. When choosing a storage mechanism, consider it's pros and cons, use whatever suites the problem at hand, use proper entities and relations. (You can choose whatever storage solution you like)
* You might be required to explain your implementation, make sure you understand all your code.

## Submitting your project
After you've completed your tasks, and you are ready to submit it, do the following:
* Create a git repositry (preferably on github.com)
* Make sure all the code is committed and pushed
* Make sure you added a markdown file (`README.md`) with instructions on how to run your project from scratch, that must include any operations that is required in order to run the project (i.e. setup a database, create tables, etc.)
* Deploy your work to be viewed from any computer (you can find simple free deployment in [heroku](https://www.heroku.com/), but you can also find one in Amazon, Google, Azure and more).
* Clone your repo and use your instructions to see it works as expected
* Add `carwiz-amit` as user to the repo (Master permission)
* Send us an email with your repo link to `amit@cariwz.co.il` and `or@carwiz.co.il` 

Please contact `amit@cariwz.co.il` or `or@carwiz.co.il` for any questions.
