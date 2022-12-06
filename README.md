# E-commerce Backend

  ## Description
  Internet retail, also known as e-commerce, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit those like myself, practising as a full-stack web developer. This program demonstrates the backend of an e-commerce site, which uses the Express.js API and Sequelize to interact with a MySQL database including the e-commerce data. 
  
  ## Table of Contents 
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)
  - [Questions](#questions)

  ## Installation
   Below is an example of how you can download the project onto your own device:

  1. Open your devices terminal application
  2. Locate to the correct file destination that you are wanting to download this project to
  3. Clone the repository using this link: 
      ```md
          git clone https://github.com/squrpe/ecommerce-backend.git
      ```
  4. You may get prompted to input you github details, thus do so. Otherwise, the project will now be succesfully installed onto your device.

  This project contains:
  - Javascript
  - Node.js
  - MySQL
  - Insomnia

  You will need to download the suitable extensions listed above to run the application in the command line and test it.

  ## Usage

Using the command line, follow these steps to seed your database and start up your server using your own credentials:

    npm i
    mysql -u root -p

Whilst in the mysql command line, create the database using these lines of code:

    source db/schema.sql;
    quit;
    
Then change the details in your .env file to your own and using these commands, you will seed your database and start the server:

    npm run seed
    npm start

## Testing

To test wether the program is working correctly, the database was ran through Insomnia. Below is an example of the program:

  ![](./assets/E-Commerce%20Backend.gif)

  [You can also access the example video by clicking here](https://drive.google.com/file/d/1HsO-PjvHvUqmvvVT4CR4SgC_GjHo8Fvh/view)


  ## Questions:
  If you have any questions, contact me here:
  - Email: squrpe@example.com

  And if you want to see my additonal work, check out my Github:
  - Github: [squrpe](https://github.com/squrpe)