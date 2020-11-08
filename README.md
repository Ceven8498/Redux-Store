# Redux Shop

# Description
Example of how to manage global state using React’s Context API with an open-source JavaScript library called Redux.

![Github license](http://img.shields.io/badge/license-MIT-blue.svg)

## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Resources](#resources)
  * [Questions](#questions)

## Installation
Download a copy of this repo to a directory of your choice. To install, you will need to run `npm i` or `npm install` to get all the dependencies running. Following proper installation of the dependencies, you will then add the seeds by typing `npm run seed` followed by `npm start` on the root directory terminal to start the server.

To stop the server you will need to use the existing terminal to execute `CTRL+C` followed by `Y` for confirmation to terminate the connection to localhost.

Please see documentation on your own host's server commands should you run this on a live instance rather than locally.

## Usage
Be sure all repository files were successfully cloned to server and a connection to the database is complete.

Interactive Live Demo: https://aqueous-mesa-67588.herokuapp.com/

![Demo Shot 0](src/../client/src/assets/redux000.png)

Customers will have the ability to create an account through a signup form found on the `Navigation Bar` located at the top of the webpage. Utilization of the `Navigation Bar` will help customers select shopping items for purchase. 

![Demo Shot 1](src/../client/src/assets/redux001.png) ![Demo Shot 2](src/../client/src/assets/redux002.png) ![Demo Shot 6](src/../client/src/assets/redux006.png) 

When an item is viewed, shoppers have the ability to add it to their cart. Customers have the ability, and extra bonus if they do so, to signup for an account to checkout orders with the intention of preserving their shopping history.

![Demo Shot 3](src/../client/src/assets/redux003.png) 

Once items are stored in the cart, customers will be able to checkout via Stripe before being redirected back to the `Shop-Shop` website. 

![Demo Shot 4](src/../client/src/assets/redux004.png)

Once a customer is ready to complete their retail experience, they can select `Cart` to make final decisions on which items to purchase from their shopping cart. Any unwanted items can be removed from the cart at this time. Customers may also resume their shopping experience at any time should they chose so.

 ![Demo Shot 5](src/../client/src/assets/redux005.png) 

Customers will be able to review items as they checkout with Stripe before entering their payment information. Stripe will handle the transaction and email their receipt. However, items purchased also remain viewable in the customer's profile. Once payment processing concludes, shoppers are redirected to the `Shop-Shop` website.

## License
![Github license](http://img.shields.io/badge/license-MIT-blue.svg) This project is covered by the MIT license.

## Contributing
At this time, I am not seeking contributions to this application for `Shop-Shop`.

## Resources
[![](src/../client/src/assets/nodejs.png)](https://nodejs.org/en/) [![](src/../client/src/assets/express.png)](https://www.npmjs.com/package/express)

[![](src/../client/src/assets/bootstrap.png)](https://www.npmjs.com/package/bootstrap) [![](src/../client/src/assets/apollo.png)](https://www.npmjs.com/package/apollo-server-express)

[![](src/../client/src/assets/mongodb.png)](http://wwww.mongodb.com/) [![](src/../client/src/assets/graphql.png)](https://www.npmjs.com/package/graphql)

[![](src/../client/src/assets/react.png)](https://www.npmjs.com/package/react) [![](src/../client/src/assets/reactscripts.png)](https://www.npmjs.com/package/react-scripts) 

[![](src/../client/src/assets/reactboot.png)](https://www.npmjs.com/package/react-bootstrap) [![](src/../client/src/assets/reactrouter.png)](https://www.npmjs.com/package/react-router-dom) 

[![](src/../client/src/assets/stripe.png)](https://www.npmjs.com/package/stripe) [![](src/../client/src/assets/heroku.png)](https://www.heroku.com) 

[![](src/../client/src/assets/jsonwebtok.png)](https://www.npmjs.com/package/jsonwebtoken)

## Questions
Please contact Devmadia by clicking below for immediate questions regarding site content:

[![Devmadia](src/../client/src/assets/Logo.png)](https://devmadia.github.io/)

For other projects by Devmadia [click here](https://github.com/Devmadia)